# git和github学习笔记

- 初始化git仓库
> git init

- 添加改动到git暂存区（Index）
> git add <filename>

- 提交改动到HEAD,即版本库中
> git commit -m "description about this commit"

- 查看当前git仓库的状态
> git status

- 如果git status显示工作区文件已经被修改，使用diff查看被修改的内容
> git diff

- 版本回退
> git reset --hard commit_id

- 查看提交历史
> git log

- 重返未来，需要先查看历史命令
> git reflog

- 舍弃工作区的修改，也相当于回到于目前版本库中最新版本的内容
> git checkout -- <filename>

- 撤回已经添加到暂存区的修改
> git reset HEAD <filename>

- 添加远程库
> git remote add origin git@github.com:server-name/path/repo-name.git

- 把本地库内容推送到远程仓库，首次推动时加 -u 参数，可以把本地master分支和远程master分支关联起来
> git push -u origin master

- 从远程库克隆，即先建立远程库，然后克隆到本地
> git clone git@github.com:server-name/path/repo-name.git
