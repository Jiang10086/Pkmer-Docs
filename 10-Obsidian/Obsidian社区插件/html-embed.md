---
uid: 1780392511161002
title: 'Obsidian 插件：HTML Embed'
tags: ['第三方工具集成', '多媒体', '编程与脚本', '效率工具', 'obsidian插件']
description: '你可以通过一个简单的html嵌入代码块，在笔记中内联嵌入独立的交互式HTML文件（包含可运行的JavaScript代码）。'
author: AI
type: auto
draft: false
editable: false
modified: 20240101000000
---

# Obsidian 插件：HTML Embed

> [!Note] 插件名片
> - 插件名称：HTML Embed
> - 插件作者：the-pieza
> - 插件说明：你可以通过一个简单的html嵌入代码块，在笔记中内联嵌入独立的交互式HTML文件（包含可运行的JavaScript代码）。
> - 插件分类：['第三方工具集成', '多媒体', '编程与脚本', '效率工具', 'obsidian插件']
> - 项目地址：[点我访问](https://github.com/the-pieza/obsidian-html-embed)
> - 国内下载地址：[下载安装](https://pkmer.cn/products/plugin/pluginMarket/?html-embed)
> - 自述文件：[Readme](https://ghproxy.net/https://raw.githubusercontent.com/the-pieza/obsidian-html-embed/master/README.md)



## 概述

### HTML Embed插件总结
1. **主要功能**：通过简单的`html-embed`代码块，在Obsidian笔记中内联嵌入独立的交互式HTML文件，且支持JavaScript运行。
2. **适用场景**：适用于各类需要在笔记中嵌入交互式内容的场景，如计算机科学笔记旁嵌入算法可视化，学习指南旁嵌入交互式化学图表，项目计划旁嵌入自定义仪表盘等，还可用于算法演示、密码学实验、数学互动演示、实时数据看板、自定义学习工具等。
3. **核心特色**：解决了Obsidian阅读视图对原生`<iframe>`标签和`<script>`块的清理问题，通过自定义代码块，利用`app://`资源协议解析HTML文件，使脚本、样式和本地资源能正确加载，嵌入内容更自然。
4. **使用建议**：使用时在笔记中添加`html-embed`代码块，设置`file`（必填，指定HTML文件路径）、`height`（默认600像素）、`width`（默认100%）等参数。每个嵌入内容下方会有“Open in browser”链接作为备用。


> [!help] 
> 这篇插件文章还没有人贡献，欢迎占坑！
> 如果您有好的想法欢迎提交PR或者文末留言。
> 

---


