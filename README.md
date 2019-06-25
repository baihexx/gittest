## 常用 git 命令
参考： https://backlog.com/git-tutorial/cn/intro/intro1_1.html

// branch
* git branch
* git branch -a
* git branch -d
* git branch <branch-name> // create branch from current branch
* git checkout <branch-name> // switch branch
* git pull <remote host name> <remote branch name:local branch name>  // first git pull a remote branch
* git merge <branch1> // merge branch1 to to current branch
* gir rebase <branch1> // rebase current branch into branch1

// reset
* git reset <commid-id> // 重置HEAD到 commid-id
* git reset <file> // undo 'git add' befor commit
* git reset --mixed
* git reset --soft
* git reset --hard

* git cherry-pick <commit-id> // pick content of commid-id into current branch

## HEAD
* https://stackoverflow.com/questions/2304087/what-is-head-in-git
* https://juejin.im/entry/59a38c5d6fb9a0248e5cc884

## States
* untracted, tracted
* unmodified, modified, staged

## git add : add precisely this content to the next commite
* tracking new filed
* stage files
* marking merge-conflicted files as resolved

## Git diff


## reset
* git add then reset
* git commit then reset
* git push then reset

* working directory  staged repository

## Undo
* unstaging a staged file: git reset HEAD <file>
* unmodifying a modified file: discard changes in working directory
  git checkout -- <file> // git just replace that file with the most rencently-commited version


fix1