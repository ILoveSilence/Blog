# 创建 gitbook 项目

简介





## 项目构建

首先需要确定电脑具备 node 环境，建议使用 14版本的 node，我一开始使用 16版本，遇到了一些奇怪的问题无法解决。



全局安装 gitbook 项目脚手架

```powershell
> npm i -g gitbook-cli
```

安装好后，查看版本：

```powershell
> gitbook -V
CLI version: 2.3.2
GitBook version: 3.2.3
```



运行 gitbook 指令，如果遇到提示说系统禁止运行脚本，解决方法如下：

https://blog.csdn.net/github_35186068/article/details/80518681



到你的项目目录下，进行项目初始化

```powershell
> gitbook init
```

如果是想在当前目录创建新的文件夹进行初始化，可以运行：

```powershell
> gitbook init ./directory
```

初始化其实做了很简单的一件事情，在你的文件夹下创建了两个文件：README.md 和 SUMMARY.md。后续进行介绍

使用 serve 指令预览图书

```powershell
> gitbook serve
```

使用 build 指令构建静态网站

```powershell
> gitbook build
```



**目录与说明**

README.md 文件是用来







**参考**

[gitbook 文档](https://github.com/GitbookIO/gitbook/blob/master/docs/setup.md)

