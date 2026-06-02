---
uid: 1780392512128000
title: 'Obsidian 插件：Tegaki'
tags: ['自动化与AI', '文字处理', '第三方工具集成', '图片与PDF', 'obsidian插件']
description: '这个插件还没经过Obsidian官方人员的人工审核哈。它能利用AI视觉API（Gemini / Claude）把手写笔记和图片转换成可搜索的文本。注意哦，图片会被发送到外部API（谷歌 / Anthropic）那里去处理。'
author: AI
type: auto
draft: false
editable: false
modified: 20240101000000
---

# Obsidian 插件：Tegaki

> [!Note] 插件名片
> - 插件名称：Tegaki
> - 插件作者：Sdesuyo
> - 插件说明：这个插件还没经过Obsidian官方人员的人工审核哈。它能利用AI视觉API（Gemini / Claude）把手写笔记和图片转换成可搜索的文本。注意哦，图片会被发送到外部API（谷歌 / Anthropic）那里去处理。
> - 插件分类：['自动化与AI', '文字处理', '第三方工具集成', '图片与PDF', 'obsidian插件']
> - 项目地址：[点我访问](https://github.com/sdesuyo/obsidian-tegaki)
> - 国内下载地址：[下载安装](https://pkmer.cn/products/plugin/pluginMarket/?tegaki)
> - 自述文件：[Readme](https://ghproxy.net/https://raw.githubusercontent.com/sdesuyo/obsidian-tegaki/master/README.md)



## 概述

### Tegaki插件总结
1. **主要功能**：利用AI视觉API（Gemini / Claude）将手写笔记、白板照片和幻灯片截图转换为可搜索的Obsidian笔记，能提取所有印刷文本并保留结构布局，还能提取手写注释及其位置信息。
2. **适用场景**：适用于需要将手写内容电子化、方便搜索和整理笔记的场景，如学生整理课堂笔记、职场人士记录会议内容等。
3. **核心特色**：与普通OCR不同，Tegaki能理解注释的书写位置，如圈画、箭头指向、页边笔记等，不仅记录内容，还记录位置信息。
4. **使用建议**：通过`Ctrl + P`可使用两个命令，“OCR: append to note”进行全面OCR并将结果追加到当前笔记；“OCR: handwriting only”仅提取带位置信息的手写注释。需注意，图像会发送到外部API进行OCR处理，不要用于含敏感信息的图像，API密钥本地存储在Obsidian库中。


> [!help] 
> 这篇插件文章还没有人贡献，欢迎占坑！
> 如果您有好的想法欢迎提交PR或者文末留言。
> 

---


