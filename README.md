# JIE 的技术博客

静态博客站点，记录 AI 应用开发的实战过程：RAG、Prompt 工程、模型调用、工具编排、评测与成本优化。24 篇文章，纯静态 HTML，无框架依赖。

## 在线访问

GitHub Pages：https://justin-yu-space.github.io/my-tech-blog/

## 本地预览

直接双击 `index.html` 用浏览器打开即可，无需构建。若需重新生成归档、标签、Feed 等页面：

```bash
node build.js
```

## 目录说明

- `index.html` / `blog.html` / `archive.html` / `tags.html` — 首页、文章列表、归档、标签页
- `posts/*.html` — 24 篇文章正文
- `projects.html` / `about.html` — 项目页与关于页
- `assets/css/` — 样式
- `assets/js/` — 前端逻辑与配置
- `assets/data/` — 站点、文章、项目数据源（由 `build.js` 使用）
- `feed.xml` / `sitemap.xml` / `robots.txt` — 订阅与搜索收录

## 说明

站点内容与代码均为个人学习记录，不涉及公司内部数据。
