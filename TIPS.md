# Git & GitHub tips

## 1. Create and switch branches in one step

`git switch -c my-branch` creates `my-branch` and switches to it.

## 2. Fix the last commit message

`git commit --amend` reopens the last commit so you can fix its message or add a forgotten file (only before you push).

## 3. Park unfinished work with stash

`git stash` sets aside uncommitted changes; `git stash pop` brings them back.

## 4. See the whole history as a graph

`git log --oneline --graph --all` draws every branch and merge in the terminal.

## 5. Throw away local changes to a file

`git restore path/to/file` discards uncommitted edits to that file.

## 6. Find the commit that broke something

`git bisect start`, then mark commits `good`/`bad`, and Git binary-searches for the first bad one.

## 7. Credit pair programmers in commits

Add `Co-authored-by: Name <email>` as the last line of a commit message to credit everyone who worked on it.

## 8. Open a PR straight from the terminal

`gh pr create --fill` opens a pull request using your commit message as the title and body.

## 9. Edit a repo in the browser

Press `.` on any GitHub repo page to open it in the github.dev editor.

## 10. Recover commits you thought were lost

`git reflog` lists everywhere HEAD has been, so you can get back to commits after a bad reset or rebase.
