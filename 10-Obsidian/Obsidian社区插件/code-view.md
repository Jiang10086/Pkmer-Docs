---
uid: 1780392511030001
title: 'Obsidian 插件：Code View'
tags: ['编程与脚本', '编辑工具', '样式与美化', '效率工具', 'obsidian插件']
description: '它是一个只读查看器，可用于查看源代码和以开发者为中心的文件（如py、ps1、sh、ts等），并且能通过Prism实现语法高亮显示。'
author: AI
type: auto
draft: false
editable: false
modified: 20240101000000
---

# Obsidian 插件：Code View

> [!Note] 插件名片
> - 插件名称：Code View
> - 插件作者：casualbot
> - 插件说明：它是一个只读查看器，可用于查看源代码和以开发者为中心的文件（如py、ps1、sh、ts等），并且能通过Prism实现语法高亮显示。
> - 插件分类：['编程与脚本', '编辑工具', '样式与美化', '效率工具', 'obsidian插件']
> - 项目地址：[点我访问](https://github.com/casualbot/obsidian-codeviewer-plugin)
> - 国内下载地址：[下载安装](https://pkmer.cn/products/plugin/pluginMarket/?code-view)
> - 自述文件：[Readme](https://ghproxy.net/https://raw.githubusercontent.com/casualbot/obsidian-codeviewer-plugin/master/README.md)



## 概述

### Code View插件总结
1. **主要功能**：为常见开发及开发者相关文件（如py、ps1、sh等）提供只读的语法高亮查看功能，不执行文件内容。
2. **适用场景**：适用于在Obsidian库中存储AI代理相关文件，如提示、工具配置、说明文件、内存文件等，方便浏览、搜索和链接，也可查看原本只能在编辑器中打开的纯文本源文件。
3. **核心特色**：让开发者文件成为Obsidian库中的一等公民，借助Prism实现语法高亮，渲染路径采用`Prism.tokenize`和DOM遍历，不使用`innerHTML`。
4. **使用建议**：终端用户可通过Obsidian的“设置→社区插件→浏览”安装，也可从[最新GitHub版本](https://github.com/CasualBot/obsidian-codeviewer-plugin/releases/latest)下载。开发此插件需Node.js 20+，可按`npm install`等命令进行操作，还可将构建内容侧载到测试库中。


> [!help] 
> 这篇插件文章还没有人贡献，欢迎占坑！
> 如果您有好的想法欢迎提交PR或者文末留言。
> 

---


