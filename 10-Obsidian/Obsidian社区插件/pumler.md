---
uid: 2026060213561436
title: 'Obsidian 插件：Pumler Diagrams'
tags: ['图表与可视化', '第三方工具集成', '效率工具', 'obsidian插件']
description: '这个插件还没经过Obsidian官方人员的人工审核。它能根据代码块渲染PlantUML、Structurizr和Mermaid图表。'
author: AI
type: auto
draft: false
editable: false
modified: 20240101000000
---

# Obsidian 插件：Pumler Diagrams

> [!Note] 插件名片
> - 插件名称：Pumler Diagrams
> - 插件作者：pumler
> - 插件说明：这个插件还没经过Obsidian官方人员的人工审核。它能根据代码块渲染PlantUML、Structurizr和Mermaid图表。
> - 插件分类：['图表与可视化', '第三方工具集成', '效率工具', 'obsidian插件']
> - 项目地址：[点我访问](https://github.com/pumler/plugin-obsidian)
> - 国内下载地址：[下载安装](https://pkmer.cn/products/plugin/pluginMarket/?pumler)
> - 自述文件：[Readme](https://ghproxy.net/https://raw.githubusercontent.com/pumler/plugin-obsidian/master/README.md)

![Pumler Diagrams](https://cdn.pkmer.cn/covers/pumler_internal_0.png!pkmer)

## 概述

### Pumler Diagrams插件总结
1. **主要功能**：可从Obsidian笔记的`pumler`代码块渲染PlantUML、Structurizr DSL和Mermaid图表，将图表源发送到公共Pumler渲染API并把返回的SVG插入笔记。
2. **适用场景**：适用于需要一个渲染器处理多种图表语言，且无需本地PlantUML、Structurizr或Mermaid服务的保险库。
3. **核心特色**：
    - 用一种代码块格式渲染多种图表。
    - 支持每个图表的`light`、`dark`或`auto`主题。
    - 编辑图表时去抖动后再调用渲染API。
    - 磁盘缓存30个最近使用的渲染SVG。
    - 提供可折叠摘要行和可缩放的大预览模态框。
4. **使用建议**：添加带有YAML头的`pumler`代码块来使用，该插件处理`pumler`代码块，不替换Obsidian原生`mermaid`渲染器，也不直接处理`mermaid`、`plantuml`或`structurizr`代码块。每个图表在代码块顶部的YAML头中配置。


> [!help] 
> 这篇插件文章还没有人贡献，欢迎占坑！
> 如果您有好的想法欢迎提交PR或者文末留言。
> 

---


