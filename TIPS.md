# Git & GitHub tips

## 1. Create and switch branches in one step

`git switch -c my-branch` creates `my-branch` and switches to it.

## 2. Fix the last commit message

`git commit --amend` reopens the last commit so you can fix its message or add a forgotten file (only before you push).

## 3. Park unfinished work with stash

`git stash` sets aside uncommitted changes; `git stash pop` brings them back.
