---
uid: 1780392511212001
title: 'Obsidian 插件：Lark Wiki Sync'
tags: ['第三方工具集成', '效率工具', '自动化与AI', '文件管理', 'obsidian插件']
description: '这个插件还未经过Obsidian官方人员的人工审核。它能实现你的Obsidian仓库和飞书知识库空间之间的双向同步，底层使用了lark-cli。它带有设置向导、一键同步功能，还能进行三方冲突解决。'
author: AI
type: auto
draft: false
editable: false
modified: 20240101000000
---

# Obsidian 插件：Lark Wiki Sync

> [!Note] 插件名片
> - 插件名称：Lark Wiki Sync
> - 插件作者：Faiszal Anwar
> - 插件说明：这个插件还未经过Obsidian官方人员的人工审核。它能实现你的Obsidian仓库和飞书知识库空间之间的双向同步，底层使用了lark-cli。它带有设置向导、一键同步功能，还能进行三方冲突解决。
> - 插件分类：['第三方工具集成', '效率工具', '自动化与AI', '文件管理', 'obsidian插件']
> - 项目地址：[点我访问](https://github.com/fszlnwr/obsidian-lark-wiki-sync)
> - 国内下载地址：[下载安装](https://pkmer.cn/products/plugin/pluginMarket/?lark-wiki-sync)
> - 自述文件：[Readme](https://ghproxy.net/https://raw.githubusercontent.com/fszlnwr/obsidian-lark-wiki-sync/master/README.md)



## 概述

### Lark Wiki Sync 插件总结
1. **主要功能**：实现 Obsidian 库与飞书文档空间的双向同步，可将一个或多个飞书文档空间同步到 Obsidian 库中，支持多空间配置、全量拉取、图片下载、冲突检测与处理等。
2. **适用场景**：适用于习惯在 Obsidian 中整理笔记，同时需要与飞书文档协同工作的用户，方便在两个平台间同步数据。
3. **核心特色**：
    - 提供设置向导，可通过下拉选择空间或粘贴文档链接配置。
    - 支持多空间同步，各空间在本地有独立子文件夹。
    - 自动将飞书标签转换为标准 Markdown 格式。
    - 具备三方冲突检测与处理机制，同步状态以飞书节点令牌为键，不受路径映射变化影响。
    - 同步前有预计划弹窗，可选择操作。
4. **使用建议**：当前版本推送功能未经端到端验证，冲突处理可能会使用 `.remote.conflict.md` 副文件，使用时可先进行测试，谨慎操作。


> [!help] 
> 这篇插件文章还没有人贡献，欢迎占坑！
> 如果您有好的想法欢迎提交PR或者文末留言。
> 

---


