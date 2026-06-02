---
uid: 1780392512082000
title: 'Obsidian 插件：Starred News Sync'
tags: ['第三方工具集成', '数据处理', '效率工具', 'obsidian插件']
description: '这个插件还没有经过Obsidian团队的人工审核。可以借助YAML前置元数据，把星标RSS阅读器里的条目导入为笔记。'
author: AI
type: auto
draft: false
editable: false
modified: 20240101000000
---

# Obsidian 插件：Starred News Sync

> [!Note] 插件名片
> - 插件名称：Starred News Sync
> - 插件作者：Jens Mittelbach
> - 插件说明：这个插件还没有经过Obsidian团队的人工审核。可以借助YAML前置元数据，把星标RSS阅读器里的条目导入为笔记。
> - 插件分类：['第三方工具集成', '数据处理', '效率工具', 'obsidian插件']
> - 项目地址：[点我访问](https://github.com/jmiba/starred-news-sync)
> - 国内下载地址：[下载安装](https://pkmer.cn/products/plugin/pluginMarket/?starred-news-sync)
> - 自述文件：[Readme](https://ghproxy.net/https://raw.githubusercontent.com/jmiba/starred-news-sync/master/README.md)



## 概述

### Starred News Sync插件总结
1. **主要功能**：将星标或保存的RSS阅读器条目以带有YAML元数据的Markdown笔记形式导入Obsidian。提供“立即同步星标项目”命令和侧边栏操作，支持手动和可选的间隔同步。
2. **适用场景**：适用于需要将RSS阅读器中星标内容整理到Obsidian进行知识管理的用户。
3. **核心特色**：
    - 采用安全文件名导入条目，为笔记创建包含标题、URL等信息的YAML字段。
    - 把HTML摘要/内容转换为Markdown，去除不安全元素和事件属性。
    - 可选择获取原文页面并提取可读内容，仅在启用远程图片时保留图片。
    - 支持使用Templater模板渲染导入笔记，可跳过已存在URL的条目。
4. **使用建议**：根据不同的RSS阅读器（如FreshRSS、Tiny Tiny RSS等），按对应设置说明配置API信息，如API URL、令牌等。若需自动同步，可开启间隔同步功能；若想自定义笔记格式，可使用Templater模板。


> [!help] 
> 这篇插件文章还没有人贡献，欢迎占坑！
> 如果您有好的想法欢迎提交PR或者文末留言。
> 

---


