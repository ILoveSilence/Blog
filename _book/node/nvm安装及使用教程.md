# nvm 安装及使用教程







## 安装

nvm 链接：https://github.com/nvm-sh/nvm#important-notes

nvm-windows 链接：https://github.com/coreybutler/nvm-windows



设置淘宝镜像源，不然在安装node的时候可能会因为网络问题报错如下：

```powershell
Downloading npm version 6.14.4... Error while downloading https://github.com/npm/cli/archive/v6.14.4.zip - Get "https://github.com/npm/cli/archive/v6.14.4.zip": EOF
panic: runtime error: invalid memory address or nil pointer dereference
```

找到你的nvm安装目录，我的是这个

```
C:\Users\...\AppData\Roaming\nvm
```

打开 settings.txt 文件，增加两行

```diff
root: C:\Users\LvLin\AppData\Roaming\nvm
path: C:\Program Files\nodejs

+ node_mirror: https://npm.taobao.org/mirrors/node/
+ npm_mirror: https://npm.taobao.org/mirrors/npm/
```







## 使用指南









参考文档：

https://blog.csdn.net/zheng18237111686/article/details/113878602

https://blog.csdn.net/J080624/article/details/107002294

https://titangene.github.io/article/nvm.html

https://github.com/nvm-sh/nvm#important-notes

https://github.com/coreybutler/nvm-windows

https://segmentfault.com/a/1190000007612011

https://blog.csdn.net/github_35186068/article/details/80518681

https://segmentfault.com/a/1190000007612011

https://blog.csdn.net/J080624/article/details/107002294





