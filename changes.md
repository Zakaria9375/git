# Changes

## Uncommitted changes in branch before switching

```shell
git stash

git switch -c new-branch

git stash apply

// apply and remove
git stash apply pop
```

## Uncommitted Changes no need

```shell
git reset --hard

```

## Rebase to specific commit

```shell
// any changes will be discarded
git reset --hard commit-id

// any changes will be saved
git reset --soft commit-id

git revert <commit-hash>
// keeping history and rebase to specific commit

git push --force
```
