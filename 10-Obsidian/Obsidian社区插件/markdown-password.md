---
uid: 1780392511258001
title: 'Obsidian 插件：Markdown Password'
tags: ['安全与隐私', '编辑工具', '效率工具', 'obsidian插件']
description: '这个插件还没有经过Obsidian工作人员的人工审核。你可以用标准的 [|仓库:ID|] 占位符和本地AES - 256 - GCM加密技术，在笔记里安全地管理机密信息。'
author: AI
type: auto
draft: false
editable: false
modified: 20240101000000
---

# Obsidian 插件：Markdown Password

> [!Note] 插件名片
> - 插件名称：Markdown Password
> - 插件作者：hoyin258
> - 插件说明：这个插件还没有经过Obsidian工作人员的人工审核。你可以用标准的 [|仓库:ID|] 占位符和本地AES - 256 - GCM加密技术，在笔记里安全地管理机密信息。
> - 插件分类：['安全与隐私', '编辑工具', '效率工具', 'obsidian插件']
> - 项目地址：[点我访问](https://github.com/hoyin258/markdown-password)
> - 国内下载地址：[下载安装](https://pkmer.cn/products/plugin/pluginMarket/?markdown-password)
> - 自述文件：[Readme](https://ghproxy.net/https://raw.githubusercontent.com/hoyin258/markdown-password/master/README.md)

![Markdown Password](https://cdn.pkmer.cn/covers/markdown-password_internal_0.gif!pkmer)

## 概述

### Markdown Password插件总结
1. **主要功能**：在Markdown文件中安全管理机密信息，使用`[|vault:id|]`占位符和本地AES - 256 - GCM加密，将加密的机密直接嵌入文件。
2. **适用场景**：适用于需要在笔记中存储敏感信息，又担心信息被云服务、AI模型或搜索索引器获取的场景。
3. **核心特色**：一是零持久化模型，主密钥和解密后的库密钥仅存在于内存，不写入磁盘；二是自动加密，输入`[|your - secret|]`自动转换为`[|vault:id|]`；三是无缝集成，在编辑和阅读模式都可用，授权后显示真实机密；四是解耦存储，机密存于`vault.json`，与主库内容分离。
4. **使用建议**：首次使用需设置主密钥，且无密码恢复功能，丢失主密钥将无法解密机密。在编辑器中输入`[|my - secret - password|]`即可创建/加密机密。


> [!help] 
> 这篇插件文章还没有人贡献，欢迎占坑！
> 如果您有好的想法欢迎提交PR或者文末留言。
> 

---


