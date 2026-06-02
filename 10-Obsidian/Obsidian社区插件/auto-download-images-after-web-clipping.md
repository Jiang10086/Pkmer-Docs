---
uid: 2026060213561299
title: 'Obsidian 插件：Auto Download Images After Web Clipping'
tags: ['自动化与AI', '图片与PDF', '效率工具', '编辑工具', 'obsidian插件']
description: '网页剪藏后，可自动将远程图片下载到本地仓库。'
author: AI
type: auto
draft: false
editable: false
modified: 20240101000000
---

# Obsidian 插件：Auto Download Images After Web Clipping

> [!Note] 插件名片
> - 插件名称：Auto Download Images After Web Clipping
> - 插件作者：chenxiccc
> - 插件说明：网页剪藏后，可自动将远程图片下载到本地仓库。
> - 插件分类：['自动化与AI', '图片与PDF', '效率工具', '编辑工具', 'obsidian插件']
> - 项目地址：[点我访问](https://github.com/chenxiccc/obsidian-auto-download-images-after-web-clipping)
> - 国内下载地址：[下载安装](https://pkmer.cn/products/plugin/pluginMarket/?auto-download-images-after-web-clipping)
> - 自述文件：[Readme](https://ghproxy.net/https://raw.githubusercontent.com/chenxiccc/obsidian-auto-download-images-after-web-clipping/master/README.md)



## 概述

### 主要功能
使用 Obsidian Web Clipper 剪藏网页时，该插件可自动检测新剪藏的 Markdown 文件，在后台下载文件里所有远程图片，并将文件中的远程图片 URL 替换为本地引用。

### 适用场景
适用于使用 Obsidian Web Clipper 剪藏网页，希望将网页中的图片保存到本地，避免因远程链接失效而无法查看图片的场景。

### 核心特色
- 支持 Markdown 图片语法和 HTML `<img>` 标签。
- 具备防盗链破解功能，利用页面来源 URL 作为 Referer 绕过 CDN 防盗链。

### 使用建议
- 此插件仅支持桌面端，需依赖 Node.js `https` 模块。
- 可在配置中调整文件夹监听范围，默认监听 `Clippings` 文件夹，也能添加更多。
- 图片保存路径有三种模式，可按需选择，默认跟随 Obsidian 附件设置。


> [!help] 
> 这篇插件文章还没有人贡献，欢迎占坑！
> 如果您有好的想法欢迎提交PR或者文末留言。
> 

---


