---
uid: 20231109234548
title: Thino 搜索
tags:
  - Obsidian
  - Obsidian插件
  - Thino
  - Memos
description: Thino 搜索
author: Bon,PKMer
type: other
draft: false
editable: false
modified: 20250122192841
id: ecf046de5cd170e4
---

# Thino 搜索

Thino 的搜索目前仅支持纯文本的搜索，当你搜索以后，会触发全局的 Thino 卡片的筛选，这个搜索以后的变化会体现在下方的 Thino 列表的卡片数量的变化，变化前后你会留意到在编辑器与 Thino 列表之间出现一个筛选器列表。

![Thino 搜索](https://cdn.pkmer.cn/images/Pasted%20image%2020231109091704.png!pkmer)

当你点击 Filter 中的搜索按钮的时候，会取消当前的搜索框的搜索；默认情况下，搜索框中的文本不会随着搜索取消而被删除，当你继续输入，或者在搜索框中按下回车键的时候，能触发重新搜索。

## 筛选器入口

当你悬浮至搜索框时，其自带的几个常用检索会出现在你的眼前，

![Thino 搜索](https://cdn.pkmer.cn/images/Pasted%20image%2020231109093657.png!pkmer)

其包括：

- 有链接 -> 注意，这里的有链接指的是有 Thino 的内部链接，而非常规理解的超链，可以理解成内部链接 `[[]]`；
- 无标签 -> 如字面意思，会将所有不带有标签的 Thino 卡片给一并筛选出来；
- 有超链接 -> 当 Thino 中存在有 http 或者 https 之类协议开头的超链接的时候，会被筛选出来，可以理解成 ` []()`；
- 有图片 -> 如字面意思指包含图片的内容

这些快捷入口能帮你节省敲检索式的时间。

### 检索范围

- 搜索不检索已经归档的内容
- 搜索不检索赢删除到回收站的内容

## 进阶用法

在 Thino 的搜索中包含了一个特殊的检索符：`-time:` 当你在输入框前输入任意的搜索内容后，只要在后边加上 `-time: `（注意 `:` 是英文的冒号，且后边需要接上一个空格），而后你输入两个用空格分隔的日期后，就会自动触发日期检索，例如 `12 -time: 2023-10-22 2023-10-28` 会触发 Thino 筛选从 2023-10-22 至 2023-10-29（之前）的所有带有 12 内容的 Thino。

其它更进阶的使用方法请查看 [[Thino Filters|检索式（筛选）]]

### 批量处理

> [!note] 功能信息
> 此功能仅需 Thino 2.3.12 及以上

针对已经筛选，或者快速搜索出来的内容，可以进行批量操作

![image.png|250](https://cdn.pkmer.cn/images/20240322094112.png!pkmer)

### 批量归档

可以针对筛选出来的内容，进行快速归档，所有内容会直接进入 [[Thino Archive|归档]] 中

### 批量删除

可以针对筛选出来的内容，进行快速归档，所有内容会直接进入 [[Thino Trash Bin|回收站]] 中

> [!Warning] 注意
> 回收站有直接删除模式，如果开启直接删除模式的用户，请在批量操作前，仔细检查。

### 批量标签编辑

> [!note] 功能信息
> 此功能仅需 Thino 2.3.12 及以上且依赖 Pro

- 可以针对已有标签进行删除操作，点击即为想要去掉某个标签
- 针对内容进行新增标签操作

![image.png|300](https://cdn.pkmer.cn/images/20240322095424.png!pkmer)
