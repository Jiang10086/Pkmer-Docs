---
uid: 2026060213561401
title: 'Obsidian 插件：Plaud Sync'
tags: ['多媒体', '自动化与AI', '第三方工具集成', '效率工具', 'obsidian插件']
description: '它能把Plaud语音记录同步到Markdown笔记里，还带有文字转录、AI总结和重点标记功能。'
author: AI
type: auto
draft: false
editable: false
modified: 20240101000000
---

# Obsidian 插件：Plaud Sync

> [!Note] 插件名片
> - 插件名称：Plaud Sync
> - 插件作者：Léonard Sellem
> - 插件说明：它能把Plaud语音记录同步到Markdown笔记里，还带有文字转录、AI总结和重点标记功能。
> - 插件分类：['多媒体', '自动化与AI', '第三方工具集成', '效率工具', 'obsidian插件']
> - 项目地址：[点我访问](https://github.com/leonardsellem/plaud-sync-for-obsidian)
> - 国内下载地址：[下载安装](https://pkmer.cn/products/plugin/pluginMarket/?plaud-sync)
> - 自述文件：[Readme](https://ghproxy.net/https://raw.githubusercontent.com/leonardsellem/plaud-sync-for-obsidian/master/README.md)



## 概述

### Plaud Sync插件总结
1. **主要功能**：将Plaud语音录制内容同步到Obsidian库中的Markdown笔记，包含转录文本、AI总结、重点内容和元数据。
2. **适用场景**：适用于有Plaud账户且有语音录制内容，希望将其整理成Markdown笔记的Obsidian用户。
3. **核心特色**
    - 增量同步，只获取上次同步后新增的录音，避免重复。
    - 生成丰富的Markdown笔记，展示标题、日期等信息。
    - 幂等更新，利用稳定的`file_id`更新现有笔记。
    - 安全存储Plaud会话令牌。
    - 自动重试失败请求，过滤已删除录音，获取完整转录和AI总结内容。
4. **使用建议**
    - 需Obsidian 0.15.0及以上版本和Plaud账户。
    - 手动安装插件，按步骤操作并重启Obsidian启用。
    - 注意这是个非官方插件，Plaud无公开API，使用逆向工程API，可能因Plaud后端变更而失效，使用需谨慎。


> [!help] 
> 这篇插件文章还没有人贡献，欢迎占坑！
> 如果您有好的想法欢迎提交PR或者文末留言。
> 

---


