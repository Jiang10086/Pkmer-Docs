---
uid: 1780392512191001
title: 'Obsidian 插件：VaultCrypt'
tags: ['安全与隐私', '第三方工具集成', '编辑工具', '效率工具', 'obsidian插件']
description: '它能使用与KeePass兼容的（.kdbx）存储方式，对笔记中的敏感字段进行内联加密。'
author: AI
type: auto
draft: false
editable: false
modified: 20240101000000
---

# Obsidian 插件：VaultCrypt

> [!Note] 插件名片
> - 插件名称：VaultCrypt
> - 插件作者：romejoe
> - 插件说明：它能使用与KeePass兼容的（.kdbx）存储方式，对笔记中的敏感字段进行内联加密。
> - 插件分类：['安全与隐私', '第三方工具集成', '编辑工具', '效率工具', 'obsidian插件']
> - 项目地址：[点我访问](https://github.com/romejoe/VaultCrypt)
> - 国内下载地址：[下载安装](https://pkmer.cn/products/plugin/pluginMarket/?vaultcrypt)
> - 自述文件：[Readme](https://ghproxy.net/https://raw.githubusercontent.com/romejoe/VaultCrypt/master/README.md)



## 概述

### 1. 主要功能
VaultCrypt是一款用于Obsidian的插件，可利用与KeePass兼容的 `.kdbx` 存储对笔记中的敏感字段进行内联加密。支持在笔记中用 `{{vc:...}}` 引用机密信息，以交互式“芯片”形式呈现，默认掩码显示，防止明文暴露。

### 2. 适用场景
适用于需要在笔记中存储和引用敏感信息，如密码、用户名等，且希望对这些信息进行加密保护的场景。

### 3. 核心特色
- 支持将机密信息存储在KeePass v3/v4（`.kdbx`）数据库中。
- 支持桌面和移动设备。
- 可设置自动锁定计时器，保障信息安全。
- 提供可选的主密钥环来存储配置文件密码。
- 使用Argon2id KDF（KDBX v4）进行强密钥推导。

### 4. 使用建议
- 通过社区插件搜索“VaultCrypt”安装，或手动下载文件安装。
- 在设置中创建指向 `.kdbx` 文件的配置文件并解锁。
- 利用插件编辑器命令添加条目。
- 在笔记中插入 `{{vc:...}}` 引用机密信息，点击“芯片”可复制值，且剪贴板会在配置的超时时间后自动清除。


> [!help] 
> 这篇插件文章还没有人贡献，欢迎占坑！
> 如果您有好的想法欢迎提交PR或者文末留言。
> 

---


