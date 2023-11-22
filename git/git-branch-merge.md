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
# delete branch remotely
git push origin --delete feature-about
```

## Exercise 1
1. Create new repository commit main branch.
2. Create a feature branch.
3. Change into the feature branch.
4. Make changes in the feature branch.
5. Commit those changes
6. Change back into the main branch
7. Merge the feature branch into your main branch

## Exercise 2
1. Change into the feature branch.
1. Make changes in the feature branch.
1. Commit those changes
1. Change back into the main branch
1. Change the same line of code that you changed in the feature branch to something different than what you did in the feature branch
1. Commit the changes
1. Merge the feature branch into your main branch
1. Resolve the conflict





