# git-error-of-update_ref-failed-for-ref

### cd $(git rev-parse --show-toplevel) > if necessary <br />
### rm -rf .git/refs/remotes/origin > remove all origin/* <br />
### mkdir .git/refs/remotes/origin > create empty origin/ <br />
### git fetch origin > repopulate origin/* 
