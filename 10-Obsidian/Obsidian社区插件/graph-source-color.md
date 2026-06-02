---
uid: 1780392511142002
title: 'Obsidian 插件：Graph Source Color'
tags: ['图谱', '图表与可视化', '样式与美化', 'obsidian插件']
description: 'None'
author: AI
type: auto
draft: false
editable: false
modified: 20240101000000
---

# Obsidian 插件：Graph Source Color

> [!Note] 插件名片
> - 插件名称：Graph Source Color
> - 插件作者：Karl
> - 插件说明：None
> - 插件分类：['图谱', '图表与可视化', '样式与美化', 'obsidian插件']
> - 项目地址：[点我访问](https://github.com/karl-cn/graph-source-color)
> - 国内下载地址：[下载安装](https://pkmer.cn/products/plugin/pluginMarket/?graph-source-color)
> - 自述文件：[Readme](https://ghproxy.net/https://raw.githubusercontent.com/karl-cn/graph-source-color/master/README.md)



## 概述

### 主要功能
Graph Source Color 是一款 Obsidian 插件，可根据链接的“源”笔记动态为图谱节点着色。具备源检测、链接传播、多色节点显示等功能，不修改 Obsidian 原生 `graph.json` 配置。

### 适用场景
适用于对笔记图谱进行可视化管理，通过颜色区分不同来源笔记的场景，帮助用户更直观地理解笔记间的关联。

### 核心特色
- 自动识别配置文件夹内的源笔记，每个文件夹为一个颜色组。
- 递归追踪链接，通过 BFS 传播让链接笔记继承源颜色。
- 多源链接笔记显示分色节点，2 源为左右分色，3 源及以上为饼图分色。
- 提供文件夹树选择器，方便配置源文件夹。
- 父文件夹颜色可级联到未显式设置颜色的子文件夹。

### 使用建议
可通过 Obsidian 社区插件或手动方式安装。安装后在设置中配置多色节点显示、源文件夹及颜色等选项。可参考 [交互式演示](https://karl-cn.github.io/graph-source-color/demo.html) 了解源颜色如何通过链接传播。


> [!help] 
> 这篇插件文章还没有人贡献，欢迎占坑！
> 如果您有好的想法欢迎提交PR或者文末留言。
> 

---


