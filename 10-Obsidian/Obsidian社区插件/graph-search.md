---
uid: 1780392511142001
title: 'Obsidian 插件：Graph Search'
tags: ['搜索与排序', '图表与可视化', '效率工具', '图谱', 'obsidian插件']
description: '它可以结合标题和正文的相关性，通过图链接的接近程度来搜索和排序笔记。'
author: AI
type: auto
draft: false
editable: false
modified: 20240101000000
---

# Obsidian 插件：Graph Search

> [!Note] 插件名片
> - 插件名称：Graph Search
> - 插件作者：scottschroeder
> - 插件说明：它可以结合标题和正文的相关性，通过图链接的接近程度来搜索和排序笔记。
> - 插件分类：['搜索与排序', '图表与可视化', '效率工具', '图谱', 'obsidian插件']
> - 项目地址：[点我访问](https://github.com/scottschroeder/obsidian-graph-search)
> - 国内下载地址：[下载安装](https://pkmer.cn/products/plugin/pluginMarket/?graph-search)
> - 自述文件：[Readme](https://ghproxy.net/https://raw.githubusercontent.com/scottschroeder/obsidian-graph-search/master/README.md)



## 概述

### Graph Search插件总结
1. **主要功能**：结合图链接接近度、标题和正文相关性对笔记进行搜索和排序。
2. **适用场景**：当普通搜索结果过多，希望获取与特定笔记或人物相关的结果时使用。
3. **核心特色**：
    - 可根据与一个或多个“临近”笔记的图接近度对匹配结果进行排序。
    - 能在考虑图距离的同时，将文本搜索与标签和路径结合。
    - 可微调评分权重和衰减以适配个人知识库。
4. **使用建议**：
    - 先在Obsidian中启用插件，通过命令面板运行“Graph query”命令，输入查询内容并回车。
    - 查询语法支持普通词汇，也可使用过滤器，如“near”“tag”“path”。
    - 可在设置的高级评分中开启调试模式，查看距离、标题、正文和总分的详细信息。不过目前搜索功能较基础，搜索权重设定较主观，且每次打开搜索模态框都会重新构建索引和图。


> [!help] 
> 这篇插件文章还没有人贡献，欢迎占坑！
> 如果您有好的想法欢迎提交PR或者文末留言。
> 

---


