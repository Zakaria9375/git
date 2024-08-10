# Git Cheat Sheet

## Everyday Commands

```shell
git status -s
// D deleted, ?? Untracked, M modified, A added

git add .

git commit -m "msg"

// to view history
git log --oneline --all --graph

// restore last commit for modified filed
git restore .

// undo to last commit deleting untracked files
git clean -fd

```

## Links

- [working with Remote Repos](./remote.md)
- [handling changes and commit](./changes.md)
- [working with branches](./branches.md)
