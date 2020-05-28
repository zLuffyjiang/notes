checkout

**$ git add .**：将当前目录下未跟踪、修改的文件添加到暂存区  
**$ git add all**：将所有目录下未跟踪、修改、删除的文件添加到暂存区

**$ git switch -c branch**：创建并切换到branch分支  
**$ git switch branch**：切换到branch分支  
**$ git branch -d branch**：删除branch分支  
**$ git branch -v**：查看当前所以分支  

git pull = git fetch + git merge：少用pull，多用fetch  
git push = 远程仓库git merge master  
远程仓库origin
git push origin branch：将本地仓库的branch分支推送到origin远程仓库的branch分支  
git pull 