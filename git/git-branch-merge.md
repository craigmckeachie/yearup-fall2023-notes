# Git Branch Merge

## Creating Branch and Checking It Out

```
git branch feature-about
git checkout feature-about
```

OR

```
git checkout -b feature-about
```

OR

```
git switch -c feature-about
```

## View Branches

```
git branch
```

> Lists the branches

## Merging Branch

```
git checkout main
git merge feature-about
```

## Cleanup

```
# deletes locally
git branch -d feature-about
```

```
// delete branch remotely
git push origin --delete feature-about
```
