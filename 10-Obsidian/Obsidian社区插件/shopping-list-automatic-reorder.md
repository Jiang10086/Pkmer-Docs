---
uid: 1780392512035001
title: 'Obsidian 插件：Automatic Shopping List Reorder'
tags: ['搜索与排序', '任务管理', '自动化与AI', '效率工具', 'obsidian插件']
description: '这个插件还没经过Obsidian官方人员的人工审核。它能自动把已购物品移到对应板块的底部。'
author: AI
type: auto
draft: false
editable: false
modified: 20240101000000
---

# Obsidian 插件：Automatic Shopping List Reorder

> [!Note] 插件名片
> - 插件名称：Automatic Shopping List Reorder
> - 插件作者：Nikolay Sokolov
> - 插件说明：这个插件还没经过Obsidian官方人员的人工审核。它能自动把已购物品移到对应板块的底部。
> - 插件分类：['搜索与排序', '任务管理', '自动化与AI', '效率工具', 'obsidian插件']
> - 项目地址：[点我访问](https://github.com/joysimple/shopping-list-automatic-reorder)
> - 国内下载地址：[下载安装](https://pkmer.cn/products/plugin/pluginMarket/?shopping-list-automatic-reorder)
> - 自述文件：[Readme](https://ghproxy.net/https://raw.githubusercontent.com/joysimple/shopping-list-automatic-reorder/master/README.md)



## 概述

### 自动购物清单排序插件总结
1. **主要功能**：该Obsidian插件可在勾选购物清单项目时自动重新排序，勾选项目移至所属部分底部，取消勾选则移回活动列表。
2. **适用场景**：适用于管理购物清单，能让活动项目始终处于顶部，完成项目置于底部，使购物过程更流畅。
3. **核心特色**：
    - 自动排序：根据勾选状态自动调整项目位置。
    - 分区意识：尊重Markdown标题，仅在当前部分内排序，可维护分类。
    - 智能防抖：1秒无操作后排序，避免快速修改时项目跳动。
    - 光标感知：编辑即将移动的行时，延迟排序，不打断输入。
4. **使用建议**：插件仅对标记为购物清单的文件生效，可通过在YAML前置元数据添加`shopping-list: true`或在笔记中添加`#shopping-list`标签来标记。还可在设置中选择勾选项目的放置位置。安装可从GitHub下载相关文件，放入指定目录并启用。


> [!help] 
> 这篇插件文章还没有人贡献，欢迎占坑！
> 如果您有好的想法欢迎提交PR或者文末留言。
> 

---


