---
uid: 2026022517443251
title: 'Obsidian 插件：Last Edit Location'
tags: ['编辑工具', '效率工具', '导航与状态栏', 'obsidian插件']
description: '打开笔记时，将光标定位到上次编辑的位置。在处理多个笔记时也能很好地发挥作用。'
author: AI
type: auto
draft: false
editable: false
modified: 20240101000000
---

# Obsidian 插件：Last Edit Location

> [!Note] 插件名片
> - 插件名称：Last Edit Location
> - 插件作者：Kyoungdeuk
> - 插件说明：打开笔记时，将光标定位到上次编辑的位置。在处理多个笔记时也能很好地发挥作用。
> - 插件分类：['编辑工具', '效率工具', '导航与状态栏', 'obsidian插件']
> - 项目地址：[点我访问](https://github.com/awfrok/obsidian-plugin-last-edit-location)
> - 国内下载地址：[下载安装](https://pkmer.cn/products/plugin/pluginMarket/?last-edit-location)
> - 自述文件：[Readme](https://ghproxy.net/https://raw.githubusercontent.com/awfrok/obsidian-plugin-last-edit-location/master/README.md)

![Last Edit Location](https://cdn.pkmer.cn/covers/last-edit-location_internal_1.png!pkmer)

## 概述

### Last Edit Location插件总结
1. **主要功能**：在Obsidian中打开笔记时，将光标移动到该笔记的最后编辑位置，且每个笔记仅执行一次此操作，支持多笔记操作。
2. **适用场景**：适用于在Obsidian中频繁编辑多个笔记，希望快速定位到上次编辑位置的用户。
3. **核心特色**：
    - 采用多种唯一标识符，包括插件生成的UUID、用户提供的字段、文件路径，满足不同用户需求。
    - 编辑笔记时，存储笔记唯一标识符及编辑的行号和字符号。
4. **使用建议**：
    - 在设置中选择“source”选项并为唯一标识符指定“ID name”，可选择插件生成UUID、用户提供字段或文件路径作为唯一标识符。
    - 若选择插件生成UUID，缺少时插件会自动生成；选择用户提供字段，需确保前置元数据中有该字段；选择文件路径则适用于不使用前置元数据的情况。
    - 可选择插件生效的文件夹。


> [!help] 
> 这篇插件文章还没有人贡献，欢迎占坑！
> 如果您有好的想法欢迎提交PR或者文末留言。
> 

---


