---
uid: 1780392511042000
title: 'Obsidian 插件：Companion MCP'
tags: ['搜索与排序', '编辑工具', '第三方工具集成', '自动化与AI', '效率工具', 'obsidian插件']
description: '这个插件还没经过Obsidian工作人员的人工审核。它能让人工智能代理通过配套的MCP服务器，使用MCP工具进行仓库语义搜索和编辑器操作。'
author: AI
type: auto
draft: false
editable: false
modified: 20240101000000
---

# Obsidian 插件：Companion MCP

> [!Note] 插件名片
> - 插件名称：Companion MCP
> - 插件作者：yama662607
> - 插件说明：这个插件还没经过Obsidian工作人员的人工审核。它能让人工智能代理通过配套的MCP服务器，使用MCP工具进行仓库语义搜索和编辑器操作。
> - 插件分类：['搜索与排序', '编辑工具', '第三方工具集成', '自动化与AI', '效率工具', 'obsidian插件']
> - 项目地址：[点我访问](https://github.com/yama662607/obsidian-companion-mcp)
> - 国内下载地址：[下载安装](https://pkmer.cn/products/plugin/pluginMarket/?companion-mcp)
> - 自述文件：[Readme](https://ghproxy.net/https://raw.githubusercontent.com/yama662607/obsidian-companion-mcp/master/README.md)



## 概述

### 主要功能
- 多语言语义搜索：借助 `intfloat/multilingual-e5-small` 实现日语、英语等100多种语言的高精度搜索。
- 实时编辑器上下文感知：让AI知晓活动文件、光标位置和文本选择情况。
- 智能笔记管理：对Markdown文件和Frontmatter进行精确的增删改查操作。

### 适用场景
适用于需要进行跨语言语义搜索、高效管理笔记的Obsidian用户。

### 核心特色
- 本地优先架构：所有嵌入和索引操作都在本地机器上进行，保障隐私。

### 使用建议
使用前需同时设置Obsidian插件和MCP服务器。插件安装可手动将 `dist/plugin-release` 内容复制到保险库的 `.obsidian/plugins/companion-mcp/` 目录。对于长笔记，使用 `read_note` 并设置 `anchor.type = "line"`；对于活动编辑器缓冲区，使用相同或更大的 `maxChars` 重新运行 `read_active_context` ，避免依赖延续提示。


> [!help] 
> 这篇插件文章还没有人贡献，欢迎占坑！
> 如果您有好的想法欢迎提交PR或者文末留言。
> 

---


