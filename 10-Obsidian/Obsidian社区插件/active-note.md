---
uid: 2026060213561206
title: 'Obsidian 插件：Active Note'
tags: ['第三方工具集成', '自动化与AI', '效率工具', 'obsidian插件']
description: '它可以将当前活动笔记的路径和所选内容写入一个JSON指针文件，以便与外部工具集成（比如Claude Code、Gemini CLI等）。'
author: AI
type: auto
draft: false
editable: false
modified: 20240101000000
---

# Obsidian 插件：Active Note

> [!Note] 插件名片
> - 插件名称：Active Note
> - 插件作者：davidszp
> - 插件说明：它可以将当前活动笔记的路径和所选内容写入一个JSON指针文件，以便与外部工具集成（比如Claude Code、Gemini CLI等）。
> - 插件分类：['第三方工具集成', '自动化与AI', '效率工具', 'obsidian插件']
> - 项目地址：[点我访问](https://github.com/davidszp/obsidian-active-note)
> - 国内下载地址：[下载安装](https://pkmer.cn/products/plugin/pluginMarket/?active-note)
> - 自述文件：[Readme](https://ghproxy.net/https://raw.githubusercontent.com/davidszp/obsidian-active-note/master/README.md)

![Active Note](https://cdn.pkmer.cn/covers/active-note_internal_0.png!pkmer)

## 概述

### 主要功能
Active Note 是一款 Obsidian 插件，可将当前活动笔记的路径和所选文本写入 JSON 指针文件，方便外部工具获取当前笔记状态。

### 适用场景
适用于需要与外部工具（如 Claude Code、Gemini CLI 等）集成的场景，让外部工具能了解 Obsidian 中当前打开的笔记及所选内容。

### 核心特色
将 Obsidian 的 UI 状态（当前活动笔记）外部化，外部工具可通过读取 JSON 指针文件获取当前笔记上下文。默认写入 `.obsidian/active-note.json` 文件，文件格式清晰，包含笔记路径和可选的所选文本信息。

### 使用建议
若与 Claude Code 集成，从保险库根目录运行 Claude Code，在 `CLAUDE.md` 中添加相关说明，让 Claude 知道如何解析 `@.` 引用，相关配置可在插件设置中复制粘贴。


> [!help] 
> 这篇插件文章还没有人贡献，欢迎占坑！
> 如果您有好的想法欢迎提交PR或者文末留言。
> 

---


