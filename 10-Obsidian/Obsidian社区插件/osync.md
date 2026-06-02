---
uid: 1780392511665000
title: 'Obsidian 插件：Osync (Self-Hosted)'
tags: ['安全与隐私', '备份与恢复', '效率工具', '第三方工具集成', 'obsidian插件']
description: '这个插件还没经过Obsidian官方人员的人工审核。它支持自建、端到端加密的仓库同步。你可以自己搭建服务器（使用Docker）。'
author: AI
type: auto
draft: false
editable: false
modified: 20240101000000
---

# Obsidian 插件：Osync (Self-Hosted)

> [!Note] 插件名片
> - 插件名称：Osync (Self-Hosted)
> - 插件作者：Thomas Jeong
> - 插件说明：这个插件还没经过Obsidian官方人员的人工审核。它支持自建、端到端加密的仓库同步。你可以自己搭建服务器（使用Docker）。
> - 插件分类：['安全与隐私', '备份与恢复', '效率工具', '第三方工具集成', 'obsidian插件']
> - 项目地址：[点我访问](https://github.com/korthomasjeong/Osync-p)
> - 国内下载地址：[下载安装](https://pkmer.cn/products/plugin/pluginMarket/?osync)
> - 自述文件：[Readme](https://ghproxy.net/https://raw.githubusercontent.com/korthomasjeong/Osync-p/master/README.md)



## 概述

### 主要功能
Osync是一款用于Obsidian的端到端加密的保险库同步插件。支持在所有设备（包括移动设备）间同步笔记，具备实时同步、端到端加密、设备粒度控制、保险库管理等功能，还提供了一系列命令操作。

### 适用场景
适用于需要在多设备间同步Obsidian笔记，且注重数据隐私安全的用户。

### 核心特色
- **端到端加密**：采用AES - 256 - GCM加密，密码经Argon2id派生，服务器仅存储加密数据，保障数据隐私。
- **实时同步**：打开Obsidian或重新聚焦时自动同步，状态栏显示同步状态，设置中有进度条。
- **设备粒度控制**：各设备可独立设置附件同步、Obsidian配置文件夹同步，还能排除特定文件夹。
- **保险库管理**：可创建、连接、断开远程保险库，查看和恢复删除文件，有版本历史查看和冲突解决功能。

### 使用建议
可先通过命令创建或连接远程保险库，根据不同设备需求调整同步设置，定期检查同步状态，在修改密码时注意数据的重新加密。


> [!help] 
> 这篇插件文章还没有人贡献，欢迎占坑！
> 如果您有好的想法欢迎提交PR或者文末留言。
> 

---


