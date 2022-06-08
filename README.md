# git-hands-on



## Creating on new branch:
1. git fetch -ap
2. git checkout --no-track -b <branch name> origin/develop
3. <made the necessary changes>
4. git add `filename`
5. git commit -m `message`
6. git pull --rebase origin develop
7. git push -u origin `branch name`

## When editing a branch that's been pushed:
1. git checkout `branch name`
2. `make all the changes`
3. git add `file name`
4. git commit -m `<commit message>`
5. git fetch -ap
6. git pull --rebase origin develop
7. git push --force
