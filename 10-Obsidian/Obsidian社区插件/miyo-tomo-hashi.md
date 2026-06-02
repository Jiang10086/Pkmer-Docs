---
uid: 1780392511283001
title: 'Obsidian 插件：MiYo Tomo Hashi'
tags: ['第三方工具集成', '自动化与AI', '效率工具', 'obsidian插件']
description: '它可以与Claude代码代理Tomo直接集成，用于会话交互和自动更新仓库。'
author: AI
type: auto
draft: false
editable: false
modified: 20240101000000
---

# Obsidian 插件：MiYo Tomo Hashi

> [!Note] 插件名片
> - 插件名称：MiYo Tomo Hashi
> - 插件作者：Marcus Breiden
> - 插件说明：它可以与Claude代码代理Tomo直接集成，用于会话交互和自动更新仓库。
> - 插件分类：['第三方工具集成', '自动化与AI', '效率工具', 'obsidian插件']
> - 项目地址：[点我访问](https://github.com/mmomm-org/miyo-tomo-hashi)
> - 国内下载地址：[下载安装](https://pkmer.cn/products/plugin/pluginMarket/?miyo-tomo-hashi)
> - 自述文件：[Readme](https://ghproxy.net/https://raw.githubusercontent.com/mmomm-org/miyo-tomo-hashi/master/README.md)

![MiYo Tomo Hashi](https://cdn.pkmer.cn/covers/miyo-tomo-hashi_html_1.png!pkmer)

## 概述

### 主要功能
- 提供与运行中的Tomo Docker容器的实时聊天功能，可在Obsidian内与Claude Code交流。
- 执行Tomo生成的`_instructions.json`文件，对Obsidian库进行批量编辑，有预览、运行日志，支持幂等重运行。
- 提供Tomo上下文，通过本地WebSocket为Claude Code提供实时编辑器上下文（活动文件、光标位置和当前选择），默认禁用，可选择开启。

### 适用场景
适用于使用Tomo进行收件箱处理或日常笔记总结的用户，将Tomo的审查输出转化为一键操作。

### 核心特色
- 本地应用且有预览，在查看操作列表后再进行库更改，自动运行模式也会先展示预览。
- 重运行安全，每个操作有幂等性探测，记录已应用操作，可从断点继续。

### 使用建议
若已使用Tomo，可开启此插件，将其审查输出快速应用到Obsidian库中，使用时注意可按需开启Tomo上下文功能。


> [!help] 
> 这篇插件文章还没有人贡献，欢迎占坑！
> 如果您有好的想法欢迎提交PR或者文末留言。
> 

---


