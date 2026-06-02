---
uid: 1780392511607000
title: 'Obsidian 插件：OpenCode Links Graph'
tags: ['模板与链接处理', '图表与可视化', '效率工具', '图谱', 'obsidian插件']
description: '这个插件还没经过Obsidian官方人员的人工审核。把原始的@.opencode/... Markdown引用当作Obsidian原生图谱视图里的内部链接来处理。'
author: AI
type: auto
draft: false
editable: false
modified: 20240101000000
---

# Obsidian 插件：OpenCode Links Graph

> [!Note] 插件名片
> - 插件名称：OpenCode Links Graph
> - 插件作者：Artur Smirnov
> - 插件说明：这个插件还没经过Obsidian官方人员的人工审核。把原始的@.opencode/... Markdown引用当作Obsidian原生图谱视图里的内部链接来处理。
> - 插件分类：['模板与链接处理', '图表与可视化', '效率工具', '图谱', 'obsidian插件']
> - 项目地址：[点我访问](https://github.com/wlankasper/obsidian-opencode-plugin)
> - 国内下载地址：[下载安装](https://pkmer.cn/products/plugin/pluginMarket/?opencode-links-graph)
> - 自述文件：[Readme](https://ghproxy.net/https://raw.githubusercontent.com/wlankasper/obsidian-opencode-plugin/master/README.md)



## 概述

### OpenCode Links Graph插件总结
1. **主要功能**：扫描Markdown文件中的原始OpenCode链接，将 `@.opencode/...md` 目标解析为真实的库文件，向Obsidian的解析链接元数据添加合成条目，使原生图谱和本地图谱能将这些关系渲染得如同普通内部链接，且不重写Markdown文件。
2. **适用场景**：适用于使用OpenCode风格引用作为规范链接语法的Obsidian库。
3. **核心特色**：通过在运行时添加解析链接元数据，弥补了Obsidian原生图谱无法识别 `@.opencode/...` 这类自定义文本的缺陷，源文件保持OpenCode原生格式，同时Obsidian能显示图谱边。
4. **使用建议**：开发安装时，将插件文件夹复制到 `.obsidian/plugins/opencode-links-graph/` 下，安装依赖并构建。可根据需求在设置中调整OpenCode链接正则、刷新延迟、是否显示通知和调试日志等参数。


> [!help] 
> 这篇插件文章还没有人贡献，欢迎占坑！
> 如果您有好的想法欢迎提交PR或者文末留言。
> 

---


