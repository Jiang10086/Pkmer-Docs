---
uid: 1780392512051000
title: 'Obsidian 插件：S3 Sync + Backup'
tags: ['第三方工具集成', '备份与恢复', '安全与隐私', '效率工具', 'obsidian插件']
description: '这个插件还没经过Obsidian官方人员的人工审核哈。它能借助兼容S3的存储服务（像AWS S3、Cloudflare R2、RustFS这些），实现仓库在不同设备间的同步和定期备份，还能选择开启端到端加密呢。'
author: AI
type: auto
draft: false
editable: false
modified: 20240101000000
---

# Obsidian 插件：S3 Sync + Backup

> [!Note] 插件名片
> - 插件名称：S3 Sync + Backup
> - 插件作者：ceilaolabs
> - 插件说明：这个插件还没经过Obsidian官方人员的人工审核哈。它能借助兼容S3的存储服务（像AWS S3、Cloudflare R2、RustFS这些），实现仓库在不同设备间的同步和定期备份，还能选择开启端到端加密呢。
> - 插件分类：['第三方工具集成', '备份与恢复', '安全与隐私', '效率工具', 'obsidian插件']
> - 项目地址：[点我访问](https://github.com/ceilaolabs/obsidian-s3-sync-and-backup)
> - 国内下载地址：[下载安装](https://pkmer.cn/products/plugin/pluginMarket/?simple-storage-sync-and-backup)
> - 自述文件：[Readme](https://ghproxy.net/https://raw.githubusercontent.com/ceilaolabs/obsidian-s3-sync-and-backup/master/README.md)



## 概述

### 《S3 Sync + Backup》插件总结
1. **主要功能**：借助S3兼容存储（如AWS S3、Cloudflare R2等）实现Obsidian库的设备间双向同步与定时备份，支持端到端加密。
2. **适用场景**：适用于多设备使用Obsidian的用户，需要对笔记库进行同步和备份，保障数据在不同设备间的一致性和安全性。
3. **核心特色**：
    - 双向同步采用三向协调，通过本地IndexedDB存储的文件SHA - 256基线精准检测变化。
    - 支持多种S3兼容存储。
    - 可选端到端加密，加密同步文件和备份快照，可记住密码自动解锁。
    - 可配置定时备份，能从设置中下载备份ZIP文件。
    - 智能冲突解决，避免数据丢失。
    - 状态栏实时显示同步和备份状态。
    - 可灵活清理旧备份。
4. **使用建议**：初次使用时，根据自身需求配置好存储服务、加密密码、备份间隔等设置。遇到文件冲突时，可通过 `LOCAL_` 和 `REMOTE_` 副本恢复数据。定期检查备份和同步状态，确保数据安全。


> [!help] 
> 这篇插件文章还没有人贡献，欢迎占坑！
> 如果您有好的想法欢迎提交PR或者文末留言。
> 

---


