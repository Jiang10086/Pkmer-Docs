---
uid: 1780392511302002
title: 'Obsidian 插件：NeoGDSync'
tags: ['第三方工具集成', '文件管理', '备份与恢复', '效率工具', 'obsidian插件']
description: '这个插件还没经过Obsidian官方人员的人工审核。它能实现轻量级的谷歌云端硬盘同步，具备基于路径的索引、冲突检测功能，还有智能、推送、拉取三种模式。'
author: AI
type: auto
draft: false
editable: false
modified: 20240101000000
---

# Obsidian 插件：NeoGDSync

> [!Note] 插件名片
> - 插件名称：NeoGDSync
> - 插件作者：martinlegend
> - 插件说明：这个插件还没经过Obsidian官方人员的人工审核。它能实现轻量级的谷歌云端硬盘同步，具备基于路径的索引、冲突检测功能，还有智能、推送、拉取三种模式。
> - 插件分类：['第三方工具集成', '文件管理', '备份与恢复', '效率工具', 'obsidian插件']
> - 项目地址：[点我访问](https://github.com/martinlegend/neogdsync)
> - 国内下载地址：[下载安装](https://pkmer.cn/products/plugin/pluginMarket/?neogdsync)
> - 自述文件：[Readme](https://ghproxy.net/https://raw.githubusercontent.com/martinlegend/neogdsync/master/README.md)



## 概述

### NeoGDSync插件总结
1. **主要功能**：该插件可实现Obsidian与Google Drive的轻量级同步，具备智能同步、强制推送（本地到云端）、强制拉取（云端到本地）功能，能检测冲突并保存冲突文件，支持路径索引、版本历史记录，可配置排除文件或文件夹，还有URI处理程序用于自动化。
2. **适用场景**：适合需要将Obsidian笔记同步到Google Drive的用户，方便在不同设备间访问和编辑笔记。
3. **核心特色**：采用路径索引，首次同步后无需全量扫描，速度快；智能同步可自动检测冲突，只同步有变化的文件；冲突处理不会静默覆盖；可设置版本历史和排除规则。
4. **使用建议**：安装插件后，在设置中输入Google OAuth2刷新令牌和Google Drive库根文件夹ID。获取刷新令牌可通过Google Drive for Desktop或其他OAuth2工具。可通过点击丝带图标或运行命令进行同步，也可使用URI从外部触发同步。


> [!help] 
> 这篇插件文章还没有人贡献，欢迎占坑！
> 如果您有好的想法欢迎提交PR或者文末留言。
> 

---


