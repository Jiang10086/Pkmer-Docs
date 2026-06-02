---
uid: 1780392510955002
title: 'Obsidian 插件：Beeminder Task Sync'
tags: ['第三方工具集成', '任务管理', '效率工具', '自动化与AI', 'obsidian插件']
description: '这个插件还没经过Obsidian官方人员的人工审核。它能将任务完成情况同步到Beeminder目标。可与Tasks插件配合使用。'
author: AI
type: auto
draft: false
editable: false
modified: 20240101000000
---

# Obsidian 插件：Beeminder Task Sync

> [!Note] 插件名片
> - 插件名称：Beeminder Task Sync
> - 插件作者：Leon Staufer
> - 插件说明：这个插件还没经过Obsidian官方人员的人工审核。它能将任务完成情况同步到Beeminder目标。可与Tasks插件配合使用。
> - 插件分类：['第三方工具集成', '任务管理', '效率工具', '自动化与AI', 'obsidian插件']
> - 项目地址：[点我访问](https://github.com/leonstaufer/obsidian-beeminder-task-sync)
> - 国内下载地址：[下载安装](https://pkmer.cn/products/plugin/pluginMarket/?beeminder-sync)
> - 自述文件：[Readme](https://ghproxy.net/https://raw.githubusercontent.com/leonstaufer/obsidian-beeminder-task-sync/master/README.md)



## 概述

### 《Beeminder Task Sync插件总结》
1. **主要功能**：自动将任务完成情况同步到Beeminder目标。给清单项目添加🐝标记，勾选任务时向Beeminder发送数据点，取消勾选则移除该数据点。
2. **适用场景**：适用于使用Obsidian管理任务，且希望将任务完成情况同步到Beeminder以跟踪进度的用户。无论是使用纯Markdown复选框，还是搭配Tasks插件都能使用。
3. **核心特色**：支持自动同步任务完成情况；与Beeminder集成，可直接在Obsidian中向Beeminder目标发送数据；具备自动补全功能，方便输入Beeminder目标。
4. **使用建议**：先从Obsidian社区插件目录安装并启用该插件，在设置中获取Beeminder的认证令牌并存储在Obsidian SecretStorage。给任务添加`🐝 goalname`标记，若省略`=value`则默认值为1。使用Tasks插件时，将`🐝`标记放在任务元数据之前。可在插件设置中配置自动补全的最小文本触发长度。


> [!help] 
> 这篇插件文章还没有人贡献，欢迎占坑！
> 如果您有好的想法欢迎提交PR或者文末留言。
> 

---


