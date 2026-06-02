---
uid: 1780392512000002
title: 'Obsidian 插件：Rollover Daily Todos Helper'
tags: ['任务管理', '自动化与AI', '效率工具', '移动端优化', 'obsidian插件']
description: '它是Rollover Daily Todos的非官方配套插件。启动后会延迟一段时间再打开今天的每日笔记，这样一来，延期工作流在桌面端和移动端都能稳定运行。'
author: AI
type: auto
draft: false
editable: false
modified: 20240101000000
---

# Obsidian 插件：Rollover Daily Todos Helper

> [!Note] 插件名片
> - 插件名称：Rollover Daily Todos Helper
> - 插件作者：eugenschmalz
> - 插件说明：它是Rollover Daily Todos的非官方配套插件。启动后会延迟一段时间再打开今天的每日笔记，这样一来，延期工作流在桌面端和移动端都能稳定运行。
> - 插件分类：['任务管理', '自动化与AI', '效率工具', '移动端优化', 'obsidian插件']
> - 项目地址：[点我访问](https://github.com/eugenschmalz/obsidian-rollover-daily-todos-helper)
> - 国内下载地址：[下载安装](https://pkmer.cn/products/plugin/pluginMarket/?rollover-daily-todos-helper)
> - 自述文件：[Readme](https://ghproxy.net/https://raw.githubusercontent.com/eugenschmalz/obsidian-rollover-daily-todos-helper/master/README.md)

![Rollover Daily Todos Helper](https://cdn.pkmer.cn/covers/rollover-daily-todos-helper_internal_0.png!pkmer)

## 概述

### 插件名称
Rollover Daily Todos Helper

### 主要功能
作为 [Rollover Daily Todos](https://github.com/lumoe/obsidian-rollover-daily-todos) 的非官方辅助插件，可在设置的启动延迟后打开今日日记，确保 `Rollover Daily Todos` 能可靠捕获笔记创建事件。

### 适用场景
适用于在启动时过早创建今日笔记，导致监听文件创建事件的插件错过该事件的情况，尤其在 Android 搭配同步库的设置中。

### 核心特色
- 启动延迟时间可在 0 - 120 秒内配置。
- 支持桌面和移动设备。
- 执行打开日记命令，可通过前缀进行命令回退解析。
- 可选择若今日笔记已打开则跳过。
- 可设置第二个命令。
- 有手动命令和“立即运行”设置按钮。

### 使用建议
- 启用 **Daily Notes** 核心插件。
- 在 Obsidian 应用行为中，启动时打开上一个文件，而非自动打开日记。
- 设置 5 - 10 秒的延迟。
- 除非使用自定义命令，否则保持 `commandId = daily-notes`。


> [!help] 
> 这篇插件文章还没有人贡献，欢迎占坑！
> 如果您有好的想法欢迎提交PR或者文末留言。
> 

---


