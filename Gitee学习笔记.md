# 一、Git介绍

## 1.Git介绍

​		Git是分布式版本控制工具，还有集中式版本控制工具，下面是二者的区别。

​		版本控制最重要的是可以记录文件修改历史，并且能够查看历史版本， 方便版本切换。学习版本控制能够从个人过渡到团队开发

​		分布式：

![image-20220111205740123](Gitee学习笔记.assets/分布式定义.png)

![image-20220111205810217](Gitee学习笔记.assets/分布式结构.png)

还有一个远程库没有画，把代码推送到远程库中

​		集中式：CVS、SVN(Sub version)、VSS

![image-20220111205345770](Gitee学习笔记.assets/集中式分布.png)

## 2.Git命令

### 2.1Git常用命令

| 命令名称                             | 作用                     |
| ------------------------------------ | ------------------------ |
| git config --global user.name 用户名 | 设置用户签名             |
| git config --global user.email 邮箱  | 设置用户签名             |
| git init                             | 初始化本地库             |
| git status                           | 查看本地库状态           |
| git add 文件名                       | 添加到暂存区             |
| git commit -m "日志信息" 文件名      | 提交到本地库             |
| git reflog                           | 查看历史记录(精简版本号) |
| git reset --hard 版本号              | 版本穿梭                 |
| git rm --cached xx.xx                | 从暂存区删除xx.xx文件    |
| git log                              | 完整的日志记录           |
|                                      |                          |
|                                      |                          |
|                                      |                          |

### 2.2初始化本地库命令

直接在要管理的项目目录下，右键单击Git Bash即可，其它方式进入盘符不方便

![image-20220112101154082](Gitee学习笔记.assets/GitInit.png)

这个.git是一个隐藏的目录文件，需要将查看隐藏文件勾选上

git -bash中的命令和linux是通用的



### 2.3vim命令

## 3.Git分支

## 4.Idea集成Git

## 5.Git升级(安装)

安装在非中文，且不带空格的目录下，给git升级的办法是在，gitcmd.exe中输入

```shell
git update-git-for-windows
```

但是这种方法太慢，可以使用阿里云的镜像下载

[阿里云镜像](https://developer.aliyun.com/mirror/)

## 6.Git工作原理

![image-20220112090119397](Gitee学习笔记.assets/Git工作原理.png)

从本地库-->远程库，用push命令

## 7.Git配置

![image-20220112100524146](Gitee学习笔记.assets/Git配置.png)

# 二、GitHub

## 1.创建远程库

## 2.代码推送

## 3.代码拉取

## 4.代码克隆

## 5.SSH免密登陆

## 6.Idea集成GitHub



# 三、Gitee码云

## 1.创建远程库

## 2.Idea集成Gitee

## 3.码云连接GitHub进行代码复制和前移



# 四、GitLab

GitLab是基于局域网的，不推给外界看到

## 1.GitLab服务器的搭建和部署

## 2.Idea集成GitLab