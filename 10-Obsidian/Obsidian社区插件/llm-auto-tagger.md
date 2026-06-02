---
uid: 1780392511239001
title: 'Obsidian 插件：LLM Auto Tagger'
tags: ['自动化与AI', '编辑工具', '效率工具', '第三方工具集成', 'obsidian插件']
description: '这个插件还没经过Obsidian官方人员的人工审核。它能利用你配置好的大语言模型（LLM）应用程序编程接口（API），自动把仓库里现有的标签添加到笔记中。'
author: AI
type: auto
draft: false
editable: false
modified: 20240101000000
---

# Obsidian 插件：LLM Auto Tagger

> [!Note] 插件名片
> - 插件名称：LLM Auto Tagger
> - 插件作者：Matboi
> - 插件说明：这个插件还没经过Obsidian官方人员的人工审核。它能利用你配置好的大语言模型（LLM）应用程序编程接口（API），自动把仓库里现有的标签添加到笔记中。
> - 插件分类：['自动化与AI', '编辑工具', '效率工具', '第三方工具集成', 'obsidian插件']
> - 项目地址：[点我访问](https://github.com/matbo1/llm-auto-tagger)
> - 国内下载地址：[下载安装](https://pkmer.cn/products/plugin/pluginMarket/?llm-auto-tagger)
> - 自述文件：[Readme](https://ghproxy.net/https://raw.githubusercontent.com/matbo1/llm-auto-tagger/master/README.md)



## 概述

### 主要功能
LLM Auto Tagger是一款Obsidian插件，借助配置好的LLM API，自动为Markdown笔记添加现有库标签，将匹配的标签写入笔记前言。

### 适用场景
适用于已有标签系统的Obsidian库。

### 核心特色
- 笔记闲置后自动运行。
- 每次标记前从Obsidian元数据读取候选标签。
- 仅允许从现有库标签中选择。
- 保留现有标签和其他前言字段。
- 支持多种API，如OpenAI、Anthropic Claude、Google Gemini等。
- 提供连接测试，可检查API URL、API密钥和模型设置。

### 使用建议
- 配置时需设置提供商、LLM API URL和API密钥，部分模式下模型可选。
- 使用自动标记功能前，点击“Test connection”按钮测试连接，确保配置的提供商可访问。
- 使用含隐私内容的笔记前，查看所选提供商的隐私、计费、数据使用和保留条款。


> [!help] 
> 这篇插件文章还没有人贡献，欢迎占坑！
> 如果您有好的想法欢迎提交PR或者文末留言。
> 

---


