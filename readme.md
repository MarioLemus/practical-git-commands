# Useful git commands guide

## Notes

- "{ }" means a space that you should replace
- rm -fr .git: deletes a git initialization in a folder

**_git rm {filename}:_** deletes a file from your repo

**_git pull:_** updates the data in your local repo due to some changes in the remote repo

**_git branch:_** lists all available branches

**_git branch {new branch name}:_** sets a new branch

**_git branch --delete {branch name}:_** deletes an existing branch from local repo

**_git push origin --delete {nombre-de-la-rama}:_** deletes an existing branch from remote repo

**_git checkout {branch name}:_** switchs to other branch

**_git reflog --relative-date:_** get logs of your branches and its modifications (helps when need to rollback to a specific version of your app)

**_git reset --hard {commit id}:_** direclty rollsback to a previous version (commit id, is taken from "git reflog")

**_git commit --amend -m "":_** edits an incorrect commit message that hasn't been yet pushed

**_git merge "branch to be merged":_** it merges branches, to apply this command is needed to switch first to your main branch

**_git clone -b "branch name"  "repo link":_** it clones a specific branch repo


## Git merge steps

**_git switch "destination branch":_** you have to switch from whatever branch to main (because main or any other branch you want, is gonna become the fundamental base where to merge)

**_git merge "providing branch"_:** merge the providing branch into the base one

**_git commit -m "mssg"_:** create a commit message for the merge process

**_git push origin "base branch"_:** in this case the base branch is "main"
