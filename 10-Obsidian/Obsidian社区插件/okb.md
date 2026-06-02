---
uid: 1780392511431000
title: 'Obsidian 插件：Vault Knowledge Base'
tags: ['搜索与排序', '效率工具', '自动化与AI', 'obsidian插件']
description: '可以通过本地的obsidian-kb语义索引来搜索当前仓库。'
author: AI
type: auto
draft: false
editable: false
modified: 20240101000000
---

# Obsidian 插件：Vault Knowledge Base

> [!Note] 插件名片
> - 插件名称：Vault Knowledge Base
> - 插件作者：dgalichet
> - 插件说明：可以通过本地的obsidian-kb语义索引来搜索当前仓库。
> - 插件分类：['搜索与排序', '效率工具', '自动化与AI', 'obsidian插件']
> - 项目地址：[点我访问](https://github.com/dgalichet/obsidian-kb-plugin)
> - 国内下载地址：[下载安装](https://pkmer.cn/products/plugin/pluginMarket/?okb)
> - 自述文件：[Readme](https://ghproxy.net/https://raw.githubusercontent.com/dgalichet/obsidian-kb-plugin/master/README.md)

![Vault Knowledge Base](https://cdn.pkmer.cn/covers/okb_html_0.png!pkmer)

## 概述

### 主要功能
Vault Knowledge Base（OKB）将Obsidian库连接到LLM代理，通过本地`obsidian - kb`语义索引搜索当前库。它包装了本地`obsidian - kb`服务，提供搜索、相关笔记和索引维护的侧边面板，同时通过MCP向代理暴露库。

### 适用场景
适用于个人或团队知识管理场景，帮助用户在Obsidian中更好地搜索、关联笔记，也便于LLM代理在不将库上传到托管知识服务的情况下检索和处理笔记。

### 核心特色
- 支持词法、语义和图搜索，能发现相关笔记。
- 本地处理索引和检索数据，保障数据安全。
- 既在Obsidian内提供搜索等功能，又能通过MCP向外部代理暴露库。

### 使用建议
该插件并非独立搜索引擎，需在同一机器上安装`obsidian - kb` CLI。在桌面端，OKB会启动`obsidian - kb serve`作为本地外部进程，并通过本地HTTP与之通信。使用前确保CLI安装并正确配置。


> [!help] 
> 这篇插件文章还没有人贡献，欢迎占坑！
> 如果您有好的想法欢迎提交PR或者文末留言。
> 

---


