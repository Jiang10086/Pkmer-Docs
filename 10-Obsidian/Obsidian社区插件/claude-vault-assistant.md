---
uid: 1780392511018001
title: 'Obsidian 插件：Claude Vault Assistant'
tags: ['第三方工具集成', '自动化与AI', '自定义命令', '效率工具', 'obsidian插件']
description: '这个插件还没经过Obsidian官方人员的人工审核。你可以定义可重复使用的提示文件，然后通过Claude Code CLI在你的仓库或当前笔记里运行这些文件。'
author: AI
type: auto
draft: false
editable: false
modified: 20240101000000
---

# Obsidian 插件：Claude Vault Assistant

> [!Note] 插件名片
> - 插件名称：Claude Vault Assistant
> - 插件作者：copperbox
> - 插件说明：这个插件还没经过Obsidian官方人员的人工审核。你可以定义可重复使用的提示文件，然后通过Claude Code CLI在你的仓库或当前笔记里运行这些文件。
> - 插件分类：['第三方工具集成', '自动化与AI', '自定义命令', '效率工具', 'obsidian插件']
> - 项目地址：[点我访问](https://github.com/copperbox/obsidian-claude-vault-assistant)
> - 国内下载地址：[下载安装](https://pkmer.cn/products/plugin/pluginMarket/?claude-vault-assistant)
> - 自述文件：[Readme](https://ghproxy.net/https://raw.githubusercontent.com/copperbox/obsidian-claude-vault-assistant/master/README.md)



## 概述

### Claude Vault Assistant插件总结
1. **主要功能**：可在Obsidian内针对整个库或当前活动笔记运行预定义的Claude提示，用户能定义可重复使用的提示文件（`PROMPT-*.md`），借助Claude Code CLI执行操作。
2. **适用场景**：适用于需要利用Claude对Obsidian库内笔记进行处理、分析、编辑等操作的场景。
3. **核心特色**：允许用户自定义提示文件，在Obsidian内部直接调用Claude Code CLI进行操作，可对库或单笔记处理。
4. **使用建议**：该插件通过在本地生成Claude Code CLI的shell进程工作，使用前需了解：插件会调用真实shell进程；Claude能执行“Allowed tools”中允许的操作，添加高风险工具（如Bash）需谨慎；笔记内容存在提示注入风险，运行前要审计库内内容，避免不可信内容导致意外文件编辑或命令执行。


> [!help] 
> 这篇插件文章还没有人贡献，欢迎占坑！
> 如果您有好的想法欢迎提交PR或者文末留言。
> 

---


