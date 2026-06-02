---
uid: 1780392511238000
title: 'Obsidian 插件：Live Preview Bold Fix'
tags: ['样式与美化', '编辑工具', '文字处理', '界面优化', 'obsidian插件']
description: '它通过覆盖粗体样式范围，修复了实时预览中粗体显示偏移的问题。'
author: AI
type: auto
draft: false
editable: false
modified: 20240101000000
---

# Obsidian 插件：Live Preview Bold Fix

> [!Note] 插件名片
> - 插件名称：Live Preview Bold Fix
> - 插件作者：konoyo-014
> - 插件说明：它通过覆盖粗体样式范围，修复了实时预览中粗体显示偏移的问题。
> - 插件分类：['样式与美化', '编辑工具', '文字处理', '界面优化', 'obsidian插件']
> - 项目地址：[点我访问](https://github.com/konoyo-014/obsidian-live-preview-bold-fix)
> - 国内下载地址：[下载安装](https://pkmer.cn/products/plugin/pluginMarket/?live-preview-bold-fix)
> - 自述文件：[Readme](https://ghproxy.net/https://raw.githubusercontent.com/konoyo-014/obsidian-live-preview-bold-fix/master/README.md)



## 概述

### Live Preview Bold Fix插件总结
1. **主要功能**：在不重写笔记内容的情况下，稳定Obsidian实时预览的渲染行为。解决混合中日韩文（CJK）与英文文本中，标点和括号周围粗体渲染不一致的问题，以及实时预览中`\\( ... \\)`和`\\[ ... \\]`的预览层渲染问题。
2. **适用场景**：适用于使用Obsidian实时预览功能，且遇到粗体渲染漂移、混合文本粗体显示不一致、数学公式预览异常等情况的用户。
3. **核心特色**：仅影响编辑器渲染，不转换或修改Markdown文件；对粗体文本应用确定性装饰层，在光标位置附近控制标记可见性；复用Obsidian内置数学小部件行为，保证数学渲染视觉一致性。
4. **使用建议**：手动安装时，将`manifest.json`、`main.js`和`versions.json`放入`.obsidian/plugins/live-preview-bold-fix/`目录，重启Obsidian并在社区插件中启用。因该插件在CodeMirror装饰层工作，兼容性可能受其他编辑渲染插件影响，测试时建议使用包含粗体边界和行内/块级数学示例的专用笔记。


> [!help] 
> 这篇插件文章还没有人贡献，欢迎占坑！
> 如果您有好的想法欢迎提交PR或者文末留言。
> 

---


