---
uid: 1780392511014001
title: 'Obsidian 插件：Claude Code Bridge'
tags: ['第三方工具集成', '编程与脚本', '自动化与AI', '效率工具', 'obsidian插件']
description: '这个插件还没经过Obsidian官方人员的人工审核。可以把选中的文本连接到Claude Code CLI，实现实时上下文共享。'
author: AI
type: auto
draft: false
editable: false
modified: 20240101000000
---

# Obsidian 插件：Claude Code Bridge

> [!Note] 插件名片
> - 插件名称：Claude Code Bridge
> - 插件作者：othnielsu
> - 插件说明：这个插件还没经过Obsidian官方人员的人工审核。可以把选中的文本连接到Claude Code CLI，实现实时上下文共享。
> - 插件分类：['第三方工具集成', '编程与脚本', '自动化与AI', '效率工具', 'obsidian插件']
> - 项目地址：[点我访问](https://github.com/radical7vii/obsidian-claude-code-bridge)
> - 国内下载地址：[下载安装](https://pkmer.cn/products/plugin/pluginMarket/?claude-code-bridge)
> - 自述文件：[Readme](https://ghproxy.net/https://raw.githubusercontent.com/radical7vii/obsidian-claude-code-bridge/master/README.md)



## 概述

### 主要功能
Claude Code Bridge 是一款 Obsidian 插件，可将选中的文本实时共享到 Claude Code CLI，让 Claude Code 能获取所选文本作为上下文。

### 适用场景
适用于在 Obsidian 中编辑文本时，需要借助 Claude Code 进行代码分析、生成等操作的场景。

### 核心特色
- 模仿 VS Code 的 IDE MCP 服务器协议，通过本地 WebSocket 服务器实现文本实时共享。
- 当在 Obsidian 中选中文本时，运行 Claude Code 的相邻终端会自动显示所选文本信息。

### 使用建议
1. 可通过源码构建并安装到 Obsidian。
2. 启用插件后，在 Obsidian 所在的库目录下打开终端，运行 `claude` 和 `/ide` 连接到 Obsidian。
3. 注意 Claude Code 必须从库目录启动，以确保工作区匹配正常。


> [!help] 
> 这篇插件文章还没有人贡献，欢迎占坑！
> 如果您有好的想法欢迎提交PR或者文末留言。
> 

---


