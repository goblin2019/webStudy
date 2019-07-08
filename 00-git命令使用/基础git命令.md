## 前言

愿你，有事做，有人爱，有所期待

### 正文

进入我司以来，都是以界面化工具（Sourcetree）完成git工作流程。但git命令还是要学习起来滴，毕竟命令行的操作会显的比较高大上。。。Hahaha

#### 1.git安装

> 这个，默认你会的。。。

### 2.常用命令了解
* 提交

```
git clone [url]
# 就可以下载远端的项目啦

git add * 
# 添加当前目录所有的文件到暂存区，也可以指定文件噢。 git add [file1] [file2] ...

git commit -m [message]
#提交暂存区到仓库

git push -u origion master
# 推送此次修改，首次需要加-u,master是默认的分支，如果不在master分支只需要修改下需要提交的分支名就好
```
* 分支

> 多人协作的话，单独自己的功能分支，开发过程这样就互不干扰了。当然最终的发布分支的冲突还是要自行解决的。

```
git branch [参数]
# 空：列出本地分支；-r：列出远程分支；-a：所有分支

git branch [branch]
# 新建一个分支，仍在当前分支
git checkout -b [branch]
# 新建一个分支，并切到该分支
git checkout [branch]
# 切换到指定分支
git checkout -
# 切换到上一个分支

git merge [branch]
# 合并指定分支到当前分支，如果存在冲突需手动解决


git cherry-pick [commit]
# 选择一个commit,合并到当前分支
git log --online -n
# 查看最近n次提交记录

```

* 撤销





