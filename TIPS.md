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
