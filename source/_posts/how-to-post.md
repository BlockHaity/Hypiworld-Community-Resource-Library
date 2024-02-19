---
title: 如何投稿
date: 2024-02-19 12:17:47
tags:
    -   开发者相关
categories: 开发者相关
---

发布者：BlockHaity
修改：BaimoQilin

# 注意

在投稿前，请确认你的资源不会违反Hypiworld玩家协议，我们会不定期删除违反Hypiworld玩家协议的资源。

# 可供参考的文档

[Hypiworld玩家协议](https://baimoqilin.top/hypiworld/rules.pdf)

[Markdown语法速查表](https://markdown.com.cn/cheat-sheet.html)

[Hexo文档](https://hexo.io/zh-cn/docs/)

# 投稿方法

## PR方法

两种方法均需要Github账号

### 轻量

本方法无需安装hexo。

1. fork [BlockHaity/Hypiworld-Community-Resource-Library](https://github.com/BlockHaity/Hypiworld-Community-Resource-Library)并clone到本地。
2. 在`source/_posts`中复制一份模版的markdown文件，命名为文章标题的英文。
3. 使用Markdown语法编辑文章。
4. commit&push&pull requests即可

### 标准
首先，安装相关依赖

``` 
# 安装nodejs（Windows）
PS> winget install openjs.nodejs
# 安装nodejs（Linux）
$ sudo apt install nodejs npm # Debian系
$ sudo pacman -S nodejs # Arch系

# 设置npm镜像源（网络条件好可以跳过）
npm config set registry https://registry.npmmirror.com

# 安装hexo
npm install -g hexo-cli
```

接下来，将仓库（BlockHaity/Hypiworld-Community-Resource-Library）fork到自己名下，然后将仓库克隆到本地，进入文件夹并运行`npm install --save`

然后，运行`hexo new （文章名）`来创建文章。可以按照发布模板来编写

接下来，将本地仓库推送到Github

最后，创建PR，PR会自动合并，网页构建需要时间，一般在1~2分钟后即可见到你的文章和资源。
