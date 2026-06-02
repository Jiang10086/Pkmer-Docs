---
uid: 2026060213561435
title: 'Obsidian 插件：PUML Viewer'
tags: ['第三方工具集成', '图表与可视化', '编程与脚本', 'obsidian插件']
description: '这个插件还没经过Obsidian官方人员的人工审核。它能将 .puml 文件和Markdown代码块中的内容渲染成PlantUML图表。'
author: AI
type: auto
draft: false
editable: false
modified: 20240101000000
---

# Obsidian 插件：PUML Viewer

> [!Note] 插件名片
> - 插件名称：PUML Viewer
> - 插件作者：andreykolygin
> - 插件说明：这个插件还没经过Obsidian官方人员的人工审核。它能将 .puml 文件和Markdown代码块中的内容渲染成PlantUML图表。
> - 插件分类：['第三方工具集成', '图表与可视化', '编程与脚本', 'obsidian插件']
> - 项目地址：[点我访问](https://github.com/andreykolygin/obsidian-puml-viewer)
> - 国内下载地址：[下载安装](https://pkmer.cn/products/plugin/pluginMarket/?puml-viewer)
> - 自述文件：[Readme](https://ghproxy.net/https://raw.githubusercontent.com/andreykolygin/obsidian-puml-viewer/master/README.md)

![PUML Viewer](https://cdn.pkmer.cn/covers/puml-viewer_html_0.png!pkmer)

## 概述

### 主要功能
- 渲染 `.puml`、`.mermaid` 等格式的图表文件及 Markdown 代码块中的 PlantUML/Mermaid 图表。
- 提供自定义图表文件视图，有“查看”和“编辑”两种模式。
- 具备图表工具栏操作，如刷新、缩放、导出为 `.png`、`.svg`、`.txt` 等格式。
- 支持在图表视图中拖动平移，渲染时自动适配查看器宽度，源文件更改时自动刷新。
- 支持 Markdown 嵌入式渲染，可在代码和图表间切换，有缩放覆盖层。

### 适用场景
适用于需要在 Obsidian 中绘制和查看 PlantUML/Mermaid 图表的场景，如项目规划、流程设计等。

### 核心特色
- 支持多种渲染服务，包括 PlantUML 服务器、Kroki 和本地服务器。
- 支持 `SVG` 和 `PNG` 格式。
- 具备启动恢复功能，重启 Obsidian 后可重新打开并渲染之前打开的图表文件。

### 使用建议
- 安装时将相关文件复制到 `<YourVault>/.obsidian/plugins/puml - viewer/` 目录，然后在设置中启用插件。
- 打开支持的图表文件后，运行“Open current diagram file in viewer”命令，可在工具栏切换“查看”和“编辑”模式。


> [!help] 
> 这篇插件文章还没有人贡献，欢迎占坑！
> 如果您有好的想法欢迎提交PR或者文末留言。
> 

---


