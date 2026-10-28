---
title: "第一篇：小站开张"
date: 2026-10-28T22:40:00+08:00
tags: ["随笔"]
categories: ["生活"]
draft: false
---

欢迎来到我的小站，这是第一篇文章。

## 这里以后会写什么

生活里的见闻和感想，读到的好书好句，学东西过程中的碎碎念。不设固定主题，想到了就写。

## 怎么写一篇新文章

在博客项目目录下执行：

```bash
hugo new posts/my-first-note.md
```

然后用任何编辑器（比如 Obsidian）打开 `content/posts/my-first-note.md` 写正文，写完后把开头信息里的 `draft = true` 删掉或改成 `false`，本地预览：

```bash
hugo server -D
```

浏览器打开 <http://localhost:1313> 就能看到效果。满意后提交并推送，网站会自动更新：

```bash
git add . && git commit -m "新文章：xxx"
git push
```

## 正文支持的写法

**加粗**、*斜体*、[链接](https://github.com/adityatelange/hugo-PaperMod)、引用：

> 生活中不是缺少美，而是缺少发现美的眼睛。

列表、表格、代码块都支持。够用了，开写。
