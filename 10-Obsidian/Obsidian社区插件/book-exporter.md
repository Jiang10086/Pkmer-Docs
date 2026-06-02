---
uid: 1780392510968001
title: 'Obsidian 插件：Book Exporter'
tags: ['文字处理', '第三方工具集成', '发布工具', '效率工具', 'obsidian插件']
description: '这个插件还没经过Obsidian官方人员的人工审核。可以通过Pandoc把书籍（一个清单笔记 + 关联的章节笔记）导出为 EPUB 和 PDF 格式。'
author: AI
type: auto
draft: false
editable: false
modified: 20240101000000
---

# Obsidian 插件：Book Exporter

> [!Note] 插件名片
> - 插件名称：Book Exporter
> - 插件作者：Sébastien Dubois
> - 插件说明：这个插件还没经过Obsidian官方人员的人工审核。可以通过Pandoc把书籍（一个清单笔记 + 关联的章节笔记）导出为 EPUB 和 PDF 格式。
> - 插件分类：['文字处理', '第三方工具集成', '发布工具', '效率工具', 'obsidian插件']
> - 项目地址：[点我访问](https://github.com/dsebastien/obsidian-book-exporter)
> - 国内下载地址：[下载安装](https://pkmer.cn/products/plugin/pluginMarket/?book-exporter)
> - 自述文件：[Readme](https://ghproxy.net/https://raw.githubusercontent.com/dsebastien/obsidian-book-exporter/master/README.md)



## 概述

### Book Exporter插件总结
1. **主要功能**：该插件可将Obsidian库中的书籍（一个清单笔记加关联的章节笔记）通过Pandoc导出为EPUB和PDF格式。
2. **适用场景**：适用于在Obsidian中撰写书籍，以清单笔记作为目录，各章节为独立笔记的场景，方便将撰写内容导出成常见电子书和文档格式。
3. **核心特色**：仅支持桌面端，使用Pandoc进行导出，对于PDF导出推荐使用Typst引擎，无需安装LaTeX。导出前需配置输出文件夹，临时文件存于系统临时目录，不影响库和插件文件夹。
4. **使用建议**：先打开想用作书籍清单的Markdown笔记，在前置元数据中添加书籍信息，用标题和带维基链接的列表构建结构。然后从命令面板运行“导出当前书籍为EPUB / PDF / 所有格式”命令。注意要提前在设置里配置好默认输出文件夹的绝对路径。


> [!help] 
> 这篇插件文章还没有人贡献，欢迎占坑！
> 如果您有好的想法欢迎提交PR或者文末留言。
> 

---


