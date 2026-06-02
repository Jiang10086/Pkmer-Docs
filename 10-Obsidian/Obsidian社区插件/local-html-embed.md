---
uid: 1780392511243001
title: 'Obsidian 插件：Local HTML Embed'
tags: ['第三方工具集成', '多媒体', '效率工具', 'obsidian插件']
description: '可以通过html嵌入代码块在笔记里嵌入仓库本地的HTML文件。'
author: AI
type: auto
draft: false
editable: false
modified: 20240101000000
---

# Obsidian 插件：Local HTML Embed

> [!Note] 插件名片
> - 插件名称：Local HTML Embed
> - 插件作者：shygoly
> - 插件说明：可以通过html嵌入代码块在笔记里嵌入仓库本地的HTML文件。
> - 插件分类：['第三方工具集成', '多媒体', '效率工具', 'obsidian插件']
> - 项目地址：[点我访问](https://github.com/shygoly/obsidian-local-html-embed)
> - 国内下载地址：[下载安装](https://pkmer.cn/products/plugin/pluginMarket/?local-html-embed)
> - 自述文件：[Readme](https://ghproxy.net/https://raw.githubusercontent.com/shygoly/obsidian-local-html-embed/master/README.md)



## 概述

### 插件名称
Local HTML Embed

### 主要功能
通过 `html-embed` 代码块将本地 HTML 文件嵌入笔记，支持在 iframe 中嵌入 `.html` 文件，可使用显式的相对路径或自动模式，能设置固定 iframe 高度，也支持自动高度模式。

### 适用场景
适用于在 Obsidian 库中保存独立 HTML 报告、图表、仪表盘或交互式原型，想直接从 Markdown 笔记中查看这些内容的场景。

### 核心特色
- 保留 UTF - 8 文本，支持使用生成的 `<base>` URL 加载相对资源。
- 为常见的标签/卡片 HTML 布局注入备用主题变量。
- 为常见的基于章节的 HTML 布局添加可折叠展示功能。

### 使用建议
手动安装时，从最新版本下载 `main.js`、`manifest.json` 和 `versions.json`，在库中创建 `.obsidian/plugins/local-html-embed/` 文件夹并放入文件，重启 Obsidian 或重新加载插件后在设置中启用。使用时，在代码块中输入 HTML 文件相对库根目录的路径即可嵌入，还可设置固定高度。


> [!help] 
> 这篇插件文章还没有人贡献，欢迎占坑！
> 如果您有好的想法欢迎提交PR或者文末留言。
> 

---


