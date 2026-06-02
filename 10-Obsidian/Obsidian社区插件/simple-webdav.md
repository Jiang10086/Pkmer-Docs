---
uid: 1780392512053000
title: 'Obsidian 插件：Simple WebDAV Sync'
tags: ['文件管理', '第三方工具集成', '备份与恢复', '效率工具', 'obsidian插件']
description: '这个插件还没经过Obsidian官方人员的人工审核。这是一款轻量级的WebDAV同步插件，采用ETag + SHA - 256三方对比机制。零依赖，支持双语（英文/中文）。'
author: AI
type: auto
draft: false
editable: false
modified: 20240101000000
---

# Obsidian 插件：Simple WebDAV Sync

> [!Note] 插件名片
> - 插件名称：Simple WebDAV Sync
> - 插件作者：gghyoo
> - 插件说明：这个插件还没经过Obsidian官方人员的人工审核。这是一款轻量级的WebDAV同步插件，采用ETag + SHA - 256三方对比机制。零依赖，支持双语（英文/中文）。
> - 插件分类：['文件管理', '第三方工具集成', '备份与恢复', '效率工具', 'obsidian插件']
> - 项目地址：[点我访问](https://github.com/gghyoo/simple-webdav)
> - 国内下载地址：[下载安装](https://pkmer.cn/products/plugin/pluginMarket/?simple-webdav)
> - 自述文件：[Readme](https://ghproxy.net/https://raw.githubusercontent.com/gghyoo/simple-webdav/master/README.md)



## 概述

### 插件名称
Simple WebDAV Sync

### 主要功能
实现Obsidian笔记库与WebDAV服务器的双向同步，支持实时、自动同步，处理文件的新增、删除、修改和重命名，具备冲突处理和安全删除机制。

### 适用场景
适用于需要在多设备间同步Obsidian笔记，且使用WebDAV服务存储笔记的用户。

### 核心特色
1. 采用ETag + SHA - 256三方比较，不依赖时间戳，不受服务器时间漂移影响。
2. 双向同步，冲突时保留双方版本。
3. 安全删除，本地删除可恢复，远程删除文件移至本地回收站。
4. 支持实时和自动同步，关闭Obsidian时触发全量同步。
5. 操作后持久化同步状态，保障崩溃安全。
6. 支持中英双语，自动检测系统语言。

### 使用建议
可从Obsidian社区插件中搜索安装，也可手动下载文件安装。设置时需填写服务器URL、用户名和密码，可按需配置自动同步间隔、防抖延迟等参数。


> [!help] 
> 这篇插件文章还没有人贡献，欢迎占坑！
> 如果您有好的想法欢迎提交PR或者文末留言。
> 

---


