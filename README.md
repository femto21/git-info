# git-info

## create a new repository on the command line
```
git init
```
```
git add .
```
```
git commit -m "first commit"
```
```
git branch -M main
```
```
git remote add origin https://github.com/<OWNER_NAME>/<REPOSITORY_NAME>.git
```
```
git push -u origin main
```

## push an existing repository from the command line

```
git remote add origin https://github.com/<OWNER_NAME>/<REPOSITORY_NAME>.git
```
```
git branch -M main
```
```
git push -u origin main
```

## Mergo a branch to main and then push it
Let's say you've implemented a new feature on a branch "test" and now want to merge it back to main
```
git add .
```
```
git commit -m "commit message"
```
```
git checkout main
```
```
git pull origin main
```
```
git merge test
```
```
git push origin main
```

Alternatively, you can also push the test branch from terminal and then manually compare and merge the branches on github
