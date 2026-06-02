---
uid: 1780392511208001
title: 'Obsidian 插件：KOHi'
tags: ['第三方工具集成', '数据处理', '学习与教育', '效率工具', 'obsidian插件']
description: '这个插件还没经过Obsidian官方人员的人工审核。可以把KOReader的高亮内容和笔记导入到你的仓库里。'
author: AI
type: auto
draft: false
editable: false
modified: 20240101000000
---

# Obsidian 插件：KOHi

> [!Note] 插件名片
> - 插件名称：KOHi
> - 插件作者：chiahsien
> - 插件说明：这个插件还没经过Obsidian官方人员的人工审核。可以把KOReader的高亮内容和笔记导入到你的仓库里。
> - 插件分类：['第三方工具集成', '数据处理', '学习与教育', '效率工具', 'obsidian插件']
> - 项目地址：[点我访问](https://github.com/chiahsien/obsidian-kohi)
> - 国内下载地址：[下载安装](https://pkmer.cn/products/plugin/pluginMarket/?kohi)
> - 自述文件：[Readme](https://ghproxy.net/https://raw.githubusercontent.com/chiahsien/obsidian-kohi/master/README.md)

![KOHi](https://cdn.pkmer.cn/covers/kohi_internal_0.png!pkmer)

## 概述

### KOHi插件总结
1. **主要功能**：将KOReader中的高亮和笔记导入到Obsidian库中。扫描KOReader设备的`.sdr`元数据目录，解析Lua序列化注释，为每本书生成一个Markdown笔记。
2. **适用场景**：适合使用KOReader阅读书籍并希望将阅读过程中的高亮和笔记整理到Obsidian进行知识管理的用户。
3. **核心特色**：
    - 自动检测KOReader的3种存储模式。
    - 支持基于Nunjucks的自定义模板，可控制输出格式。
    - 可选择性导入，能全量导入或通过模糊搜索选择特定书籍导入。
    - 自动清理文件名中的非法字符。
    - 重新导入时可覆盖已有笔记，行为简单可预测。
4. **使用建议**：先通过USB连接KOReader设备，在Obsidian设置中设置挂载路径，然后通过命令面板选择“KOHi: Import all highlights”或“KOHi: Import selected highlights”进行导入，生成的笔记会出现在配置的输出文件夹中。


> [!help] 
> 这篇插件文章还没有人贡献，欢迎占坑！
> 如果您有好的想法欢迎提交PR或者文末留言。
> 

---


