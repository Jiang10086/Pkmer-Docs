---
uid: 1780392512249000
title: 'Obsidian 插件：Zotero Research Assistant'
tags: ['第三方工具集成', '图片与PDF', '学习与教育', '自动化与AI', 'zotero', 'obsidian插件']
description: '这个插件还没经过Obsidian官方人员的人工审核哈。它能通过Docling流程导入并对Zotero里的PDF文件进行光学字符识别（OCR），同步包括注释在内的元数据，还能借助本地基于Redis的检索增强生成（RAG）技术和你的研究文献进行交流呢。'
author: AI
type: auto
draft: false
editable: false
modified: 20240101000000
---

# Obsidian 插件：Zotero Research Assistant

> [!Note] 插件名片
> - 插件名称：Zotero Research Assistant
> - 插件作者：Jens Mittelbach
> - 插件说明：这个插件还没经过Obsidian官方人员的人工审核哈。它能通过Docling流程导入并对Zotero里的PDF文件进行光学字符识别（OCR），同步包括注释在内的元数据，还能借助本地基于Redis的检索增强生成（RAG）技术和你的研究文献进行交流呢。
> - 插件分类：['第三方工具集成', '图片与PDF', '学习与教育', '自动化与AI', 'zotero', 'obsidian插件']
> - 项目地址：[点我访问](https://github.com/jmiba/zotero-redisearch-rag)
> - 国内下载地址：[下载安装](https://pkmer.cn/products/plugin/pluginMarket/?zotero-redisearch-rag)
> - 自述文件：[Readme](https://ghproxy.net/https://raw.githubusercontent.com/jmiba/zotero-redisearch-rag/master/README.md)

![Zotero Research Assistant](https://cdn.pkmer.cn/covers/zotero-redisearch-rag_internal_0.png!pkmer)

## 概述

### Zotero Research Assistant插件总结
1. **主要功能**：可在Obsidian中导入Zotero项目，提取PDF文本（必要时进行OCR），将文本块索引到Redis Stack，用户能就Zotero文献提问并获得带引用的答案，引用可直接跳转到笔记中的相关文本块。
2. **适用场景**：适用于需要在Obsidian中对Zotero文献进行研究、提问和整理的场景，帮助用户更好地利用Zotero的文献资源进行思考和创作。
3. **核心特色**：采用本地优先的RAG模式，有可编辑的丰富Obsidian笔记；支持增量重新索引，编辑仅更新受影响的文本块；引用可链接到笔记中的具体文本块；聊天会话可保存并导出到笔记；有可选的聊天历史查询重写和代理检索规划功能。
4. **使用建议**：先在Obsidian中选择Zotero项目，由Docling提取文本，文本块嵌入并索引到Redis Stack后即可提问获取带引用的答案。注意导入的笔记中有同步部分和文本块标记。


> [!help] 
> 这篇插件文章还没有人贡献，欢迎占坑！
> 如果您有好的想法欢迎提交PR或者文末留言。
> 

---


