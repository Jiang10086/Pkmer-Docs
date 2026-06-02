---
uid: 2026060213561221
title: 'Obsidian 插件：Agent Skill Graph'
tags: ['图表与可视化', '自动化与AI', '图谱', 'obsidian插件']
description: '这个插件还没经过Obsidian官方人员的人工审核。它能在图形视图中可视化人工智能代理的技能结构。它可以根据前置元数据重命名SKILL.md节点，绘制引用边，还能根据节点类型为节点上色。'
author: AI
type: auto
draft: false
editable: false
modified: 20240101000000
---

# Obsidian 插件：Agent Skill Graph

> [!Note] 插件名片
> - 插件名称：Agent Skill Graph
> - 插件作者：hanamizuki
> - 插件说明：这个插件还没经过Obsidian官方人员的人工审核。它能在图形视图中可视化人工智能代理的技能结构。它可以根据前置元数据重命名SKILL.md节点，绘制引用边，还能根据节点类型为节点上色。
> - 插件分类：['图表与可视化', '自动化与AI', '图谱', 'obsidian插件']
> - 项目地址：[点我访问](https://github.com/hanamizuki/obsidian-skill-graph)
> - 国内下载地址：[下载安装](https://pkmer.cn/products/plugin/pluginMarket/?agent-skill-graph)
> - 自述文件：[Readme](https://ghproxy.net/https://raw.githubusercontent.com/hanamizuki/obsidian-skill-graph/master/README.md)



## 概述

### Agent Skill Graph插件总结
1. **主要功能**：在Obsidian的图形视图中可视化OpenClaw / Claude Code代理技能结构。将SKILL.md节点按前置元数据重命名，绘制引用边，并按类型为节点着色。
2. **适用场景**：适用于管理OpenClaw或Claude Code代理技能目录的用户，可直观查看技能结构和引用关系。
3. **核心特色**：以图形化方式展示技能结构，节点显示前置元数据中的名称，自动解析引用文件并建立连接，按类型区分节点颜色。且为只读模式，不修改原始文件，更改仅在内存中，禁用插件后恢复。
4. **使用建议**：先从技能目录创建保险库，再安装插件（克隆或下载仓库并建立符号链接），然后在Obsidian中启用插件，最后通过命令打开图形视图。开发时可使用`npm run dev`开启监听模式。


> [!help] 
> 这篇插件文章还没有人贡献，欢迎占坑！
> 如果您有好的想法欢迎提交PR或者文末留言。
> 

---


