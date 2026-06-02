---
uid: 1780392511013000
title: 'Obsidian 插件：CJK Bold Fix'
tags: ['样式与美化', '文字处理', '编辑工具', 'obsidian插件']
description: '这个插件还没经过Obsidian官方人员的人工审核。它能修复实时预览模式下中文、日文、韩文的粗体和斜体显示问题。'
author: AI
type: auto
draft: false
editable: false
modified: 20240101000000
---

# Obsidian 插件：CJK Bold Fix

> [!Note] 插件名片
> - 插件名称：CJK Bold Fix
> - 插件作者：ebibibi
> - 插件说明：这个插件还没经过Obsidian官方人员的人工审核。它能修复实时预览模式下中文、日文、韩文的粗体和斜体显示问题。
> - 插件分类：['样式与美化', '文字处理', '编辑工具', 'obsidian插件']
> - 项目地址：[点我访问](https://github.com/ebibibi/obsidian-cjk-bold-fix)
> - 国内下载地址：[下载安装](https://pkmer.cn/products/plugin/pluginMarket/?cjk-bold-fix)
> - 自述文件：[Readme](https://ghproxy.net/https://raw.githubusercontent.com/ebibibi/obsidian-cjk-bold-fix/master/README.md)



## 概述

### CJK Bold Fix插件总结
1. **主要功能**：修复Obsidian实时预览模式下中文、日文、韩文文本的加粗和斜体显示问题。
2. **适用场景**：适用于在Obsidian实时预览模式下编辑包含CJK文字的笔记时，遇到加粗和斜体显示异常的情况。
3. **核心特色**：通过注册CodeMirror 6 ViewPlugin，分四个阶段处理文本。先收集解析器强调信息，再用正则确定正确强调位置，接着覆盖错误强调，最后应用正确强调样式并隐藏标记。
4. **使用建议**：可通过Obsidian社区插件浏览器搜索“CJK Bold Fix”安装，也可手动从GitHub下载`main.js`和`manifest.json`，创建`cjk-bold-fix`文件夹并放入文件，最后在Obsidian设置中启用插件。该插件仅解决实时预览模式的显示问题，阅读模式显示正常。


> [!help] 
> 这篇插件文章还没有人贡献，欢迎占坑！
> 如果您有好的想法欢迎提交PR或者文末留言。
> 

---


