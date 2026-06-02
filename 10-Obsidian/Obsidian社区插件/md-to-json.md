---
uid: 1780392511265001
title: 'Obsidian 插件：Markdown to JSON'
tags: ['数据处理', '编辑工具', '文字处理', '效率工具', 'obsidian插件']
description: '它能将Markdown笔记以结构化的JSON块形式复制到剪贴板。'
author: AI
type: auto
draft: false
editable: false
modified: 20240101000000
---

# Obsidian 插件：Markdown to JSON

> [!Note] 插件名片
> - 插件名称：Markdown to JSON
> - 插件作者：Meghan Lendhe
> - 插件说明：它能将Markdown笔记以结构化的JSON块形式复制到剪贴板。
> - 插件分类：['数据处理', '编辑工具', '文字处理', '效率工具', 'obsidian插件']
> - 项目地址：[点我访问](https://github.com/meghan-lendhe/md-to-json)
> - 国内下载地址：[下载安装](https://pkmer.cn/products/plugin/pluginMarket/?md-to-json)
> - 自述文件：[Readme](https://ghproxy.net/https://raw.githubusercontent.com/meghan-lendhe/md-to-json/master/README.md)



## 概述

### Markdown to JSON插件总结
1. **主要功能**：在Obsidian命令面板添加“Copy Markdown as JSON blocks”命令，可将当前Markdown笔记转换为有序的JSON块并复制到剪贴板。
2. **适用场景**：适用于需要将Obsidian中的案例研究笔记快速布局到Figma页面的场景，与Figma的“JSON to Text”插件配合使用，能为案例研究页面快速生成独立文本图层。
3. **核心特色**：将Markdown不同元素转换为特定类型的JSON块，如标题转换为`h1` - `h6`，非空行和列表项各自成为独立块；生成的JSON块包含`type`、`text`、`id`等字段，`id`便于后续排序和更新。
4. **使用建议**：先在Obsidian中打开案例研究笔记，通过`Ctrl + P`打开命令面板，运行“Copy Markdown as JSON blocks”；再打开Figma，运行“JSON to Text”插件，将复制的JSON粘贴到插件界面并点击导入。手动安装需先构建插件，再将`manifest.json`和`main.js`复制到指定目录。


> [!help] 
> 这篇插件文章还没有人贡献，欢迎占坑！
> 如果您有好的想法欢迎提交PR或者文末留言。
> 

---


