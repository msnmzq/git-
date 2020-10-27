### 安装git

### git本地库

分为：

工作区：通过git add添加到暂存区

暂存区：临时存储内容。通过git commit将内容提交到本地库。

本地库：本地库的内容时永久的

### git操作

#### git init

初始化本地库。生成一个.git文件夹，不能删除和随意修改

#### 设置签名

### git status

查看当前状态，有哪些内容未提交到暂存区

### git add fileName（可以是文件夹名称）

将文件（或者文件夹中的所有文件）提交到暂存区

git add .			将所有的内容上传到暂存区

### git commit  -m"介绍"  fileName

git commit -m"介绍" .				将所有的内容上传到本地库

## 和远程库的操作

git remote add 别名 远程地址：为远程库设置别名

git remote -v ：查看远程库别名

git push 别名 本地分支名。push之后，github会生成一个master分支







