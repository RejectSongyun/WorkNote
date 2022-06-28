# git命令

##### 创建仓库命令

git init
git init newrepo
git clone 仓库地址 ：克隆仓库

##### git配置命令

git config ：查看当前git配置信息
git config -e ：编辑当前仓库的配置文件
git config --global user.name "昵称" ：设置用户昵称
git config --global user.email test@runoob.com ：设置用户邮箱

##### 提交与修改命令

git add 文件名 （可用*.java形式）：当前目录下文件加入缓存区
git commit  -m "提交说明" ：提交
git status ：查看当前版本号
git diff ：比较文件的不同
git reset ：回退版本
git rm ：将文件从暂存区和工作区中删除
git mv ：移动或重命名工作区文件

##### 查看日志

git log ：查看历史提交记录
git blame\<file> ：以列表形式查看指定文件的历史修改记录

##### 远程操作

git remote ：远程仓库操作
git fetch ：从远程获取代码仓库
git pull ：下载远程代码并合并
git push ：上传远程代码并合并

