---
uid: 1780392511244001
title: 'Obsidian 插件：Local REST API Second Brain MCP Extension'
tags: ['第三方工具集成', '编程与脚本', '效率工具', 'obsidian插件']
description: '它是本地REST API的扩展，用于添加第二大脑MCP服务器。'
author: AI
type: auto
draft: false
editable: false
modified: 20240101000000
---

# Obsidian 插件：Local REST API Second Brain MCP Extension

> [!Note] 插件名片
> - 插件名称：Local REST API Second Brain MCP Extension
> - 插件作者：Mehran Ziadloo
> - 插件说明：它是本地REST API的扩展，用于添加第二大脑MCP服务器。
> - 插件分类：['第三方工具集成', '编程与脚本', '效率工具', 'obsidian插件']
> - 项目地址：[点我访问](https://github.com/ziadloo/obsidian-local-rest-api-second-brain-mcp-extension)
> - 国内下载地址：[下载安装](https://pkmer.cn/products/plugin/pluginMarket/?local-rest-api-second-brain-mcp-extension)
> - 自述文件：[Readme](https://ghproxy.net/https://raw.githubusercontent.com/ziadloo/obsidian-local-rest-api-second-brain-mcp-extension/master/README.md)



## 概述

### 插件主要功能
该插件是Obsidian Local REST API的扩展，将Obsidian库转换为支持AI的“第二大脑”，通过暴露专门的Model Context Protocol (MCP)服务器端点，为大语言模型（LLMs）提供对个人知识库的智能、语义化访问。

### 适用场景
适用于需要借助大语言模型处理个人知识库信息的场景，让LLMs能高效获取相关知识。

### 核心特色
1. 采用本地化语义搜索引擎，基于查询含义找到最相关笔记，而非将整个库内容直接提供给LLMs。
2. 结合语义搜索和图遍历（BFS），通过本地嵌入模型找到最佳切入点，再利用Obsidian内部链接收集上下文知识，保证信息高度相关且节省令牌。
3. 依托父插件基础设施，专注于AI知识检索。

### 使用建议
由于需依赖Obsidian Local REST API插件，使用前要确保该插件已正确安装和配置。


> [!help] 
> 这篇插件文章还没有人贡献，欢迎占坑！
> 如果您有好的想法欢迎提交PR或者文末留言。
> 

---


