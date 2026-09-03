# 刘子晗的个人博客

基于 Astro、MDX 与 KaTeX 构建，并通过 GitHub Pages 发布。

## 本地运行

```bash
npm install
npm run dev
```

## 新增文章

在 `src/content/posts/` 新建 `.md` 或 `.mdx` 文件：

```md
---
title: 文章标题
description: 一句话摘要
date: 2026-09-04
tags:
  - 标签
---

正文从这里开始。
```

普通内容使用 Markdown；需要彩色文字或定制组件时使用 MDX。推送到 `main` 后，GitHub Actions 会自动构建和发布。
