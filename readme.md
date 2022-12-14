# Useful git commands guide

## Notes

- "{ }" means a space that you should replace
- rm -fr .git: deletes a git initialization in a folder

**_git rm {filename}:_** deletes a file from your repo

**_git pull:_** updates the data in your local repo due to some changes in the remote repo

**_git branch {new branch name}:_** sets a new branch

**_git checkout:_** shows available working branches

**_git reflog --relative-date:_** get logs of your branches and its modifications (helps when need to rollback to a specific version of your app)

**_git reset --hard {commit id}:_** direclty rollsback to a previous version (commit id, is taken from "git reflog")

**_git commit --amend -m "":_** edits an incorrect commit message that hasn't been yet pushed
