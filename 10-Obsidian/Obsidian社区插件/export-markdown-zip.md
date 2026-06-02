---
uid: 1780392511090000
title: 'Obsidian 插件：Export Markdown ZIP'
tags: ['文件管理', '备份与恢复', '发布工具', '效率工具', 'obsidian插件']
description: '这个插件还没经过Obsidian官方人员的人工审核。可以把一篇带有关联笔记和本地附件的笔记导出成一个压缩包。'
author: AI
type: auto
draft: false
editable: false
modified: 20240101000000
---

# Obsidian 插件：Export Markdown ZIP

> [!Note] 插件名片
> - 插件名称：Export Markdown ZIP
> - 插件作者：padane22-spec
> - 插件说明：这个插件还没经过Obsidian官方人员的人工审核。可以把一篇带有关联笔记和本地附件的笔记导出成一个压缩包。
> - 插件分类：['文件管理', '备份与恢复', '发布工具', '效率工具', 'obsidian插件']
> - 项目地址：[点我访问](https://github.com/padane22-spec/obsidian-export-markdown-zip)
> - 国内下载地址：[下载安装](https://pkmer.cn/products/plugin/pluginMarket/?export-markdown-zip)
> - 自述文件：[Readme](https://ghproxy.net/https://raw.githubusercontent.com/padane22-spec/obsidian-export-markdown-zip/master/README.md)

![Export Markdown ZIP](https://cdn.pkmer.cn/covers/export-markdown-zip_internal_0.gif!pkmer)

## 概述

### Export Markdown ZIP插件总结
1. **主要功能**：将一个Markdown笔记及其递归链接的Markdown文件、本地图片和非图片附件，以及重写后仍能正常工作的Markdown图，导出为单个ZIP存档。
2. **适用场景**：当需要分享Obsidian笔记时，避免接收者遇到链接损坏、图片缺失和上下文图不完整等问题。
3. **核心特色**：支持从命令面板或文件上下文菜单导出活动笔记；递归跟踪Obsidian维基链接和Markdown链接；包含图片、PDF、音频等本地附件；重写导出的Markdown链接为标准相对路径；在ZIP内保留以存档命名的顶级文件夹下的库相对路径。
4. **使用建议**：先通过`npm install`和`npm run build`构建插件，将相关文件复制到`.obsidian/plugins/export - markdown - zip/`目录，在Obsidian中启用该插件，可在插件设置中设置默认导出目录，也可每次手动选择。


> [!help] 
> 这篇插件文章还没有人贡献，欢迎占坑！
> 如果您有好的想法欢迎提交PR或者文末留言。
> 

---


