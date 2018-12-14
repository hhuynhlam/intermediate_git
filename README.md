# Intermediate GIT
Private Branch
Public Branch
HEAD
Graph
Merge Bubble
Fast-Forward
Squashing

git bisect
git cherry-pick
git rebase
git reflog
git pull --rebase

.gitconfig

Git Commit Messages

Don't:
1. Put everything in one commit.
1. Write incomplete commit messages. (unless rewrite)
1. Break something. Committing. Fixing it later. (unless rewrite)
1. Rewriting without checking the state of each commit.
1. Rewriting history on public branches

Do:
1. Commit often to private branches.
1. Rebase private branch frequently with public base branch.
1. Ensure every commit on a public branch passes all checks (lint, tests, etc.).
1. Curate your commit history.
