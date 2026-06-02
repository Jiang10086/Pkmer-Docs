---
uid: 1780392512182000
title: 'Obsidian 插件：Vault Encryptor'
tags: ['文件管理', '安全与隐私', '编辑工具', '效率工具', 'obsidian插件']
description: '可以对文件和文件夹进行手动右键加密/解密操作，加密后的 .enc 文件无法编辑。'
author: AI
type: auto
draft: false
editable: false
modified: 20240101000000
---

# Obsidian 插件：Vault Encryptor

> [!Note] 插件名片
> - 插件名称：Vault Encryptor
> - 插件作者：curiousabe
> - 插件说明：可以对文件和文件夹进行手动右键加密/解密操作，加密后的 .enc 文件无法编辑。
> - 插件分类：['文件管理', '安全与隐私', '编辑工具', '效率工具', 'obsidian插件']
> - 项目地址：[点我访问](https://github.com/curiousabe/obsidian-vault-encryptor)
> - 国内下载地址：[下载安装](https://pkmer.cn/products/plugin/pluginMarket/?vault-encryptor)
> - 自述文件：[Readme](https://ghproxy.net/https://raw.githubusercontent.com/curiousabe/obsidian-vault-encryptor/master/README.md)



## 概述

### 主要功能
Vault Encryptor 是 Obsidian 的手动加密插件，可通过命令面板或文件树右键对文件和文件夹进行加密和解密操作，支持递归加密/解密文件夹。加密后的文件扩展名为 `.enc`，且不能直接编辑。

### 适用场景
适用于需要对 Obsidian 中的敏感文件或文件夹进行加密保护，防止他人未经授权访问的场景。

### 核心特色
- 采用 AES - 256 - GCM + PBKDF2 - SHA256 加密算法，迭代次数固定为 210000，安全性较高。
- 纯手工、保守策略，避免自动操作带来的风险。
- 不覆盖输出，若目标文件已存在会提示手动处理冲突。

### 使用建议
- 使用前备份重要文件，以防加密或解密过程中出现意外。
- 牢记加密密码，避免因密码遗忘导致无法解密文件。
- 遇到文件冲突时，按提示手动处理，确保数据安全。


> [!help] 
> 这篇插件文章还没有人贡献，欢迎占坑！
> 如果您有好的想法欢迎提交PR或者文末留言。
> 

---


