---
uid: 1780392511131000
title: 'Obsidian 插件：GitHub Pager'
tags: ['第三方工具集成', '发布工具', '效率工具', 'obsidian插件']
description: '这个插件还未经过Obsidian官方人员的人工审核。你可以有选择地将笔记和图片发布到GitHub，用于Hugo、Jekyll或Hexo网站。'
author: AI
type: auto
draft: false
editable: false
modified: 20240101000000
---

# Obsidian 插件：GitHub Pager

> [!Note] 插件名片
> - 插件名称：GitHub Pager
> - 插件作者：cloudac7
> - 插件说明：这个插件还未经过Obsidian官方人员的人工审核。你可以有选择地将笔记和图片发布到GitHub，用于Hugo、Jekyll或Hexo网站。
> - 插件分类：['第三方工具集成', '发布工具', '效率工具', 'obsidian插件']
> - 项目地址：[点我访问](https://github.com/cloudac7/obsidian-github-pager)
> - 国内下载地址：[下载安装](https://pkmer.cn/products/plugin/pluginMarket/?github-pager)
> - 自述文件：[Readme](https://ghproxy.net/https://raw.githubusercontent.com/cloudac7/obsidian-github-pager/master/README.md)



## 概述

### 主要功能
将Obsidian作为无头CMS，可选择性地将笔记和图片发布到GitHub仓库，适配Hugo、Jekyll、Hexo等静态网站生成器。支持通过映射表选择性同步、灵活设置远程路径、批量同步、智能检测变更、自动同步、回退到 `remote_path` 前置元数据、转换链接和处理图片。

### 适用场景
适合需要将Obsidian笔记发布到GitHub用于静态网站搭建的用户。

### 核心特色
- 选择性同步：可通过映射表管理本地文件与远程路径的对应关系。
- 灵活路径：远程文件名可与本地不同。
- 智能检测：内容未变时跳过推送。
- 自动同步：保存映射文件或含 `share: true` 前置元数据的文件时自动推送。

### 使用建议
安装时需克隆仓库、安装依赖、构建插件并复制文件到指定目录，再在Obsidian设置中启用。配置时需提供有 `repo` 权限的GitHub个人访问令牌、仓库所有者、仓库名、基础路径和图片路径等信息。


> [!help] 
> 这篇插件文章还没有人贡献，欢迎占坑！
> 如果您有好的想法欢迎提交PR或者文末留言。
> 

---


