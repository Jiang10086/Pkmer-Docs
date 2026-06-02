---
uid: 1780392511000001
title: 'Obsidian 插件：ChatGPT Math Clipboard'
tags: ['第三方工具集成', '编辑工具', '自动化与AI', '文字处理', 'obsidian插件']
description: '它能将ChatGPT网页查看器的回复复制为Markdown格式，并严格把KaTeX转换为LaTeX。'
author: AI
type: auto
draft: false
editable: false
modified: 20240101000000
---

# Obsidian 插件：ChatGPT Math Clipboard

> [!Note] 插件名片
> - 插件名称：ChatGPT Math Clipboard
> - 插件作者：vofen
> - 插件说明：它能将ChatGPT网页查看器的回复复制为Markdown格式，并严格把KaTeX转换为LaTeX。
> - 插件分类：['第三方工具集成', '编辑工具', '自动化与AI', '文字处理', 'obsidian插件']
> - 项目地址：[点我访问](https://github.com/vofen430/obsidian-chatgpt-math-clipboard)
> - 国内下载地址：[下载安装](https://pkmer.cn/products/plugin/pluginMarket/?chatgpt-math-clipboard)
> - 自述文件：[Readme](https://ghproxy.net/https://raw.githubusercontent.com/vofen430/obsidian-chatgpt-math-clipboard/master/README.md)



## 概述

### 主要功能
ChatGPT Math Clipboard是一款Obsidian桌面插件，可将ChatGPT内置Web Viewer中的公式以Markdown格式复制到笔记中，能正确渲染。点击ChatGPT原生复制按钮时，插件读取渲染后的响应DOM，将内联KaTeX转换为`$...$`，显示KaTeX转换为`$$...$$`，且剪贴板仅含纯文本。

### 适用场景
适用于在Obsidian中使用ChatGPT Web Viewer，需要将ChatGPT中的公式复制到笔记的场景。

### 核心特色
- 仅转换带有`application/x - tex`注释的KaTeX节点，不猜测括号是否为公式。
- 若ChatGPT DOM改变导致严格提取失败，保留原生复制行为。
- 本地运行，仅对`chatgpt.com`的Web Viewer页面生效，不进行网络请求、不存储账户数据、不上传内容。

### 使用建议
需启用Obsidian桌面的核心Web Viewer插件，并在Web Viewer中打开ChatGPT标签页。该版本在Obsidian `1.12.7`和2026年5月30日的ChatGPT DOM上验证通过。


> [!help] 
> 这篇插件文章还没有人贡献，欢迎占坑！
> 如果您有好的想法欢迎提交PR或者文末留言。
> 

---


