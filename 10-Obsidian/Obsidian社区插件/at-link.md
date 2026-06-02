---
uid: 2026060213561282
title: 'Obsidian 插件：At Link'
tags: ['编辑工具', '模板与链接处理', '效率工具', 'obsidian插件']
description: '输入@可以打开自动补全功能，补全笔记、标题和块的维基链接。'
author: AI
type: auto
draft: false
editable: false
modified: 20240101000000
---

# Obsidian 插件：At Link

> [!Note] 插件名片
> - 插件名称：At Link
> - 插件作者：Stefan Imbesi
> - 插件说明：输入@可以打开自动补全功能，补全笔记、标题和块的维基链接。
> - 插件分类：['编辑工具', '模板与链接处理', '效率工具', 'obsidian插件']
> - 项目地址：[点我访问](https://github.com/stefan-imbesi/obsidian-at-link)
> - 国内下载地址：[下载安装](https://pkmer.cn/products/plugin/pluginMarket/?at-link)
> - 自述文件：[Readme](https://ghproxy.net/https://raw.githubusercontent.com/stefan-imbesi/obsidian-at-link/master/README.md)



## 概述

### At Link插件总结
1. **主要功能**：在Obsidian编辑器中输入 `@` 时，开启内部链接自动补全功能，可从笔记、标题和块中搜索并插入维基链接。
2. **适用场景**：适用于需要快速插入维基链接的场景，如撰写笔记时引用其他笔记、标题或块。
3. **核心特色**：
    - 以 `@` 为明确触发符号，在行首或空格后输入 `@` 触发自动补全。
    - 搜索范围包括库中的Markdown文件、标题和有 `^id` 的块。
    - 选择建议后，自动将 `@query` 替换为正确的维基链接。
    - 搜索结果按精确前缀、不区分大小写的前缀、模糊子序列排序，最多显示20条。
4. **使用建议**：
    - 安装时，将 `main.js`、`manifest.json` 和 `styles.css` 复制到库的插件文件夹。
    - 开发时，使用 `npm run dev` 进行实时构建，构建后可复制 `main.js` 或创建符号链接更新插件。


> [!help] 
> 这篇插件文章还没有人贡献，欢迎占坑！
> 如果您有好的想法欢迎提交PR或者文末留言。
> 

---


