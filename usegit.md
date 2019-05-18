#git和github学习笔记

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