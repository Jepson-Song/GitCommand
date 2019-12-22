- 初始化  
  git init
- 添加文件到缓冲区  
  git add filename
- 添加所有文件到缓冲区  
  git add .  
  git add all
- 提交缓冲区文件到仓库  
  git commit -m ""
- 查看仓库状态  
  git status
- 添加远程仓库  
  git remote add origin 仓库地址
- 移除远程仓库  
  git remote remove origin
- 将本地仓库推送到远程仓库  
  git push -u origin master （第一次加-u，之后就不用了）
- 把远程仓库更新到本地  
  git pull
- 比较修改过的还没提交的文件的差异  
  git diff filename
- 查看日志  
  git log
- 回退版本  
  git reset --hard HEAD^ 回退到上一个版本  
  git reset --hard 版本号 回退到指定版本
- 查看命令历史
  git reflog
- 创建分支  
  git branch 分支名
- 切换分支  
  git checkout 分支名
- 创建并切换分支  
  git checkout -b branch
- 合并某分支到当前分支  
  git merge 分支名
- 删除分支  
  git branch -d 分支名
- 查看分支合并图  
  git log --graph
- 新建标签，默认为最新版本  
  git tag 标签名 版本号
- 查看所有标签  
  git tag
- 查看标签详细信息  
  git show 标签名