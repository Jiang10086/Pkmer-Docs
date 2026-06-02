---
uid: 2026060213561270
title: 'Obsidian 插件：Archivist'
tags: ['第三方工具集成', '备份与恢复', '文件管理', '效率工具', 'obsidian插件']
description: '它可以将仓库按版本备份到Dropbox，采用内容寻址存储方式，支持分层保留策略，还能进行文件级别的恢复。'
author: AI
type: auto
draft: false
editable: false
modified: 20240101000000
---

# Obsidian 插件：Archivist

> [!Note] 插件名片
> - 插件名称：Archivist
> - 插件作者：Marcus Breiden
> - 插件说明：它可以将仓库按版本备份到Dropbox，采用内容寻址存储方式，支持分层保留策略，还能进行文件级别的恢复。
> - 插件分类：['第三方工具集成', '备份与恢复', '文件管理', '效率工具', 'obsidian插件']
> - 项目地址：[点我访问](https://github.com/mmomm-org/obsidian-archivist)
> - 国内下载地址：[下载安装](https://pkmer.cn/products/plugin/pluginMarket/?archivist)
> - 自述文件：[Readme](https://ghproxy.net/https://raw.githubusercontent.com/mmomm-org/obsidian-archivist/master/README.md)

![Archivist](https://cdn.pkmer.cn/covers/archivist_internal_7.png!pkmer)

## 概述

### Archivist插件总结
1. **主要功能**：在后台运行，按用户设定的时间将Obsidian库备份到Dropbox，支持查看每个笔记的所有版本，可在“备份浏览器”或“显示当前文件历史”中恢复指定版本的文件。
2. **适用场景**：适用于已付费使用Dropbox、希望自主掌控备份（不依赖第三方服务）的Obsidian用户；追求单文件版本历史记录的高级用户；曾受同步工具困扰、需要独立可审计备份渠道的用户。
3. **核心特色**：采用内容寻址存储，相同文件自动去重；具备分层保留策略，自动调整备份频率；本地优先，令牌和索引存于库中，仅连接三个指定网络主机；提供独立恢复CLI，无依赖的Node脚本，即使插件或Obsidian出现问题，也能用`node`从Dropbox恢复文件。
4. **使用建议**：该插件处于1.0版本前，备份和恢复功能虽日常使用良好，但建议同时保留另一份独立备份（如定期压缩包）。


> [!help] 
> 这篇插件文章还没有人贡献，欢迎占坑！
> 如果您有好的想法欢迎提交PR或者文末留言。
> 

---


