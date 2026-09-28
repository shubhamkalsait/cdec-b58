# GIT

## What is Git?

## Git Commands:
```shell
git init # initialize vcs in present working dir
git status # to check VCS status
git log # check previous versions / commits
git log --oneline # Check previous commits in short
git add <filename> # Add File in staging area
git add . # add all changes from PWD into staging area
git commit # Create new commit version
git commit -m "<MESSAGE>" # create new commit with message
git revert <COMMIT_ID> # to revert the commit with new commit
git restore --staged <FILENAME> # to unstage the changes / to remove changes from staging area
git restore <FILENAME> # undo untracked changes
git config --global user.name "shubhamk" # update user name signature (username)
git config --global user.email "sk@cbz.com"  # update user email signature (useremail)
git branch # list branches
git branch <BRANCHNAME> # create new branch
git checkout <BRANCHNAME> # switch branch
git checkout -b <BRANCHNAME> # create branch if not exist and switch
git fetch origin <BRANCH> # fetch changes from remote repo
git merge <BRANCH/COMMITID> # Merge fetched changes to current branch
git pull origin main # Pull commits from remote repo. PULL = FETCH + MERGE.
git remote add origin <URL> # add remote repo connection in local repo
git push origin main --set-upstream # Push commits from local repo to remote repo if branch is not available at remote repo
git push origin main # Push commits from local repo to remote repo
git clone <URL> # download the complete repo into local system
git diff <BRANCH/COMMIT> # Show difference between current branch and given branch or commit
git reset <COMMITID> # remove the commits and revert to previos commits

```
