# Git Command Reference

- git clone: Use this to download an existing remote repository from GitHub onto your laptop.
- git switch: Use this to move between branches or create a new branch with the -c flag.
- git add: Use this to stage new or modified files before creating a commit.
- git commit: Use this to save a permanent snapshot of your staged changes to branch history.
- git commit --amend: Use this to fix a typo in your last commit message or add forgotten edits to it.
- git push: Use this to upload your local branch commits to your GitHub repository.
- git push --force-with-lease: Use this to safely update a remote branch after rebasing or amending without overwriting others' work.
- git pull: Use this to download the latest commits from GitHub and merge them into your current local branch.
- git merge: Use this to combine changes from another branch into your current branch.
- git restore: Use this to discard uncommitted edits in a file and revert it to the last committed state.
- git reset --soft: Use this to undo recent commits while keeping the file changes staged for a new commit.
- git reset --hard: Use this to completely delete recent commits along with all uncommitted changes in your working folder.
- git reflog: Use this to view all recent pointer movements and recover commits lost after a hard reset.
- git stash: Use this to temporarily shelf uncommitted changes so you can switch branches with a clean folder.
- git stash pop: Use this to reapply your most recently stashed changes back into your working files.
- git rebase: Use this to move your branch commits onto the tip of main for a clean, linear history.
- git revert: Use this to safely undo an earlier commit on a shared branch by creating a new inverse commit.
