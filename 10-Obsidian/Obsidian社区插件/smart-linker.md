---
uid: 1780392512060001
title: 'Obsidian 插件：Smart Linker'
tags: ['自动化与AI', '搜索与排序', '模板与链接处理', '效率工具', 'obsidian插件']
description: '它能借助向量搜索（Vector Search）插件的AI嵌入技术，自动查找并插入语义相关的笔记。'
author: AI
type: auto
draft: false
editable: false
modified: 20240101000000
---

# Obsidian 插件：Smart Linker

> [!Note] 插件名片
> - 插件名称：Smart Linker
> - 插件作者：lemannrus
> - 插件说明：它能借助向量搜索（Vector Search）插件的AI嵌入技术，自动查找并插入语义相关的笔记。
> - 插件分类：['自动化与AI', '搜索与排序', '模板与链接处理', '效率工具', 'obsidian插件']
> - 项目地址：[点我访问](https://github.com/lemannrus/smart-linker)
> - 国内下载地址：[下载安装](https://pkmer.cn/products/plugin/pluginMarket/?smart-linker)
> - 自述文件：[Readme](https://ghproxy.net/https://raw.githubusercontent.com/lemannrus/smart-linker/master/README.md)



## 概述

### Smart Linker插件总结
1. **主要功能**：借助AI嵌入技术自动查找并插入语义相关的笔记。读取预计算的向量嵌入，利用余弦相似度发现笔记间的联系。
2. **适用场景**：适用于Obsidian用户在整理笔记时，希望快速找到与当前笔记语义相关内容的场景。
3. **核心特色**：
    - 基于内容语义而非关键词查找相似笔记。
    - 在笔记末尾的专用块插入相关链接。
    - 利用预计算嵌入实现快速本地搜索。
    - 自动去重，处理分块嵌入。
    - 可配置链接数量、相似度阈值、排除文件夹和显示格式。
    - 仅修改管理块，不触碰笔记内容。
4. **使用建议**：使用前需安装[Vector Search](https://github.com/ashwin271/obsidian-vector-search)插件生成笔记嵌入。先安装Ollama并拉取嵌入模型，再安装Vector Search插件构建嵌入索引。可从社区插件安装，也可手动安装。打开笔记后，通过`Cmd/Ctrl + P`运行“Smart Linker: Update related links for current note”命令更新相关链接。


> [!help] 
> 这篇插件文章还没有人贡献，欢迎占坑！
> 如果您有好的想法欢迎提交PR或者文末留言。
> 

---


