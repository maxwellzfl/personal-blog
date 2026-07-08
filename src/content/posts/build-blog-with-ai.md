---
title: 用 AI 搭建了这个博客（示例文章）
date: 2026-07-07
category: AI
description: 记录用 Claude 从零搭建这个 Astro 博客的过程。
tags: [Claude, Astro]
---

这是一篇示例文章，展示 AI 实践类内容的写法。

## 技术栈

这个网站用 [Astro](https://astro.build) 搭建，文章用 Markdown 写，托管在免费的静态站点平台上。

## 写新文章的方式

在 `src/content/posts/` 下新建一个 `.md` 文件，frontmatter 写好 title、date、category 即可。保存后推送到 Git 仓库，网站会自动重新构建发布。
