#  Taks01
## 第一章 Git简介
### 1.1 版本控制器
#### 1.1.1 什么是版本控制器
版本控制系统是可以记录我们对于代码细节的每一次修改，以至于我们可以使代码快速回溯的某一次修改之前
#### 1.1.2 版本控制系统分类
现在的版本控制系统主要有两类：集中式版本控制系统和分布式版本控制系统

集中式版本控制系统：集中式版本库集中存放于一台中央服务器。协同工作是需要先从服务器里面获取最新的版本，修改完后再把修改推送给服务器

分布式版本控制系统：没有中央服务器，每个人的电脑上都有一个镜像下来的完整的代码库，有一个仅起交换修改作用的“中央服务器”
### 1.2 Git简介和历史
在Linux之父Linus Torvalds的带领下用了10天编写出了第一个Git版本。自诞生以来，Git 日臻成熟完善，在高度易用的同时，仍然保留着初期设定的目标。 它的速度飞快，极其适合管理大项目，有着令人难以置信的非线性分支管理系统（参见 Git 分支）。
### 1.3 Git的安装
关于Git的安装，我们可以访问Git book所给的下载教程进行下载，我们在下面的几部分也是仅做简要叙述。具体链接 --> [安装 Git](https://git-scm.com/book/zh/v2/%E8%B5%B7%E6%AD%A5-%E5%AE%89%E8%A3%85-Git)
#### 1.3.1 Linux
略
#### 1.3.2 macOS
略
#### 1.3.3 wondows
在 Windows 上安装 Git 也有几种安装方法。 我们也可以打开 https://git-scm.com/downloads  进行下载安装。安装好后我们可以打开Git bash。
![](./figures/Git_gui.png)
另一个简单的方法是安装 GitHub Desktop。 该安装程序包含图形化和命令行版本的 Git。 它也能支持 Powershell，提供了稳定的凭证缓存和健全的换行设置。
#### 1.3.4 初次运行Git的配置
当我们安装好Git后，还需要在Git bash或者terminal进行一些相关设置，以下设置仅需设置一次即可。
```bash
git config --global user.name "Your Name"
git config --global user.email "email@example.com"
```
除此之外，Git还有很多设置，包括常用编辑器等，大家可以键入以下命令查看自己的设置并进行修改。
```bash
git config --list
```
### 1.4相关学习资源
- [Git Book](https://git-scm.com/book/zh/v2)
- [廖雪峰Git教程](https://www.liaoxuefeng.com/wiki/896043488029600)
- [Git权威指南](https://gotgit.readthedocs.io/en/latest/index.html)
- [freenode](https://freenode.net/)
- [Github-cheat-sheet](https://github.com/tiimgreen/github-cheat-sheet)
- [动手学Git](https://www.freeaihub.com/git/index.html)
- [learn git branching](https://learngitbranching.js.org/?locale=zh_CN)
## 第二章 Git基础命令
