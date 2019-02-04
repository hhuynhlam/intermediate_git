## Common Useful Commands
- [git pull --rebase](https://www.atlassian.com/git/tutorials/syncing/git-pull)
- [git diff](https://www.atlassian.com/git/tutorials/saving-changes/git-diff)
- [git reset --hard](https://git-scm.com/docs/git-reset#git-reset---hard)
- [git cherry-pick](https://git-scm.com/docs/git-cherry-pick)
- [git rebase](https://www.atlassian.com/git/tutorials/rewriting-history/git-rebase)
- [git reflog](https://www.atlassian.com/git/tutorials/rewriting-history/git-reflog)
- [git gc](https://git-scm.com/docs/git-gc)
- [git bisect](https://hackernoon.com/understanding-git-bisect-i-e-use-binary-search-to-find-the-change-that-introduced-a-bug-89489b4c9fa6)

## Tips
### Don't:
1. Put everything in one commit.
1. Write incomplete commit messages. (unless rewrite)
1. Break something. Committing. Fixing it later. (unless rewrite)
1. Rewriting without checking the state of each commit.
1. Rewriting history on public branches

### Do:
1. Commit often to private branches.
1. Rebase private branch frequently with public base branch.
1. Ensure every commit on a public branch passes all checks (lint, tests, etc.).
1. Curate your commit history.

### Further Reading
1. [Keeping a Linear Git History](http://www.bitsnbites.eu/a-tidy-linear-git-history/)
1. [Graph Theory](http://think-like-a-git.net/)
