---
uid: 20260602135614
title: 'Obsidian 插件：PlantUML Integrator'
tags: ['第三方工具集成', '图表与可视化', '编程与脚本', '效率工具', 'obsidian插件']
description: '这个插件还没经过Obsidian官方人员的人工审核。它能渲染PlantUML代码块和 .puml 嵌入内容，并且能根据依赖情况自动使缓存失效。'
author: AI
type: auto
draft: false
editable: false
modified: 20240101000000
---

# Obsidian 插件：PlantUML Integrator

> [!Note] 插件名片
> - 插件名称：PlantUML Integrator
> - 插件作者：fangface-hub
> - 插件说明：这个插件还没经过Obsidian官方人员的人工审核。它能渲染PlantUML代码块和 .puml 嵌入内容，并且能根据依赖情况自动使缓存失效。
> - 插件分类：['第三方工具集成', '图表与可视化', '编程与脚本', '效率工具', 'obsidian插件']
> - 项目地址：[点我访问](https://github.com/fangface-hub/obsidian_plantuml_integrator)
> - 国内下载地址：[下载安装](https://pkmer.cn/products/plugin/pluginMarket/?plantuml-integrator)
> - 自述文件：[Readme](https://ghproxy.net/https://raw.githubusercontent.com/fangface-hub/obsidian_plantuml_integrator/master/README.md)



## 概述

### 1. 主要功能
- 在Markdown预览中渲染PlantUML代码块（`plantuml`、`puml`）。
- 渲染 `.puml` 嵌入文件。
- 缓存包含依赖树，在包含文件修改时自动重新渲染。
- 右键点击已渲染的图表可清除缓存并仅重新渲染该图表。
- 支持选择渲染模式，包括远程服务器端点和本地PlantUML服务器。

### 2. 适用场景
适用于需要在Obsidian中绘制和展示PlantUML图表的场景，如软件设计文档、项目架构图等。

### 3. 核心特色
- 依赖感知的缓存失效机制，自动更新图表。
- 提供两种渲染模式，可根据需求灵活选择。

### 4. 使用建议
- 若选择服务器模式，可在设置中配置PlantUML服务器URL，默认使用 `https://kroki.io/plantuml/svg`。
- 若选择本地jar模式，需自行启动PlantUML PicoWeb服务器，可将启动命令注册为用户登录时自动运行，以提高使用效率。


> [!help] 
> 这篇插件文章还没有人贡献，欢迎占坑！
> 如果您有好的想法欢迎提交PR或者文末留言。
> 

---


