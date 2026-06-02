---
uid: 1780392511243000
title: 'Obsidian 插件：Local Graph Tag Links'
tags: ['图表与可视化', '图谱', '模板与链接处理', '效率工具', 'obsidian插件']
description: '这个插件还没经过Obsidian工作人员的人工审核。它能让本地图谱展示所有通过共享标签关联起来的笔记。'
author: AI
type: auto
draft: false
editable: false
modified: 20240101000000
---

# Obsidian 插件：Local Graph Tag Links

> [!Note] 插件名片
> - 插件名称：Local Graph Tag Links
> - 插件作者：Lumyo
> - 插件说明：这个插件还没经过Obsidian工作人员的人工审核。它能让本地图谱展示所有通过共享标签关联起来的笔记。
> - 插件分类：['图表与可视化', '图谱', '模板与链接处理', '效率工具', 'obsidian插件']
> - 项目地址：[点我访问](https://github.com/lumyo/obsidian-local-graph-tag-links)
> - 国内下载地址：[下载安装](https://pkmer.cn/products/plugin/pluginMarket/?local-graph-tag-links)
> - 自述文件：[Readme](https://ghproxy.net/https://raw.githubusercontent.com/lumyo/obsidian-local-graph-tag-links/master/README.md)

![Local Graph Tag Links](https://cdn.pkmer.cn/covers/local-graph-tag-links_internal_0.jpeg!pkmer)

## 概述

### 主要功能
修复Obsidian内置本地图谱中共享标签连接的笔记不显示的问题，使本地图谱显示所有通过共享标签连接的笔记。

### 适用场景
适用于使用Obsidian并希望在本地图谱中查看通过共享标签关联笔记的用户。

### 核心特色
通过包装Obsidian内部图引擎原型，在子图数据到达渲染器之前进行拦截，运行自己的广度优先搜索（BFS），注入共享标签的笔记、其前后链接、未解析链接及标签等，且遵循深度设置。

### 使用建议
1. 在“设置→社区插件”中安装并启用该插件。
2. 打开任意笔记的本地图谱（通过“更多选项→打开本地图谱”或命令面板）。
3. 在本地图谱过滤面板中启用“显示标签”。
4. 共享标签连接的笔记将在合适深度显示，原有本地图谱的过滤和切换功能仍正常工作。


> [!help] 
> 这篇插件文章还没有人贡献，欢迎占坑！
> 如果您有好的想法欢迎提交PR或者文末留言。
> 

---


