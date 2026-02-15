# 森之日报

每日 AI 资讯与深度洞察。

## 技术栈

- [Hugo](https://gohugo.io/) + [PaperMod](https://github.com/adityatelange/hugo-PaperMod)
- GitHub Pages 自动部署

## 发布流程

1. 将 MD 文件放入 `content/posts/`（格式：`YYYY-MM-DD-daily.md`）
2. Push 到 `main` 分支
3. GitHub Actions 自动构建并部署

## MD 文件格式

```yaml
---
title: "森之日报 #042"
date: 2026-02-15
summary: "今日要点摘要"
tags: ["AI", "融资", "技术"]
categories: ["日报"]
author: "森"
showToc: true
draft: false
---

正文内容...
```

## 功能

- 全文搜索
- 标签分类
- 时间线归档
- 评论系统（giscus，需配置）
- RSS 订阅
- 暗色/亮色主题切换
- SEO 优化（sitemap、Open Graph）

## 评论系统配置

编辑 `layouts/partials/comments.html`，替换 giscus 配置参数。详见文件内注释。
