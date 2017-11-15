---
title: git 别名 | git
date: 2017-11-13 09:27:36
categories:
  - git
tags:
  - git
abbrlink: 20951f34e76e48cf
---

# Git 命令别名

可以用 git config 为命令设置别名。来看看下面的例子：
```sh
$ git config --global alias.co checkout
$ git config --global alias.br branch
$ git config --global alias.ci commit
$ git config --global alias.st status
```

现在，如果要输入 `git commit` 只需键入 `git ci` 即可。而随着 Git 使用的深入，会有很多经常要用到的命令，遇到这种情况，不妨建个别名提高效率。

# 更多

* [git 学习汇总](http://blog.wangjinle.com/posts/fd56adc47e2516b6.html)