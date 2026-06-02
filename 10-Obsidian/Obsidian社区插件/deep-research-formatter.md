---
uid: 2026060213561375
title: 'Obsidian 插件：Deep Research Formatter'
tags: ['文字处理', '编辑工具', '数据处理', '自动化与AI', '第三方工具集成', 'obsidian插件']
description: '通过移除难以辨认的内联标记，对ChatGPT深度研究的Markdown导出内容进行规范化处理。'
author: AI
type: auto
draft: false
editable: false
modified: 20240101000000
---

# Obsidian 插件：Deep Research Formatter

> [!Note] 插件名片
> - 插件名称：Deep Research Formatter
> - 插件作者：Longxiao Zhang
> - 插件说明：通过移除难以辨认的内联标记，对ChatGPT深度研究的Markdown导出内容进行规范化处理。
> - 插件分类：['文字处理', '编辑工具', '数据处理', '自动化与AI', '第三方工具集成', 'obsidian插件']
> - 项目地址：[点我访问](https://github.com/zhanglongx/deep-research-formatter)
> - 国内下载地址：[下载安装](https://pkmer.cn/products/plugin/pluginMarket/?deep-research-formatter)
> - 自述文件：[Readme](https://ghproxy.net/https://raw.githubusercontent.com/zhanglongx/deep-research-formatter/master/README.md)



## 概述

### Deep Research Formatter插件总结
1. **主要功能**：清理从ChatGPT Deep Research导出的Markdown文件，去除或重写其中的内联标记，如移除`cite`标记和导出的`【...†...】`引用块，将`entity`和`url`标记替换为可读标签。
2. **适用场景**：适用于在Obsidian中处理从ChatGPT Deep Research导出的Markdown文档，使文档更易阅读。
3. **核心特色**：能安全处理未知标记类型，保留YAML前置元数据、代码块和内联代码，标记移除后仅进行最小程度的空格清理。
4. **使用建议**：安装前需确保Node.js 20或更高版本、npm 10或更高版本、Obsidian 1.5.0或更高版本。通过`npm install`安装依赖，`npm run build`进行构建，将`main.js`、`manifest.json`、`versions.json`复制到Obsidian插件目录，在设置中开启插件。开发时可使用`npm run dev`开启监听模式，`npm test`运行自动化测试。


> [!help] 
> 这篇插件文章还没有人贡献，欢迎占坑！
> 如果您有好的想法欢迎提交PR或者文末留言。
> 

---


