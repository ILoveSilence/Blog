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



相关链接

https://www.chengweiyang.cn/gitbook/github-pages/README.html

https://www.jianshu.com/p/421cc442f06c

http://www.chengweiyang.cn/gitbook/introduction/README.html

https://blog.csdn.net/axi295309066/article/details/61420694

https://juejin.cn/post/6931225754264928269

https://segmentfault.com/a/1190000018753593

https://snowdreams1006.github.io/myGitbook/openwrite/

https://snowdreams1006.github.io/myGitbook/experience/gitbook-cli.html

https://haoqiangchen.github.io/hqbook/Tools/gitbook/build.html

https://champyin.com/2018/10/05/%E5%A6%82%E4%BD%95%E4%BD%BF%E7%94%A8gitbook%E5%8F%91%E5%B8%83%E8%87%AA%E5%B7%B1%E7%9A%84%E4%B9%A6%E7%B1%8D/

https://segmentfault.com/a/1190000018734441

https://segmentfault.com/a/1190000018753593

https://www.cnblogs.com/lingchen-liang/p/13537685.html

https://juejin.cn/post/6931225754264928269

https://chrisniael.gitbooks.io/gitbook-documentation/content/platform/organizations/convert.html

https://github.com/GitbookIO/gitbook/blob/master/docs/setup.md

https://linxiaoru.github.io/2019/01/18/%E5%A6%82%E4%BD%95%E7%94%A8gitbook%E6%90%AD%E5%BB%BA%E8%87%AA%E5%B7%B1%E7%9A%84%E6%96%87%E6%A1%A3%E6%95%B4%E5%90%88%E5%B9%B3%E5%8F%B0/ （gitpage主题可以参考这个）





gitbook build --output=/tmp/gitbook
