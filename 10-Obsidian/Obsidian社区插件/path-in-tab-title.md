---
uid: 1780392511980000
title: 'Obsidian 插件：Path in tab title'
tags: ['界面优化', '文件管理', '效率工具', 'obsidian插件']
description: '在标签页标题中显示文件夹名称。'
author: AI
type: auto
draft: false
editable: false
modified: 20240101000000
---

# Obsidian 插件：Path in tab title

> [!Note] 插件名片
> - 插件名称：Path in tab title
> - 插件作者：d9k
> - 插件说明：在标签页标题中显示文件夹名称。
> - 插件分类：['界面优化', '文件管理', '效率工具', 'obsidian插件']
> - 项目地址：[点我访问](https://github.com/d9k/obsidian-path-in-tab-title)
> - 国内下载地址：[下载安装](https://pkmer.cn/products/plugin/pluginMarket/?path-in-tab-title)
> - 自述文件：[Readme](https://ghproxy.net/https://raw.githubusercontent.com/d9k/obsidian-path-in-tab-title/master/README.md)

![Path in tab title](https://cdn.pkmer.cn/covers/path-in-tab-title_internal_0.png!pkmer)

## 概述

### 插件名称
Path in tab title

### 主要功能
在标签页标题中显示文件夹名称。

### 适用场景
适用于拥有大量笔记且按文件夹分类管理的Obsidian用户，能帮助用户更清晰地识别不同笔记所在的文件夹路径。

### 核心特色
能让用户直观看到笔记所在的文件夹路径，便于快速定位文件。

### 使用建议
1. 安装时，将 `main.js` 和 `manifest.json` 复制到 `.obsidian/plugins/path-in-tab-title/` 文件夹，重启Obsidian后在设置中启用。
2. 由于存在更新标签标题有延迟、应用重启后标签标题恢复默认、仅更改聚焦标签标题等已知限制，使用时需留意。
3. 可添加推荐样式，使标签标题中的文件夹名称显示更美观：
```css
.workspace-tab-header-inner-title small {
  opacity: 70%;
}
```
4. 也可尝试替换 `app.js` 中的代码，但因涉及Electron应用补丁，需谨慎操作。


> [!help] 
> 这篇插件文章还没有人贡献，欢迎占坑！
> 如果您有好的想法欢迎提交PR或者文末留言。
> 

---


