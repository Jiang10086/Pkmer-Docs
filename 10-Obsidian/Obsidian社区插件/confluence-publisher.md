---
uid: 1780392511044000
title: 'Obsidian 插件：Confluence Publisher'
tags: ['第三方工具集成', '发布工具', '效率工具', 'obsidian插件']
description: '这个插件还没经过Obsidian官方人员的人工审核。可以用REST API把当前激活的笔记同步到Confluence。'
author: AI
type: auto
draft: false
editable: false
modified: 20240101000000
---

# Obsidian 插件：Confluence Publisher

> [!Note] 插件名片
> - 插件名称：Confluence Publisher
> - 插件作者：grhawk
> - 插件说明：这个插件还没经过Obsidian官方人员的人工审核。可以用REST API把当前激活的笔记同步到Confluence。
> - 插件分类：['第三方工具集成', '发布工具', '效率工具', 'obsidian插件']
> - 项目地址：[点我访问](https://github.com/grhawk/obsidian-2-confluence)
> - 国内下载地址：[下载安装](https://pkmer.cn/products/plugin/pluginMarket/?confluence-publisher)
> - 自述文件：[Readme](https://ghproxy.net/https://raw.githubusercontent.com/grhawk/obsidian-2-confluence/master/README.md)



## 概述

### Confluence Publisher插件总结
1. **主要功能**：借助REST API将Obsidian中的当前笔记同步到Confluence，把Obsidian风格的Markdown转换为HTML（Confluence存储格式），可更新或创建目标空间中的页面。
2. **适用场景**：适用于需要将Obsidian笔记同步到Confluence进行团队协作、知识共享的场景。
3. **核心特色**：能将Markdown转换为Confluence存储HTML；可通过前置元数据页面ID或标题查找更新现有页面；能在可选父页面下创建新页面；还会将Confluence页面ID存回前置元数据。
4. **使用建议**：先安装依赖并构建插件，将相关文件复制到保险库插件文件夹，在Obsidian中启用并配置设置。使用时，打开要同步的笔记，通过命令面板运行“Sync active note to Confluence”。若前置元数据中有页面ID则更新现有页面，无则按标题查找更新，都不满足则创建新页面并将ID存回前置元数据。同时要获取好Confluence的空间密钥、API令牌和父页面ID等信息。


> [!help] 
> 这篇插件文章还没有人贡献，欢迎占坑！
> 如果您有好的想法欢迎提交PR或者文末留言。
> 

---


