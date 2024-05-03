# Mod资源投稿模板

{% code title="title.md" fullWidth="false" %}
```markdown
---
title: 发布模板
date: 2024-02-19 13:26:31
tags:
    -   开发者相关
categories: 开发者相关
cover: https://examples.com/cover.png
---

发布者：

资源作者：

正文

文件 [文件名](文件链接)
```
{% endcode %}

## 相关说明

### 文件头

`tag`为标签，建议使用mcmod.cn中版本检索中的小分类，如"优化"

`categories`为分类，建议使用mcmod.cn中版本检索中的大分类，如“魔改”，在此处说明，分类有且只有一个。

### 尾部文件链接

虽然可以，但不建议将资源托管到网站，因为无论是Github还是Netlify在国内下载大文件的速度都十分感人，如果一定要托管在此处的话，请将你的资源放在`source`文件夹中`files`文件夹中以文章命名的文件夹中。调用方式如下

```markdown
文件 [文件名](/files/文章名/文件名)
```
