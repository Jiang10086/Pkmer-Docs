---
uid: 1780392511013001
title: 'Obsidian 插件：CJK Cross-Script Search'
tags: ['搜索与排序', '文字处理', '效率工具', 'obsidian插件']
description: 'None'
author: AI
type: auto
draft: false
editable: false
modified: 20240101000000
---

# Obsidian 插件：CJK Cross-Script Search

> [!Note] 插件名片
> - 插件名称：CJK Cross-Script Search
> - 插件作者：sai1047976
> - 插件说明：None
> - 插件分类：['搜索与排序', '文字处理', '效率工具', 'obsidian插件']
> - 项目地址：[点我访问](https://github.com/sai1047976/obsidian-cjk-cross-search)
> - 国内下载地址：[下载安装](https://pkmer.cn/products/plugin/pluginMarket/?cjk-cross-search)
> - 自述文件：[Readme](https://ghproxy.net/https://raw.githubusercontent.com/sai1047976/obsidian-cjk-cross-search/master/README.md)



## 概述

### CJK Cross - Script Search插件总结
1. **主要功能**：在Obsidian全局搜索中，能让简体中文和繁体中文相互匹配查找，如输入“萬維鋼”可找到含“万维钢”的文件，反之亦然。还能处理常见的两岸用词差异，如“軟體”“軟件”“软件”可相互匹配。支持搜索框输入和编程式搜索调用。
2. **适用场景**：适用于Obsidian的全局搜索面板（`Cmd + Shift + F` / `Ctrl + Shift + F`），暂不适用于快速切换器和标签/反向链接面板。
3. **核心特色**：利用OpenCC重写查询，使用Obsidian原生的`OR`语法，不干扰CJK输入法，在输入法组合期间暂停重写，保证候选窗口正常工作。输入框显示原内容，仅扩展底层查询。
4. **使用建议**：可在设置中开启或关闭跨脚本搜索，选择OpenCC变体（默认“Taiwan”，或选“Basic”减少误匹配），还可开启调试日志查看重写的查询。


> [!help] 
> 这篇插件文章还没有人贡献，欢迎占坑！
> 如果您有好的想法欢迎提交PR或者文末留言。
> 

---


