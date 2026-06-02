---
uid: 1780392512103000
title: 'Obsidian 插件：LRU Tab Limiter'
tags: ['文件管理', '界面优化', '效率工具', 'obsidian插件']
description: '这个插件还没经过Obsidian官方人员的手动审核。它能通过替换最久未使用的标签页，将Markdown标签页数量控制在一定限度内。'
author: AI
type: auto
draft: false
editable: false
modified: 20240101000000
---

# Obsidian 插件：LRU Tab Limiter

> [!Note] 插件名片
> - 插件名称：LRU Tab Limiter
> - 插件作者：Ivan Chen
> - 插件说明：这个插件还没经过Obsidian官方人员的手动审核。它能通过替换最久未使用的标签页，将Markdown标签页数量控制在一定限度内。
> - 插件分类：['文件管理', '界面优化', '效率工具', 'obsidian插件']
> - 项目地址：[点我访问](https://github.com/fireshort/obsidian-tab-limit)
> - 国内下载地址：[下载安装](https://pkmer.cn/products/plugin/pluginMarket/?tab-limit-lru)
> - 自述文件：[Readme](https://ghproxy.net/https://raw.githubusercontent.com/fireshort/obsidian-tab-limit/master/README.md)



## 概述

### LRU Tab Limiter插件总结
1. **主要功能**：该插件可将打开的Markdown标签页数量控制在可配置的限制范围内。当打开新标签页会超出限制时，它会关闭最久未使用的Markdown标签页，而非阻止新标签页打开。
2. **适用场景**：适用于Obsidian用户在处理大量Markdown文件时，避免打开过多标签页导致界面混乱，帮助用户保持工作区的简洁。
3. **核心特色**：采用最近最少使用（LRU）策略，切换到某个标签页会将其标记为最近使用，优先替换较旧的非活动标签页。
4. **使用建议**：在插件设置中可选择全局Markdown标签页的最大数量，默认限制为5个。不要同时启用此插件和原始Tab Limiter插件，二者管理相同的工作区行为，会相互冲突。手动安装时，需按步骤构建插件并将相关文件复制到指定目录，最后在社区插件中启用。


> [!help] 
> 这篇插件文章还没有人贡献，欢迎占坑！
> 如果您有好的想法欢迎提交PR或者文末留言。
> 

---


