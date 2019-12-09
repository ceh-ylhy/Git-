官网：https://git-scm.com/

1、安装git

Centos
  yum install git
Linux
  sudo apt-get install git
Windows
  1) 下载git安装
  2) 开始菜单选择Git Bash
        $ git config --global user.name "Your Name"
        $ git config --global user.email "email@example.com"
        
2、配置Git

初始化一个Git仓库，使用git init命令。

    $ mkdir learngit
    $ cd learngit
    $ git init

添加文件到Git仓库，分两步：

使用命令git add <file>，注意，可反复多次使用，添加多个文件；
使用命令git commit -m <备注>，完成。
