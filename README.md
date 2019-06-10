## 常用 git 命令
参考： https://backlog.com/git-tutorial/cn/intro/intro1_1.html

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
