---
uid: 1780392511990000
title: 'Obsidian 插件：PhantomCipher'
tags: ['安全与隐私', '数据处理', '效率工具', 'obsidian插件']
description: '这是一个基于Argon2id + AES - GCM的高性能透明全数据库加密方案。'
author: AI
type: auto
draft: false
editable: false
modified: 20240101000000
---

# Obsidian 插件：PhantomCipher

> [!Note] 插件名片
> - 插件名称：PhantomCipher
> - 插件作者：Lumingtianze
> - 插件说明：这是一个基于Argon2id + AES - GCM的高性能透明全数据库加密方案。
> - 插件分类：['安全与隐私', '数据处理', '效率工具', 'obsidian插件']
> - 项目地址：[点我访问](https://github.com/lumingtianze/obsidian-phantom-cipher)
> - 国内下载地址：[下载安装](https://pkmer.cn/products/plugin/pluginMarket/?phantom-cipher)
> - 自述文件：[Readme](https://ghproxy.net/https://raw.githubusercontent.com/lumingtianze/obsidian-phantom-cipher/master/README.md)



## 概述

### PhantomCipher插件总结
1. **主要功能**：为Obsidian库提供无缝透明的加密体验，采用Argon2id + AES - GCM加密方案。支持信封加密（V2），能用KEK包装DEK，可在不重新加密物理文件的情况下更改密码；内置压缩，支持大附件，有原生二进制格式，还能进行完整性验证。
2. **适用场景**：适用于对Obsidian库中普通文件进行加密保护，但不适用于高安全性要求的机密或核心业务数据。
3. **核心特色**：透明工作流，在编辑器正常写入，文件在磁盘以加密形式存储；采用Deflate压缩，抵消Base64编码带来的体积增加；支持纯二进制存储加密负载，提升媒体文件性能。
4. **使用建议**：该项目处于早期阶段，加密架构可能随时改变，需常查看更新日志；加密重要文件前要备份整个库；手动保存/备份KEK和DEK，多设备使用时要手动同步凭证；遗忘密码会导致永久数据丢失。对于大文件，建议使用16GB以上内存的设备。


> [!help] 
> 这篇插件文章还没有人贡献，欢迎占坑！
> 如果您有好的想法欢迎提交PR或者文末留言。
> 

---


