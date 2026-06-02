---
uid: 1780392511236000
title: 'Obsidian 插件：Liuyao'
tags: ['图表与可视化', '编程与脚本', '效率工具', 'obsidian插件']
description: '它可以从代码块中绘制六爻卦象。'
author: AI
type: auto
draft: false
editable: false
modified: 20240101000000
---

# Obsidian 插件：Liuyao

> [!Note] 插件名片
> - 插件名称：Liuyao
> - 插件作者：Kasukabe Tsumugi
> - 插件说明：它可以从代码块中绘制六爻卦象。
> - 插件分类：['图表与可视化', '编程与脚本', '效率工具', 'obsidian插件']
> - 项目地址：[点我访问](https://github.com/baendlorel/obsidian-liuyao)
> - 国内下载地址：[下载安装](https://pkmer.cn/products/plugin/pluginMarket/?liuyao)
> - 自述文件：[Readme](https://ghproxy.net/https://raw.githubusercontent.com/baendlorel/obsidian-liuyao/master/README.md)



## 概述

### 主要功能
Liuyao 是一款 Obsidian 插件，可从 fenced `liuyao` 代码块渲染六爻卦象。支持输入 6 位数字或 6 个卦名来生成卦象，还可在首行添加日期信息。

### 适用场景
适用于对六爻占卜感兴趣，希望在 Obsidian 中记录和查看六爻卦象的用户。

### 核心特色
- 支持多种输入格式，包括 6 位特定数字（0 - 3）和 6 个卦名。
- 若提供有效日期，渲染卡片会显示六神。
- 能展示卦的家族和名称、每爻的关系文本，以及“世”“应”标记。

### 使用建议
- 输入需为 6 位数字，且每位数字只能是 0、1、2、3 之一，首位为初爻，末位为上爻。
- 若要添加日期，将其置于首行，卦象输入置于第二行。
- 开发时，先执行 `pnpm install` 安装依赖，再用 `pnpm build` 构建插件，将生成的三个文件复制到 `.obsidian/plugins/liuyao/` 目录。


> [!help] 
> 这篇插件文章还没有人贡献，欢迎占坑！
> 如果您有好的想法欢迎提交PR或者文末留言。
> 

---


