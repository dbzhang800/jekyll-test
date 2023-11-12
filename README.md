## jekyll-test

本地不安装 Jekyll 这套Ruby的东西，
测试最最简单的支持Jekyll的GitHub Pages站点。

### 仓库设置

Settings => Pages => Buid and deployment

Source: 选择 Depoly from a branch

Branch：选择 main root

### 仓库文件

* 需要一个 index.md 文件，文件头部需要有三个中横线构成的头部

```
---
title: Home
---
```

> 很多人说如果没有index.md的话，会使用README.md文件，个人试过不行，不知道是否姿势不对造成的。

## 参考

* https://github.com/MichaelCurrin/simplest-jekyll
