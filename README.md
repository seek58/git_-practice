基础
简介
安装和配置
常用功能
分支策略
实践练习
进阶
基础
简介
Git是一种分布式的版本管理系统，常用于多人协作进行软件开发的版本控制，我们所有的项目都是使用进行Git进行源码管理的，熟练掌握git的常用功能是和大家协作进行开发的基本要求。

安装和配置
根据自己的操作系统进行下载安装：https://git-scm.com/downloads

配置姓名和邮箱：

git config --global user.name 张三
git config --global user.email san.zhang@mljr.com
查看配置情况：

git config -l
SSH配置：http://jaminzhang.github.io/git/config-and-add-SSH-key-in-GitLab/

常用功能
git init

git status

git add

git commit

git log

git remote add

git push

git pull

git reset <target_file_name>

git checkout -- <target_file_name>

git branch <new_branch_name>

git checkout <new_branch_name>

git branch

git merge

git push

git clone

解决冲突（推荐使用图形界面工具解决冲突）：http://www.cnblogs.com/sinojelly/archive/2011/08/07/2130172.html

diff代码：git diff命令或者利用在线代码托管提供的功能（https://gitlab.com/gitlab-org/gitlab-ce/compare?from=master&to=master）

分支策略
我们采用分支开发，主干发布的分支策略

关于分支开发，主干发布：http://nvie.com/posts/a-successful-git-branching-model/

实践练习
练习一：15分钟快速入门Git在线练习

练习二：在gitlab上个人group下新建一个练习项目，练习所有常用命令的使用，熟悉git和gitlab的使用

进阶
Pro Git https://git-scm.com/book/en/v2

Git主页
