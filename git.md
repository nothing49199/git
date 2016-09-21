# 第一章 操作流程
* git init 初始化

* git add .(或者文明名  **.**)

* git commit -m 

* git checkout -b  分支名 创建一个分支并切换到 该分支上
* git branch -a       查看所有分支
* git add -u 更新所有文件

* git remote add 远程名称 远程地址（绑定）

* git push 远程名 本地名

# 第二章 在github上创建仓库

* git init
* git add README.md
* git commit -m "first commit"
* git remote add origin https://* * github.com/BrentHuang/MyRepo.git
* git push -u origin master


* 在本地新建一个分支： git branch Branch1
* 切换到你的新分支: git checkout Branch1
* 将新分支发布在github上： git push origin Branch1
* 在本地删除一个分支： git branch -d Branch1
* 在github远程端删除一个分支： git push origin :Branch1   (分支名前的冒号代表删除)

* 直接使用git pull和git push的设置

* git branch --set-upstream-to=origin/master master 
* git branch --set-upstream-to=origin/ThirdParty ThirdParty
* git config --global push.default matching

