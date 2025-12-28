# git 常用命令
## 配置全局信息
```
git config --global user.name "your_name"
git config --global user.email "your_email@example.com"
```
## 初始化仓库
```
git init
```
## 克隆仓库
```
git clone https://github.com/your_username/your_repository.git
```
## 添加修改文件
```
git add .
```
## 提交到本地仓库
```
git commit -m "your commit message"
```
## 查看状态与日志
```
git status
git log
```
## 创建/切换/合并分支
```
git branch branch_name 创建
git checkout branch_name 切换
git merge branch_name 合并
```
## 删除分支
```
git branch -d branch_name 需要先合并
```
## 远程操作
```
git remote add origin https://github.com/your_username/your_repository.git  添加远程仓库
git push -u origin branch_name  推送分支到远程仓库
git pull origin branch_name  从远程仓库拉取分支
```
## 回滚到指定提交
```
git reset --hard commit_hash
```