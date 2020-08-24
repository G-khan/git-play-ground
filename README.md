# git-play-ground
Git Playground

> Squash Commit 1

> Squash Commit 2

> Squash Commit 3

> Squash Commit 4

    git rebase --interactive HEAD~4
    

    871adf Commit 1    --- newer commit --┐
    0c3317 Commit 2                       |-- Join these into one
    87871a Commit 3                       |
    643d0e commit 4    -------------------┘
    6394dc Another Feature

[Source](https://www.internalpointers.com/post/squash-commits-into-one-git)

new thing for local commit