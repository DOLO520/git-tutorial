# 基本操作

git init --初始化仓库

git status--查看仓库状态

git add --向暂存区添加文件

git commit --保存仓库的历史纪录

git log --查看提交日志

git diff --查看更改前后的差别

# 分支的操作

git branch 显示分支一览表

git checkout -b 创建，切换分支

 git checkout master切换到master分支
 
git merge --no-ff 合并分支

git log --graph以图表的形式查看分支

# 更改提交的操作

git reset --hard 哈希值 回溯到特定时间点

编辑 添加 提交 

git reflog查看当前仓库执行过的操作日志

git reset --hard 哈希值 回溯到历史前状态

git commit --amend 修改提交信息

# 推送至远程

git remote add origin 远程仓库网址

git push -u origin master 推送至master分支

# 从远程仓库获取

git clone 远程仓库网址

获取远程的feature-D分支

git checkout -b feature-D origin/feature-D

向本地的feature-D分支提交更改

git diff

git commit -am "Add feature-D"

推送feature-D分支

git push 

git pull 获取最新的远程仓库分支

git pull origin feature-D
