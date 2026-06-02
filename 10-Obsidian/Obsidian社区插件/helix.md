---
uid: 1780392511152001
title: 'Obsidian 插件：Helix Keybindings'
tags: ['编辑工具', '快捷键', '文字处理', '效率工具', 'obsidian插件']
description: '编辑时可使用Helix键位绑定。'
author: AI
type: auto
draft: false
editable: false
modified: 20240101000000
---

# Obsidian 插件：Helix Keybindings

> [!Note] 插件名片
> - 插件名称：Helix Keybindings
> - 插件作者：obsidian-helix
> - 插件说明：编辑时可使用Helix键位绑定。
> - 插件分类：['编辑工具', '快捷键', '文字处理', '效率工具', 'obsidian插件']
> - 项目地址：[点我访问](https://github.com/obsidian-helix/obsidian-helix)
> - 国内下载地址：[下载安装](https://pkmer.cn/products/plugin/pluginMarket/?helix)
> - 自述文件：[Readme](https://ghproxy.net/https://raw.githubusercontent.com/obsidian-helix/obsidian-helix/master/README.md)



## 概述

### Helix Keybindings插件总结
1. **主要功能**：该插件借助 [Helix CodeMirror6 extension by jrvidal](https://gitlab.com/_rvidal/codemirror-helix)，让 [Obsidian.md](https://obsidian.md/) 支持 [Helix](https://helix-editor.com/) 键位绑定。
2. **适用场景**：适用于习惯Helix编辑器键位操作，且希望在Obsidian编辑时延续该操作习惯的用户。
3. **核心特色**：简单地将Helix扩展添加到Obsidian编辑器中，核心功能实现归功于[jrvidal](https://github.com/jrvidal)。不过CM6扩展尚处于早期开发阶段。
4. **使用建议**：
    - 安装：可像安装其他社区插件一样，从官方插件列表（https://community.obsidian.md/plugins/helix）安装并启用。
    - 使用：先在 `Options->Editor->Advanced` 中禁用Vim键位绑定，然后在插件设置里启用Helix键位绑定，也可通过命令切换。
    - 自定义：默认光标颜色为强调色，可通过创建自定义CSS片段更改，如设置为红色：
```css
.cm-hx-block-cursor .cm-hx-cursor {
  background: red !important;
}
```


> [!help] 
> 这篇插件文章还没有人贡献，欢迎占坑！
> 如果您有好的想法欢迎提交PR或者文末留言。
> 

---


