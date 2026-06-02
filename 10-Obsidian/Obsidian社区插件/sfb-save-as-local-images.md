---
uid: 1780392512031001
title: 'Obsidian 插件：Save as Local Images'
tags: ['图片与PDF', '编辑工具', '效率工具', '文件管理', 'obsidian插件']
description: '它可以下载当前笔记里所有的远程图片，并把它们保存到你仓库的附件文件夹中，同时会重写链接，让其指向本地副本。'
author: AI
type: auto
draft: false
editable: false
modified: 20240101000000
---

# Obsidian 插件：Save as Local Images

> [!Note] 插件名片
> - 插件名称：Save as Local Images
> - 插件作者：saltyfireball
> - 插件说明：它可以下载当前笔记里所有的远程图片，并把它们保存到你仓库的附件文件夹中，同时会重写链接，让其指向本地副本。
> - 插件分类：['图片与PDF', '编辑工具', '效率工具', '文件管理', 'obsidian插件']
> - 项目地址：[点我访问](https://github.com/saltyfireball/obsidian-save-as-local-images)
> - 国内下载地址：[下载安装](https://pkmer.cn/products/plugin/pluginMarket/?sfb-save-as-local-images)
> - 自述文件：[Readme](https://ghproxy.net/https://raw.githubusercontent.com/saltyfireball/obsidian-save-as-local-images/master/README.md)



## 概述

### Save as Local Images插件总结
1. **主要功能**：下载当前笔记或整个文件夹（递归）中的远程图片并保存到本地库，重写图片URL指向本地副本。
2. **适用场景**：适用于需要将笔记中远程图片本地化的场景，无论是单笔记还是批量处理文件夹内的笔记。
3. **核心特色**：
    - 支持多种图片语法，包括Markdown、HTML、Wiki嵌入等。
    - 自动按笔记路径创建文件夹结构保存图片。
    - 处理前置元数据中的图片URL。
    - 重写URL，安全处理含特殊字符的本地路径。
    - 生成唯一文件名，避免冲突。
    - 根据HTTP头检测文件扩展名。
    - 单文件错误处理，不影响其他图片下载。
    - 显示下载进度。
4. **使用建议**：可通过命令面板“Save all remote images locally”处理单笔记图片；在文件资源管理器中右键文件夹选择该选项处理整个文件夹。遇到错误可查看控制台日志。


> [!help] 
> 这篇插件文章还没有人贡献，欢迎占坑！
> 如果您有好的想法欢迎提交PR或者文末留言。
> 

---


