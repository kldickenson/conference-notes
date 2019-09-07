GIT ALIASES

To see the aliases in your git config:
git config --global --list | grep alias



GIT FETCH --prune
https://git-scm.com/docs/git-fetch


GIT REFLOG
https://git-scm.com/docs/git-reflog


GIT CLEAN
https://git-scm.com/docs/git-clean

Destructive command (deletes untracked files, INCLUDING files in .gitignore) with interactive:
git clean -xfdi --dry-run  === git clean -xfdn

if you want the clean to ignore the .gitignore files (no -x):
git clean -fdn



GIT RESET
Takes commit OUT of history
https://git-scm.com/docs/git-reset



GIT REVERT - provide the hash of the actual commit you want to "reverse", it will stay in the history

https://git-scm.com/docs/git-revert

git revert xxxxxx


GIT REBASE
https://git-scm.com/docs/git-rebase

You can use "rebase" on your own branch to do a "squash"!

git rebase -i start-hash end-hash

Change "pick" to "squash", "pick" the first (most recent) and "squash" the older hashes.
You might have to create a new branch to see.


GIT CHERRY PICK
https://git-scm.com/docs/git-cherry-pick


GTI TAG -a (annotated, ie. V2.0)  -m "message"