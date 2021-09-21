1. Reset : On the commit-level, resetting is a way to move the tip of a branch to a different commit. Meanwhile revert: Reverting undoes a commit by creating a new commit.
2. Git rebase moves a feature branch into a master. Git merge adds a new commit, preserving the history.
3. git stash pop throws away the stash after applying it, whereas git stash apply leaves it in the stash list for possible later reuse.
4. Interactive rebasing can be used for changing commits in many ways such as editing, deleting, and squashing.