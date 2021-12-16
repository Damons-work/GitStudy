# GIT
### 查看用户名和邮箱地址
##### git config user.name
##### git config user.email
###### 每次提交代码提交人信息(名字和邮箱地址)
### 修改用户名和邮箱地址
##### git config --global user.name "username"
##### git config --global user.email "email"
### Git建仓
##### mkdir File 新建名叫File的文件夹
##### cd File 进入File
##### git init    初始化仓库
##### git add .    添加文件到暂存区
###### 例: git add README.md    添加REAMDE.md(某一个文件)
###### git add .  (.代表全部文件)
##### git commit    将暂存区内容添加到仓库中
###### 例: git commit -m "描述"     提交代码并给出描述

### Git克隆
##### git clone 拷贝远程仓库到本地
###### 例: git clone git@github.com:Damons-work/Soul-Knight.git

### Git状态
##### git status 查看仓库当前的状态，显示有变更的文件
##### git diff 比较文件的不同，即暂存区和工作区的差异

### Git提交错误
##### git log 查看历史提交记录(一般看到上一次的提交记录)
##### git reset 回退上一版本

### Git远程操作
##### git remote 远程仓库操作
##### git fetch +分支  从远程获取代码库
##### git pull 下载远程代码并和本地代码合并
##### git push +分支 上传远程代码并合并

### Git分支管理
##### git branch +分支名 创建分支
##### git checkout +分支名 切换分支
##### git merge +分支名 合并分支