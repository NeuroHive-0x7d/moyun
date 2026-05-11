---
title: "关于这个博客"
---

一个安静写字的地方。

## 关于我

复制 `content/pages/about.md` 并在此处填写你的个人信息。

## 技术栈

本博客使用 **React 18 + Vite 5** 构建，纯静态部署，无需后端服务。所有文章以 **Markdown** 文件存放于 `content/posts/` 目录，由 **react-markdown** 渲染，支持 GFM、KaTeX 数学公式、代码语法高亮。

主题名为**「墨韵」**——暖纸底色（`#f6f2ec`），墨色文字（`#2d2a26`），琥珀点缀（`#b89450`）。字体使用 Noto Serif SC（正文）、DM Sans（UI）与 JetBrains Mono（代码）。支持明暗双模，暗色模式下切换为深褐底色与暖白文字，减少夜间阅读的视觉疲劳。

### 特性

- 纯静态，无后端，可部署至任何静态托管服务
- 无追踪器，无分析脚本，无第三方请求
- 响应式布局，适配手机、平板与桌面
- 代码高亮 + 复制按钮，技术写作友好
- 文章目录（IntersectionObserver 高亮当前位置）
- 阅读进度条 + 图片灯箱 + 自定义光标
- 构建时自动生成 RSS 订阅源

## 开始使用

1. 复制 `src/data/profile.example.js` 为 `src/data/profile.js`，编辑个人信息
2. 编辑本文件（`content/pages/about.md`），自由撰写关于页内容
3. 在 `content/posts/` 目录下添加 `.md` 文件，填写 YAML 头部信息后即可发布文章
