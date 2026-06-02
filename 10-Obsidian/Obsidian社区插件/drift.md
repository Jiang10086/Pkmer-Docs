---
uid: 1780392511058000
title: 'Obsidian 插件：Drift'
tags: ['文件管理', '编辑工具', '效率工具', 'obsidian插件']
description: '这个插件还没经过Obsidian工作人员的人工审核。它能检测外部文件的变化，并以并排对比的方式显示差异，还能逐块选择接受或拒绝更改。'
author: AI
type: auto
draft: false
editable: false
modified: 20240101000000
---

# Obsidian 插件：Drift

> [!Note] 插件名片
> - 插件名称：Drift
> - 插件作者：ryanbbrown
> - 插件说明：这个插件还没经过Obsidian工作人员的人工审核。它能检测外部文件的变化，并以并排对比的方式显示差异，还能逐块选择接受或拒绝更改。
> - 插件分类：['文件管理', '编辑工具', '效率工具', 'obsidian插件']
> - 项目地址：[点我访问](https://github.com/ryanbbrown/obsidian-drift)
> - 国内下载地址：[下载安装](https://pkmer.cn/products/plugin/pluginMarket/?drift)
> - 自述文件：[Readme](https://ghproxy.net/https://raw.githubusercontent.com/ryanbbrown/obsidian-drift/master/README.md)

![Drift](https://cdn.pkmer.cn/covers/drift_internal_0.gif!pkmer)

## 概述

### 插件名称
Drift

### 主要功能
该插件是VS Code风格的并排差异查看器，能自动检测外部文件（含AI编码代理）的更改，提供文件更改前后的视图，支持逐块接受或拒绝更改、全部接受或拒绝，还可折叠未更改区域。

### 适用场景
适用于使用各种工具（如AI编码代理、同步服务、脚本、其他插件）修改Obsidian库文件的场景。

### 核心特色
1. 即时检测：利用CodeMirror 6事务监控，无轮询和延迟，实时检测外部更改。
2. 逐块操作：可逐块选择接受或拒绝更改，而非只能全选或全不选。
3. 批量操作：可对多个待处理差异文件进行全部接受或拒绝的批量操作。
4. 持久化：待处理差异在Obsidian重启后仍保留，过时差异会在重新加载时自动丢弃。
5. 编辑保护：编辑有待处理差异的文件时会弹出警告，防止数据意外丢失。

### 使用建议
安装后插件自动运行，外部工具修改库中的Markdown文件时，会在后台打开“Drift”选项卡显示并排差异，可按需选择接受或拒绝更改。若关闭选项卡，可使用“打开差异查看器”命令重新打开。


> [!help] 
> 这篇插件文章还没有人贡献，欢迎占坑！
> 如果您有好的想法欢迎提交PR或者文末留言。
> 

---


