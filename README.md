# 个人博客

基于 [Astro](https://astro.build) 的极简中文博客，三个板块：投资、生活、AI。

## 本地预览

需要 Node.js 18.17 以上（推荐 20+）。

```bash
npm install
npm run dev
```

浏览器打开 http://localhost:4321 即可。

## 写新文章

在 `src/content/posts/` 下新建 `.md` 文件（文件名用英文，会成为文章 URL），frontmatter 写 title、date、category（投资/生活/AI 三选一）、description（可选）。推送到仓库后网站自动更新。

## 修改站点信息

站点名称、简介、板块在 `src/consts.ts`；关于页在 `src/pages/about.astro`；样式在 `src/styles/global.css`；域名在 `astro.config.mjs`。
