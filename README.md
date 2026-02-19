# Useful git commands
Update local branch list
```
git remote update origin --prune
```

Delete all local branches except master
```
git branch | grep -v '^*' | xargs git branch -D
```
