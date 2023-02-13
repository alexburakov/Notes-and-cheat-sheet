**SETUP & INIT**

```
git config --global user.name “[firstname lastname]”
git config --global user.email “[valid-email]”
git init
git clone [url]
```

**STAGE & SNAPSHOT**

```
git add -A
git commit -m '[descriptive message]'
git status

git reset [mode(--hard)] [id commit]
```

**BRANCH & MERGE**

```
git branch
git branch [new-branch]
git checkout new-branch
git checkout main

git merge new-features

git log
git diff
```

**TEMPORARY COMMITS**

```
git stash
git stash pop
```

**SHARE & UPDATE**

```
git remote add [origin]
git push origin main
git pull
```
