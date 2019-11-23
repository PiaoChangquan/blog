整理一些平时用的git 命令方便平时用的时候直接使用
# 关于分支
```
#创建分支我 
git checkout branch xxx

#切换到远程分支
git checkout track -- orgin/your-branchName

#就是将本地的 origin/xxx 与 git 服务器的 origin/xxx 分支进行同步
git fetch --al
```
# 提交
```
#追加提交
git commit --amend
```

# merge & rebase
```
这个没看懂调查一下再说
```

# cherry-pick
```
# 将某次的的提交提取出来，用于切换分支时可能公用的改动
git cherry-pick commit-id
```

# chekout branch file 
```
#将你的某个文件还原到某个分支的版本,如果某次你手误提交了错误的文件，但是改动又忘了
git checkout branch -- file
```

# stash
```
#用于暂存更改
#压栈
git stash
#弹栈
git stash pop
#查看栈
git stash list 
#弹出指定的stash
git stash pop/apply stashid
```
