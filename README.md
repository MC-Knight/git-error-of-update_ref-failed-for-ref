# git-error-of-update_ref-failed-for-ref

###cd $(git rev-parse --show-toplevel) >if necessary
###rm -rf .git/refs/remotes/origin >remove all origin/*
###mkdir .git/refs/remotes/origin >create empty origin/
###git fetch origin >repopulate origin/*
