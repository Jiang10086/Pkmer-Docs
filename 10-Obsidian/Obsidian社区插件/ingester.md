---
uid: 1780392511184001
title: 'Obsidian 插件：Ingester'
tags: ['自动化与AI', '第三方工具集成', '效率工具', '文件管理', 'obsidian插件']
description: '这个插件还没经过Obsidian官方人员的人工审核。它能监控一个文件夹，查看是否有新的网页剪藏，并且会自动触发Claude Code的/ingest指令。'
author: AI
type: auto
draft: false
editable: false
modified: 20240101000000
---

# Obsidian 插件：Ingester

> [!Note] 插件名片
> - 插件名称：Ingester
> - 插件作者：shadielfares
> - 插件说明：这个插件还没经过Obsidian官方人员的人工审核。它能监控一个文件夹，查看是否有新的网页剪藏，并且会自动触发Claude Code的/ingest指令。
> - 插件分类：['自动化与AI', '第三方工具集成', '效率工具', '文件管理', 'obsidian插件']
> - 项目地址：[点我访问](https://github.com/shadielfares/ingester)
> - 国内下载地址：[下载安装](https://pkmer.cn/products/plugin/pluginMarket/?ingester)
> - 自述文件：[Readme](https://ghproxy.net/https://raw.githubusercontent.com/shadielfares/ingester/master/README.md)



## 概述

### 主要功能
Ingester 是一款 Obsidian 插件，可监控指定文件夹，当有新的网页剪报文件出现时，自动触发 Claude Code 的 `/ingest` 技能，将文件内容处理到知识库中。

### 适用场景
适用于需要将网页内容快速整理到 Obsidian 知识库，借助 Claude Code 进行分析处理的场景。

### 核心特色
自动监测新剪报文件，自动调用 Claude Code 处理，能有效提高知识整理效率。

### 使用建议
1. 确保安装了 Claude Code CLI 并配置好环境变量，tmux 正在运行，使用 zsh  shell。
2. 按要求将相关文件复制到指定目录，并在插件设置中配置好监控文件夹。
3. 若更改监控文件夹，需同步更新 `SKILL.md` 中的路径引用。
4. 使用该插件需 Anthropic 账户和 API 访问权限，Claude Code 处理内容时会连接 Anthropic 的 API 服务器，可查看其隐私政策了解数据处理详情。


> [!help] 
> 这篇插件文章还没有人贡献，欢迎占坑！
> 如果您有好的想法欢迎提交PR或者文末留言。
> 

---


