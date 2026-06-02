---
uid: 2026060213561479
title: 'Obsidian 插件：Remote Vault Sync'
tags: ['第三方工具集成', '备份与恢复', '效率工具', 'obsidian插件']
description: '这个插件还没经过Obsidian官方人员的人工审核。你可以用基于Git的版本控制功能，把你的仓库备份并同步到S3。'
author: AI
type: auto
draft: false
editable: false
modified: 20240101000000
---

# Obsidian 插件：Remote Vault Sync

> [!Note] 插件名片
> - 插件名称：Remote Vault Sync
> - 插件作者：suneater-labs
> - 插件说明：这个插件还没经过Obsidian官方人员的人工审核。你可以用基于Git的版本控制功能，把你的仓库备份并同步到S3。
> - 插件分类：['第三方工具集成', '备份与恢复', '效率工具', 'obsidian插件']
> - 项目地址：[点我访问](https://github.com/suneater-labs/remote-vault-sync)
> - 国内下载地址：[下载安装](https://pkmer.cn/products/plugin/pluginMarket/?remote-vault-sync)
> - 自述文件：[Readme](https://ghproxy.net/https://raw.githubusercontent.com/suneater-labs/remote-vault-sync/master/README.md)



## 概述

### 主要功能
Remote Vault Sync 插件可借助基于 Git 的版本控制，将 Obsidian 保险库备份并同步到 S3。

### 适用场景
适用于需要对 Obsidian 笔记进行云端备份和多设备同步，且希望利用版本控制管理笔记历史的用户。

### 核心特色
1. 利用原生 Git 进行版本控制，通过 `child_process` 操作，`.git` 目录可直接与 S3 复制。
2. 支持使用 LFS 在 S3 存储大文件。
3. 具备丰富的可视化界面，如文件徽章与通知、查看变更差异、合并冲突解决、状态栏同步指示、查看提交变更等。

### 使用建议
使用前需确保系统已安装 `git` 和 `git-lfs`。用户可通过命令面板执行相关操作，还能在设置选项卡中进行默认设置。借助界面上的功能按钮，如状态栏组件、功能区图标等，能方便地完成推送、拉取、恢复等操作。


> [!help] 
> 这篇插件文章还没有人贡献，欢迎占坑！
> 如果您有好的想法欢迎提交PR或者文末留言。
> 

---


