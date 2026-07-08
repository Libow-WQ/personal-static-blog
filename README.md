# 个人博客静态页面

项目预览：https://libow-wq.github.io/personal-static-blog/

源码仓库：https://github.com/Libow-WQ/personal-static-blog

## 项目简介

这是一个基于 HTML5 + CSS3 开发的个人技术博客静态页面项目，包含首页和文章列表页。项目采用 Flexbox 与 Grid 混合布局，实现桌面端、平板端、手机端三端响应式适配，适合作为前端基础能力展示作品。

## 技术栈

- HTML5
- CSS3
- Flexbox
- CSS Grid
- CSS Variables
- 响应式布局
- GitHub Pages

## 核心功能

- 首页展示个人信息、项目简介、统计信息和最新文章
- 文章列表页展示多篇技术文章摘要、标签、发布时间和阅读时长
- 移动端导航栏折叠为汉堡菜单
- 支持纯 CSS 主题色切换
- 支持桌面端、平板端、手机端自适应布局
- 无 JavaScript 依赖，页面结构轻量

## 技术亮点

1. 使用 `:root` CSS 自定义属性统一管理主题色，主色为 `#2D7CF6`，便于后续维护和一键换肤。
2. 使用 `:checked` 伪类实现移动端汉堡菜单展开和收起，不依赖 JavaScript。
3. 首页使用 Grid 构建主视觉区，文章卡片区域使用响应式网格布局。
4. 文章列表页使用 Grid 构建内容区和侧边栏，卡片内部结合 Flexbox 完成内容对齐。
5. 页面不依赖第三方库，静态资源少，首屏加载快。

## 目录结构

```text
personal-static-blog/
├── index.html       # 首页
├── articles.html    # 文章列表页
├── styles.css       # 公共样式
├── README.md        # 项目说明
├── DEPLOY.md        # 发布说明
└── .nojekyll        # GitHub Pages 静态站点配置
```

## 本地运行

直接双击打开 `index.html` 即可预览。

也可以使用任意静态服务器打开项目目录。

## 简历描述

个人博客静态页面（HTML5 + CSS3）：独立完成首页与文章列表页开发，采用 Flexbox + Grid 混合布局实现桌面端、平板端、手机端响应式适配；使用 CSS Variables 管理主题色并支持一键换肤；移动端汉堡菜单采用纯 CSS `:checked` 方案实现，无 JavaScript 依赖；项目已部署至 GitHub Pages，可在线访问。
