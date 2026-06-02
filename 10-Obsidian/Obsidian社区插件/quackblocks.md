---
uid: 2026060213561441
title: 'Obsidian 插件：QuackBlocks'
tags: ['数据分析', '数据处理', '表格', '图表与可视化', '编程与脚本', 'obsidian插件']
description: '它能借助DuckDB WASM实现可执行的SQL代码块功能 —— 可以查询Parquet数据，还能在文档里直接渲染表格和图表。'
author: AI
type: auto
draft: false
editable: false
modified: 20240101000000
---

# Obsidian 插件：QuackBlocks

> [!Note] 插件名片
> - 插件名称：QuackBlocks
> - 插件作者：yllucsyeoj
> - 插件说明：它能借助DuckDB WASM实现可执行的SQL代码块功能 —— 可以查询Parquet数据，还能在文档里直接渲染表格和图表。
> - 插件分类：['数据分析', '数据处理', '表格', '图表与可视化', '编程与脚本', 'obsidian插件']
> - 项目地址：[点我访问](https://github.com/yllucsyeoj/quackblocks)
> - 国内下载地址：[下载安装](https://pkmer.cn/products/plugin/pluginMarket/?quackblocks)
> - 自述文件：[Readme](https://ghproxy.net/https://raw.githubusercontent.com/yllucsyeoj/quackblocks/master/README.md)



## 概述

### 主要功能
QuackBlocks 是基于 DuckDB WASM 的 Obsidian 插件，可在 Obsidian 内运行 SQL 代码块，对本地 Parquet 文件进行查询，并将结果以内联表格或图表形式呈现。

### 适用场景
适用于需要在 Obsidian 笔记中对 Parquet 数据进行分析、可视化展示的场景，如数据报告撰写、数据分析记录等。

### 核心特色
- 无需外部服务器，直接在 Obsidian 内运行分析型 SQL。
- 支持从前端声明的 Parquet 文件加载表格。
- 结果以格式化 HTML 表格和多种类型的 Observable Plot 图表展示。
- 可通过简洁指令语法为每个代码块配置图表。
- 图表采用显式 SVG 尺寸，支持可靠的 PDF 导出。

### 使用建议
1. 手动安装需从最新版本下载相关文件，复制到指定文件夹并在社区插件设置中启用；也可通过 BRAT 插件添加。
2. 在笔记的前端声明数据源，支持相对路径、绝对路径和家目录扩展。
3. 编写 `quack` 代码块进行数据查询和可视化。


> [!help] 
> 这篇插件文章还没有人贡献，欢迎占坑！
> 如果您有好的想法欢迎提交PR或者文末留言。
> 

---


