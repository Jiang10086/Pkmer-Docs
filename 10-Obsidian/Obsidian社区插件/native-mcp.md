---
uid: 1780392511300000
title: 'Obsidian 插件：Native MCP'
tags: ['搜索与排序', '文件管理', '第三方工具集成', '自动化与AI', '效率工具', 'obsidian插件']
description: '这是一个MCP服务器，能让AI助手读取、搜索、创建和修改你仓库里的笔记。'
author: AI
type: auto
draft: false
editable: false
modified: 20240101000000
---

# Obsidian 插件：Native MCP

> [!Note] 插件名片
> - 插件名称：Native MCP
> - 插件作者：Utkarsh Srivastava
> - 插件说明：这是一个MCP服务器，能让AI助手读取、搜索、创建和修改你仓库里的笔记。
> - 插件分类：['搜索与排序', '文件管理', '第三方工具集成', '自动化与AI', '效率工具', 'obsidian插件']
> - 项目地址：[点我访问](https://github.com/usrivastava92/obsidian-native-mcp)
> - 国内下载地址：[下载安装](https://pkmer.cn/products/plugin/pluginMarket/?native-mcp)
> - 自述文件：[Readme](https://ghproxy.net/https://raw.githubusercontent.com/usrivastava92/obsidian-native-mcp/master/README.md)

![Native MCP](https://cdn.pkmer.cn/covers/native-mcp_html_0.png!pkmer)

## 概述

### Native MCP 插件总结
1. **主要功能**：这是一个基于 Model Context Protocol 的服务器插件，能让 AI 助手（如 Claude Desktop、Cursor 等）直接、安全且高效地访问 Obsidian 保险库，可实现读取、搜索、创建和修改笔记。
2. **适用场景**：适用于需要借助 AI 助手对 Obsidian 笔记进行操作的场景，如利用 AI 辅助编辑笔记内容、搜索相关信息等。
3. **核心特色**：以最小化每次编辑时大语言模型（LLM）需处理的字节数为设计目标。每次读取返回内容和加密哈希，每次写入声明预期的前置哈希，多数编辑只需进行小范围替换或打补丁，而非重写整个文件。
4. **使用建议**：有两种使用方式，一是作为 Obsidian 插件，一键安装，能自动发现保险库，有设置界面可按工具进行开关设置，通过 HTTP/SSE 和令牌在 Obsidian 内运行；二是使用 CLI，为独立的 Node 二进制文件，可通过环境变量或配置文件配置，通过标准输入输出以 JSON - RPC 通信。


> [!help] 
> 这篇插件文章还没有人贡献，欢迎占坑！
> 如果您有好的想法欢迎提交PR或者文末留言。
> 

---


