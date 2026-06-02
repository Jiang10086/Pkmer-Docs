---
uid: 1780392511136002
title: 'Obsidian 插件：GoodReadSync'
tags: ['第三方工具集成', '学习与教育', '数据处理', '效率工具', 'obsidian插件']
description: '它可以把Goodreads上的书籍信息同步到你的仓库里。'
author: AI
type: auto
draft: false
editable: false
modified: 20240101000000
---

# Obsidian 插件：GoodReadSync

> [!Note] 插件名片
> - 插件名称：GoodReadSync
> - 插件作者：sergiodlash
> - 插件说明：它可以把Goodreads上的书籍信息同步到你的仓库里。
> - 插件分类：['第三方工具集成', '学习与教育', '数据处理', '效率工具', 'obsidian插件']
> - 项目地址：[点我访问](https://github.com/sergiodlash/goodreadsync)
> - 国内下载地址：[下载安装](https://pkmer.cn/products/plugin/pluginMarket/?goodreadsync)
> - 自述文件：[Readme](https://ghproxy.net/https://raw.githubusercontent.com/sergiodlash/goodreadsync/master/README.md)



## 概述

### GoodReadSync插件总结
1. **主要功能**：自动将Goodreads书架上的书籍信息同步到Obsidian库中，为书籍创建笔记。
2. **适用场景**：适合喜欢在Goodreads记录阅读信息，同时希望将这些信息整合到Obsidian进行知识管理的用户。
3. **核心特色**：利用Goodreads的RSS订阅源，根据用户设置的书架自动创建笔记。通过检查`bookID`避免重复导入，保证笔记的唯一性。
4. **使用建议**：
    - 先创建模板笔记，笔记中必须包含`bookID: {{ book_id }}`属性。
    - 在插件设置里，填写Goodreads用户ID（可从个人资料URL获取）、要导入的书架名称、笔记创建的目标目录和模板笔记路径。
    - 可通过命令面板调用导入命令，也能点击左侧功能区的书籍图标来导入新书到库中。


> [!help] 
> 这篇插件文章还没有人贡献，欢迎占坑！
> 如果您有好的想法欢迎提交PR或者文末留言。
> 

---


