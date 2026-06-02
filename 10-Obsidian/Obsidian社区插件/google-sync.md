---
uid: 1780392511137002
title: 'Obsidian 插件：Google Calendar and Tasks Sync'
tags: ['第三方工具集成', '任务管理', '日历与时间', '效率工具', 'obsidian插件']
description: '这个插件还没经过Obsidian官方人员的人工审核。它能把你仓库里的日程和任务文件夹同步到谷歌日历和谷歌任务里。'
author: AI
type: auto
draft: false
editable: false
modified: 20240101000000
---

# Obsidian 插件：Google Calendar and Tasks Sync

> [!Note] 插件名片
> - 插件名称：Google Calendar and Tasks Sync
> - 插件作者：Connor
> - 插件说明：这个插件还没经过Obsidian官方人员的人工审核。它能把你仓库里的日程和任务文件夹同步到谷歌日历和谷歌任务里。
> - 插件分类：['第三方工具集成', '任务管理', '日历与时间', '效率工具', 'obsidian插件']
> - 项目地址：[点我访问](https://github.com/cordedmink2/obsidian-google-sync)
> - 国内下载地址：[下载安装](https://pkmer.cn/products/plugin/pluginMarket/?google-sync)
> - 自述文件：[Readme](https://ghproxy.net/https://raw.githubusercontent.com/cordedmink2/obsidian-google-sync/master/README.md)



## 概述

### 插件名称
Google Calendar and Tasks Sync

### 主要功能
将Obsidian笔记中的`events/`文件夹内笔记同步为Google日历事件，`tasks/`文件夹内笔记同步为Google任务，支持双向同步，可导入Google的事件和任务，还能将过去的事件和旧任务整理到存档、过期或已完成文件夹。

### 适用场景
适合喜欢用Markdown进行规划，又希望在Google服务覆盖的所有地方都能访问日历和任务列表的用户。

### 核心特色
- 同步模式保守，避免破坏本地编辑。Obsidian到Google自动同步（需开启对应设置），Google到Obsidian手动导入或可选启动时导入（默认不覆盖已有笔记）。
- 导入设置可控制导入范围，避免笔记过多。

### 使用建议
- 若需全双向合并工作流，先在备用日历/列表上仔细测试。
- 导入时按需调整导入窗口的天数范围。
- 若想让导入的笔记修改后推回Google，删除`syncDirection: pull-only`字段或设为`two-way`。


> [!help] 
> 这篇插件文章还没有人贡献，欢迎占坑！
> 如果您有好的想法欢迎提交PR或者文末留言。
> 

---


