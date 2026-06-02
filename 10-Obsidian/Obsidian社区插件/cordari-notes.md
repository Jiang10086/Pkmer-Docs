---
uid: 2026060213561321
title: 'Obsidian 插件：Cordari'
tags: ['第三方工具集成', '多媒体', '效率工具', 'obsidian插件']
description: '这个插件还没经过Obsidian官方人员的人工审核哦。可以把你的Cordari语音记录摘要、文字记录和音频同步到你的仓库里。'
author: AI
type: auto
draft: false
editable: false
modified: 20240101000000
---

# Obsidian 插件：Cordari

> [!Note] 插件名片
> - 插件名称：Cordari
> - 插件作者：rsteckler
> - 插件说明：这个插件还没经过Obsidian官方人员的人工审核哦。可以把你的Cordari语音记录摘要、文字记录和音频同步到你的仓库里。
> - 插件分类：['第三方工具集成', '多媒体', '效率工具', 'obsidian插件']
> - 项目地址：[点我访问](https://github.com/rsteckler/cordari-obsidian)
> - 国内下载地址：[下载安装](https://pkmer.cn/products/plugin/pluginMarket/?cordari-notes)
> - 自述文件：[Readme](https://ghproxy.net/https://raw.githubusercontent.com/rsteckler/cordari-obsidian/master/README.md)



## 概述

### Cordari插件总结
1. **主要功能**：将Cordari的语音记录、手写笔记同步到Obsidian库中，以Markdown文件形式呈现。每次同步会为每个录音创建一个带有YAML元数据的Markdown文件，同时保存音频文件；为每个手写笔记创建一个包含识别出的Markdown、AI摘要及回链的文件。
2. **适用场景**：适用于使用Cordari进行语音记录和手写笔记，且希望将这些内容整合到Obsidian进行管理的用户。
3. **核心特色**：持续协调同步，Cordari端的重命名会同步到文件，后续的转录、摘要和识别更新会直接更新文件，库中删除的内容下次同步会重新写入；仅发送读取请求，不会将库中内容推回Cordari。
4. **使用建议**：需Cordari Pro账户和Obsidian 1.4.0+桌面版。安装时在Obsidian社区插件中搜索“Cordari”安装并启用，然后在插件设置中连接Cordari账户。开发时可本地构建。


> [!help] 
> 这篇插件文章还没有人贡献，欢迎占坑！
> 如果您有好的想法欢迎提交PR或者文末留言。
> 

---


