---
uid: 1780392511017001
title: 'Obsidian 插件：Claude Skill Sync'
tags: ['第三方工具集成', '编程与脚本', '自动化与AI', '效率工具', '文件管理', 'obsidian插件']
description: '这个插件还没经过Obsidian官方人员的人工审核。它能把AI编码工具（Claude Code、Codex、Cursor、Gemini等14种以上）的技能集中到一个文件夹里，和每个工具的本地目录建立符号链接。支持双向同步，有状态仪表盘，还有18种以上预设。'
author: AI
type: auto
draft: false
editable: false
modified: 20240101000000
---

# Obsidian 插件：Claude Skill Sync

> [!Note] 插件名片
> - 插件名称：Claude Skill Sync
> - 插件作者：2949984428
> - 插件说明：这个插件还没经过Obsidian官方人员的人工审核。它能把AI编码工具（Claude Code、Codex、Cursor、Gemini等14种以上）的技能集中到一个文件夹里，和每个工具的本地目录建立符号链接。支持双向同步，有状态仪表盘，还有18种以上预设。
> - 插件分类：['第三方工具集成', '编程与脚本', '自动化与AI', '效率工具', '文件管理', 'obsidian插件']
> - 项目地址：[点我访问](https://github.com/2949984428/claude-skill-sync)
> - 国内下载地址：[下载安装](https://pkmer.cn/products/plugin/pluginMarket/?claude-skill-sync)
> - 自述文件：[Readme](https://ghproxy.net/https://raw.githubusercontent.com/2949984428/claude-skill-sync/master/README.md)



## 概述

### 主要功能
将 Obsidian vault 作为 AI agent skill 中央仓库，可一键将技能文件软链接到 Claude Code、Codex 等工具的技能目录，具备双向同步、侧边栏状态卡展示、失效链接清理、指向错误修复、定时自动同步及启动状态提醒等功能。

### 适用场景
适用于使用多种 AI 编码工具，需要集中管理和同步技能文件的开发者，可在不同电脑上保持技能文件的一致性。

### 核心特色
采用“单一真身（vault），多处替身（symlink）”理念，不复制内容、不占额外空间，任何位置编辑都即时一致；支持多平台，可利用 Obsidian 自身同步方案实现跨电脑同步。

### 使用建议
推荐开发者本地安装，先克隆仓库，再在 Obsidian vault 里建立软链接；启用插件后，在设置中确认技能根目录和目标平台，将技能文件放入指定目录，点击“全部安装”即可；注意 `data.json` 不参与跨机同步。移动端暂不支持。


> [!help] 
> 这篇插件文章还没有人贡献，欢迎占坑！
> 如果您有好的想法欢迎提交PR或者文末留言。
> 

---


