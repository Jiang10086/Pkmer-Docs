---
uid: 1780392512020000
title: 'Obsidian 插件：Second Brain Sync'
tags: ['第三方工具集成', '搜索与排序', '效率工具', 'obsidian插件']
description: '这个插件还没经过Obsidian官方人员的人工审核哦。它能把你的Obsidian笔记同步到你在Cloudflare Workers上自建的第二大脑MCP服务器。你还能在Obsidian里搜索你的“大脑”呢。'
author: AI
type: auto
draft: false
editable: false
modified: 20240101000000
---

# Obsidian 插件：Second Brain Sync

> [!Note] 插件名片
> - 插件名称：Second Brain Sync
> - 插件作者：Rahil Pirani
> - 插件说明：这个插件还没经过Obsidian官方人员的人工审核哦。它能把你的Obsidian笔记同步到你在Cloudflare Workers上自建的第二大脑MCP服务器。你还能在Obsidian里搜索你的“大脑”呢。
> - 插件分类：['第三方工具集成', '搜索与排序', '效率工具', 'obsidian插件']
> - 项目地址：[点我访问](https://github.com/rahilp/second-brain-obsidian-plugin)
> - 国内下载地址：[下载安装](https://pkmer.cn/products/plugin/pluginMarket/?second-brain-sync)
> - 自述文件：[Readme](https://ghproxy.net/https://raw.githubusercontent.com/rahilp/second-brain-obsidian-plugin/master/README.md)



## 概述

### Second Brain Sync插件总结
1. **主要功能**：可将Obsidian笔记同步到自托管的Second Brain MCP服务器，支持一键或用热键同步单条笔记、批量同步特定标签的所有笔记、自动同步带特定标签的笔记，能自动拆分长笔记，状态栏显示上次同步时间。
2. **适用场景**：适用于希望将Obsidian笔记同步到自己的AI记忆库，并能在Obsidian内或支持MCP的AI工具中进行语义搜索的用户。
3. **核心特色**：基于Cloudflare Workers + Vectorize构建，数据存储在自己的基础设施上，保障数据安全。
4. **使用建议**：使用前需部署Second Brain Worker，部署后在插件设置中填入Worker URL和Auth token并测试连接。设置同步标签，在笔记的前置元数据中添加该标签即可同步。可选择手动同步或开启自动同步，自动同步可设置延迟时间。


> [!help] 
> 这篇插件文章还没有人贡献，欢迎占坑！
> 如果您有好的想法欢迎提交PR或者文末留言。
> 

---


