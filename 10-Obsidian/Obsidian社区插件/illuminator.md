---
uid: 1780392511169000
title: 'Obsidian 插件：Illuminator'
tags: ['图片与PDF', '自动化与AI', '效率工具', '样式与美化', 'obsidian插件']
description: '这个插件还没经过Obsidian官方人员的人工审核。它能在粘贴图片时自动去除图片的白色背景，并将图片转换为优化后的WebP格式。这对于在浅色主题的仓库里保持文字清晰度和视觉协调性来说，简直太合适啦。'
author: AI
type: auto
draft: false
editable: false
modified: 20240101000000
---

# Obsidian 插件：Illuminator

> [!Note] 插件名片
> - 插件名称：Illuminator
> - 插件作者：tiezjin
> - 插件说明：这个插件还没经过Obsidian官方人员的人工审核。它能在粘贴图片时自动去除图片的白色背景，并将图片转换为优化后的WebP格式。这对于在浅色主题的仓库里保持文字清晰度和视觉协调性来说，简直太合适啦。
> - 插件分类：['图片与PDF', '自动化与AI', '效率工具', '样式与美化', 'obsidian插件']
> - 项目地址：[点我访问](https://github.com/tiezjin/illuminator)
> - 国内下载地址：[下载安装](https://pkmer.cn/products/plugin/pluginMarket/?illuminator)
> - 自述文件：[Readme](https://ghproxy.net/https://raw.githubusercontent.com/tiezjin/illuminator/master/README.md)



## 概述

### Illuminator插件总结
1. **主要功能**：当直接粘贴图片或在文件面板右键点击图片时，将白色背景转为透明，转换图片为更小体积的WebP格式，并自动更新笔记链接。
2. **适用场景**：适合在浅色模式下使用自定义背景色（如米黄、淡绿等）的用户。不过要注意，去除白色背景后，在Obsidian暗黑模式下图片中的纯黑色文字会难以看清。
3. **核心特色**：采用RGB阈值，将亮度高于设定值的像素转为100%透明；所有处理都在本地Web Worker中完成，数据不离开文件夹；属于本地轻量级插件。
4. **使用建议**：此操作会永久修改图像数据且不可逆，如有需要，使用前请备份原始图片。安装时，先下载main.js和manifest.json文件，在库中创建.obsidian/plugins/illuminator/文件夹，将文件移入该文件夹，再在设置的社区插件中启用。


> [!help] 
> 这篇插件文章还没有人贡献，欢迎占坑！
> 如果您有好的想法欢迎提交PR或者文末留言。
> 

---


