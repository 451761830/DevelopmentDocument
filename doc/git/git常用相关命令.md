## Git配置

- 配置用户名
	> git config --global user.name '用户名'

- 配置邮箱
	> git config --global user.email '用户邮箱'

- 查看配置
	> git config --list

## 分支管理

- 创建分支
	> git checkout -b dev	

- 查看分支
	> git branch -a
- 分支内容提交
	> git commit -a -m '提交内容描述'
	
- 切换至master分支
	> git checkout master 	

- 合并分支
	> git merge dev

- 删除分支
	> git branch -d dev
