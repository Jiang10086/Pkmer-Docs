---
uid: 1780392512178000
title: 'Obsidian 插件：Vault Bridge SFTP'
tags: ['文件管理', '第三方工具集成', '备份与恢复', '效率工具', 'obsidian插件']
description: '这个插件还没经过Obsidian官方人员的人工审核哦。你可以通过自己的SSH/SFTP服务器，在不同设备间实现仓库的对接。它能进行双向同步，还能解决冲突问题，保障多设备使用安全，而且完全支持自建服务呢。'
author: AI
type: auto
draft: false
editable: false
modified: 20240101000000
---

# Obsidian 插件：Vault Bridge SFTP

> [!Note] 插件名片
> - 插件名称：Vault Bridge SFTP
> - 插件作者：andrewkopylev
> - 插件说明：这个插件还没经过Obsidian官方人员的人工审核哦。你可以通过自己的SSH/SFTP服务器，在不同设备间实现仓库的对接。它能进行双向同步，还能解决冲突问题，保障多设备使用安全，而且完全支持自建服务呢。
> - 插件分类：['文件管理', '第三方工具集成', '备份与恢复', '效率工具', 'obsidian插件']
> - 项目地址：[点我访问](https://github.com/andrewkopylev/vaultbridge)
> - 国内下载地址：[下载安装](https://pkmer.cn/products/plugin/pluginMarket/?vault-bridge-sftp)
> - 自述文件：[Readme](https://ghproxy.net/https://raw.githubusercontent.com/andrewkopylev/vaultbridge/master/README.md)



## 概述

### 主要功能
Vault Bridge SFTP 是一款用于 Obsidian 的插件，借助 SSH/SFTP 服务器实现笔记库在多台桌面设备间的双向同步。它运用 3 向差异比较，能处理文件冲突，保留两个版本，还具备服务器重置检测、自我修复等功能。

### 适用场景
适合希望通过自己的 SSH/SFTP 服务器在桌面设备间同步 Obsidian 笔记库，且不想依赖云服务、代理服务或支付订阅费用的用户。

### 核心特色
- 双向同步，采用 3 向差异比较，一次操作完成拉取和推送。
- 冲突处理时保留两个版本，以修改时间决定主版本。
- 多设备安全，有服务器端锁和清单生成计数器。
- 节省带宽，通过 SHA - 1 检测文件变化。
- 具备批量删除保护、服务器重置检测和自我修复功能。
- 可设置自动同步触发条件。
- 采用原子传输，避免同步中断导致文件损坏。

### 使用建议
根据自身需求开启自动同步功能，在进行批量删除操作时谨慎选择继续、跳过或取消，确保数据安全。


> [!help] 
> 这篇插件文章还没有人贡献，欢迎占坑！
> 如果您有好的想法欢迎提交PR或者文末留言。
> 

---


