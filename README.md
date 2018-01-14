# 关于GIT:

## install git

https://git-scm.com/book/zh/v2/%E8%B5%B7%E6%AD%A5-%E5%AE%89%E8%A3%85-Git

## GIT基础使用

git是一个**版本控制系统**，就是用来处理pull request(提交请求)，merge(请求合并)的一个linux工具，而github是一个以git服务为基础的网站，但是github不仅仅是git，它提供了一系列工具，包括issue问题跟踪、贡献统计、wiki页面(用于项目说明)、以及好用的blog。
<br>
新接触github，需要学会提交自己的代码，总结一下命令：

### 1.打开终端，cd 进入到待提交的文件夹

### 2.第一次使用git时需要配置github用户名和邮箱：

```shell
$ git config --global user.name github用户名 
$ git config --global user.email github邮箱
```

~~### 3.设置ssh连接~~ 

### 4.提交

接下来就简单了，以后提交也只需从这步开始

#### 4.1添加文件

```shell
$ git add . 
```
‘.’表示添加所有文件，你也可以在add 后指定提交的文件名。

#### 4.2提交注释

```shell
$ git commit -m "写下你想写的东西"
```

#### 4.3提交到github远程仓库

```shell
$ git push -u url master 
```
url就是你的仓库的url，用https的，url后是分支的名字，master是主分支。

<br>
然后就ｏｋ啦！
<br>
对了，输入密码时是不显示的！！！！
<br>
目前掌握这些命令就行，但是使用github更重要的是协同工作，所以以后还要学会切换分支，git pull，和请求合并。
