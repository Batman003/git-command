# git-command

## To Add repo from local to remote github
```
mkdir my_project
cd my_project
touch .gitignore
git init
git add .
git commit -m "Initial commit"
git remote add origin youruser@yourserver.com:/path/to/my_project.git
git push origin main

```

## If this error : remote contains work that you do not have locally.
```
git pull origin main --allow-unrelated-histories
git merge origin origin/master
```
