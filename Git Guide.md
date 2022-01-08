# Git 基本操作

Git 的工作就是创建和保存你项目的快照及与之后的快照进行对比。

本章将对有关创建与提交你的项目快照的命令作介绍。

Git 常用的是以下 6 个命令：**git clone**、**git push**、**git add** 、**git commit**、**git checkout**、**git pull**，后面我们会详细介绍。

![](https://www.runoob.com/wp-content/uploads/2015/02/git-command.jpg)

**说明：**

-   workspace：工作区
-   staging area：暂存区/缓存区
-   local repository：版本库或本地仓库
-   remote repository：远程仓库

一个简单的操作步骤：

$ git init    
$ git add . $ git commit 

-   git init - 初始化仓库。
-   git add . - 添加文件到暂存区。
-   git commit - 将暂存区内容添加到仓库中。

### 创建仓库命令

下表列出了 git 创建仓库的命令：

命令

说明

`[git init](https://www.runoob.com/git/git-init.html)`

初始化仓库

`[git clone](https://www.runoob.com/git/git-clone.html)`

拷贝一份远程仓库，也就是下载一个项目。

---

## 提交与修改

Git 的工作就是创建和保存你的项目的快照及与之后的快照进行对比。

下表列出了有关创建与提交你的项目的快照的命令：

命令

说明

`[git add](https://www.runoob.com/git/git-add.html)`

添加文件到仓库

`[git status](https://www.runoob.com/git/git-status.html)`

查看仓库当前的状态，显示有变更的文件。

`[git diff](https://www.runoob.com/git/git-diff.html)`

比较文件的不同，即暂存区和工作区的差异。

`[git commit](https://www.runoob.com/git/git-commit.html)`

提交暂存区到本地仓库。

`[git reset](https://www.runoob.com/git/git-reset.html)`

回退版本。

`[git rm](https://www.runoob.com/git/git-rm.html)`

删除工作区文件。

`[git mv](https://www.runoob.com/git/git-mv.html)`

移动或重命名工作区文件。

### 提交日志

命令

说明

`[git log](https://www.runoob.com/git/git-commit-history.html#git-log)`

查看历史提交记录

`[git blame <file>](https://www.runoob.com/git/git-commit-history.html#git-blame)`

以列表形式查看指定文件的历史修改记录

### 远程操作

命令

说明

`[git remote](https://www.runoob.com/git/git-remote.html)`

远程仓库操作

`[git fetch](https://www.runoob.com/git/git-fetch.html)`

从远程获取代码库

`[git pull](https://www.runoob.com/git/git-pull.html)`

下载远程代码并合并

`[git push](https://www.runoob.com/git/git-push.html)`

上传远程代码并合并