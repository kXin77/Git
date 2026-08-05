---

mindmap-plugin: basic

---

# git使用

## 使用过程命令
- 首次使用需要配置自己的个人信息
	- 选择Open Git Bash here
	git config --global user.name "名字"
	git config --global user.email "xxx@xxx.cn，（邮箱）"
- git本地仓库初始化
	- git init
- 查看文件状态
	- git status
- 添加到暂存区
	- git add 文件名
- 暂存区提交到本地仓库
	- git commit -m “提示说明信息” 文件名
- 查看提交日志
	- git log
- 版本回退
	- git reset --hard 版本号
- 添加到远程仓库
	- git remote add origin 远程仓库地址
- 查看绑定的远程仓库
	- git remote -v
- 本地仓库推送到远程仓库
	- git push -u origin "要添加的分支名"
- 远程仓库克隆到本地仓库
	- git clone 远程仓库地址
- 创建分支
	- git branch 新分支名
- 查询分支
	- git branch            列出所有本地分支
	void
	git branch -r         列出所有远程分支
	void
	git branch -a         列出所有本地分支和远程分支
- 切换分支
	- git  checkout 分支名
- 推送到远程分支
	- git push  origin "要添加的分支名"
- 合并分支
	- git meroe 要合并的目标分支