# erlang
* In erlang, you can do `X = 1. X = 1.`. This looks like a reassignment, but it isn't; once the variable is bound, it's a pattern match. I finally grokked this when I came across this bit of code: `same(X,X) -> true. same(_,_) -> false.`.

# git
* `git add -p` Add, prompting for each change.
* `git pull --rebase` Pull using rebase instead of merge to include remote changes.
* `git stash -p` Stash, prompting for each stashed change.

# vim
* `:e!` Reloads the current file with changes from disk.
