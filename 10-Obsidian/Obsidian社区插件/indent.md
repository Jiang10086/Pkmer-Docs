---
uid: 1780392511183001
title: 'Obsidian 插件：Indent'
tags: ['编辑工具', '文字处理', '效率工具', 'obsidian插件']
description: '这个插件还没有经过Obsidian官方人员的手动审核。禁用缩进代码块，这样制表符/空格就会变成常规缩进。'
author: AI
type: auto
draft: false
editable: false
modified: 20240101000000
---

# Obsidian 插件：Indent

> [!Note] 插件名片
> - 插件名称：Indent
> - 插件作者：Jan Sandström
> - 插件说明：这个插件还没有经过Obsidian官方人员的手动审核。禁用缩进代码块，这样制表符/空格就会变成常规缩进。
> - 插件分类：['编辑工具', '文字处理', '效率工具', 'obsidian插件']
> - 项目地址：[点我访问](https://github.com/pixerojan/obsidian-indent)
> - 国内下载地址：[下载安装](https://pkmer.cn/products/plugin/pluginMarket/?indent)
> - 自述文件：[Readme](https://ghproxy.net/https://raw.githubusercontent.com/pixerojan/obsidian-indent/master/README.md)



## 概述

### 插件名称
Indent

### 主要功能
在Obsidian的实时预览模式下，禁用缩进代码块，使制表符或空格成为正常缩进。通过在以制表符或4个以上空格开头的行前添加零宽非连接符（ZWNJ），让缩进正常显示且不触发代码块规则。

### 适用场景
适用于在Obsidian中编写文本时，不希望以缩进形式触发代码块，而是希望实现正常文本缩进的场景。

### 核心特色
- 将缩进行视为普通文本，不生成缩进代码块。
- 保留围栏代码块。
- 不影响列表和引用行。
- 保留实际输入的缩进方式（制表符或空格）。
- 可在插件设置中开启或关闭该功能。

### 使用建议
该插件在编辑后会立即在编辑器中应用更改，可正常使用Tab键。若需开发该插件，可按步骤安装依赖、构建和开启监听模式。需注意，此插件有意偏离CommonMark规范以消除缩进代码块。


> [!help] 
> 这篇插件文章还没有人贡献，欢迎占坑！
> 如果您有好的想法欢迎提交PR或者文末留言。
> 

---


