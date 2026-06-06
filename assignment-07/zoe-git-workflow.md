# Assignment 07: Git Workflow

## Student Name
Zoe

## Repository
cse632-0526-

## Branch Name
feature/zoe-assignment-07

## Commands Practiced
- git clone
- git remote -v
- git config user.name
- git config user.email
- git checkout -b
- git status
- git add
- git diff --staged
- git commit
- git push
- git fetch
- git merge
- git log
- git rev-parse HEAD

## Directories Created
- assignment-07/
- assignment-08/
- final_project/

## Git Remote Output
origin	https://github.com/zoezhang-svg/cse632-0526-.git (fetch)
origin	https://github.com/zoezhang-svg/cse632-0526-.git (push)

## Git Status Output
On branch feature/zoe-assignment-07
Changes to be committed:
	new file:   assignment-07/zoe-git-workflow.md

## Pull Request URL
https://github.com/zoezhang-svg/cse632-0526-/pull/1
## Latest Commit Hash
[Temporary Placeholder]

## Merge Conflict Summary
To simulate a merge conflict, I created two branches ('readme-conflict-a' and 'readme-conflict-b') that edited the exact same line in README.md. After merging Branch A directly into main via GitHub, Branch B became conflicted. I ran 'git fetch' and 'git merge origin/main' while on Branch B to pull the conflicting changes down locally. I resolved the conflict by removing the Git markers ('<<<<<<<', '=======', '>>>>>>>') and editing the first line to read '# CSE632 Assignment 07 Git Practice'. Finally, I staged the resolved file and committed the changes to finish the merge.

## Reflection
This assignment provided a practical look into how Git structures parallel development using branches. By utilizing separate branches, I learned that new features can be constructed safely without risking the stability of production code on the main branch. Working with 'git add' and reviewing with 'git diff --staged' reinforced the concept of the staging area as a clean drafting space where changes are audited prior to making them a permanent part of the project history. Creating a Pull Request illustrated the collaborative process of introducing feature work back into a shared codebase. Lastly, manually handling the merge conflict demystified how Git handles overlapping modifications, proving that conflicts are intentional safety checkpoints rather than errors.
