---
uid: 20260223234213
title: Obsidian Weekly 2026-02-22：Obsidian v1.12.2 内测版已发布！附件可随文件一同删除啦~
tags: [Weekly, Obsidian]
description: Obsidian Weekly 2026-02-22：Obsidian v1.12.2 内测版已发布！附件可随文件一同删除啦~
author: 淡水鱼,PKMer
type: other
draft: false
editable: false
modified: 20260223234338
---

# Obsidian Weekly 2026-02-22：Obsidian v1.12.2 内测版已发布！附件可随文件一同删除啦~

> [!Abstract]
> **统计时间**：2026-02-08 21:00 ~ 2026-02-22 21:00
> **声明**：本栏目灵感来源于 _Eleanor Konik_ 女士于 2021 年 4 月至 2023 年 6 月期间写作发表的一系列 [Obsidian Roundup](https://www.eleanorkonik.com/tag/roundup/) 文章，如有兴趣可关注原作者的个人网站 [Obsidian Iceberg](https://www.eleanorkonik.com/)；内容来源于 Obsidian 官方 Discord 频道和相应项目在 Github 或其独立网站上的信息。描述中可能存在基于个人理解进行的修改，如有错谬欢迎指正。感谢 Obsidian 团队为我们带来如此优秀的软件。

## 官方资讯

### Obsidian v1.12.2 内测版已发布

#### V1.12.0 桌面端

##### 新增功能

* 新增了 [命令行界面](https://help.obsidian.md/cli)，让你能够通过终端控制 Obsidian，用于脚本编写、自动化以及与外部工具集成。
* 在数据库中新增了一个搜索工具栏按钮，用于筛选查询结果。
* 删除文件时，新增的提示会询问是否同时删除其附件。**文件与链接**中的新设置项允许你配置此行为（可选择“总是”、“每次询问”或“从不”）。
* 现在可以在实时预览中通过拖动图片角来调整图片大小。双击角点可将图片大小重置为原始尺寸。

##### 已改进

###### 数据库

* 当选中单个文件时，表格单元格右键菜单现在会显示文件菜单。

###### 文件管理器

* 现支持使用 `Ctrl-C/Ctrl-V` 进行复制和粘贴操作。

###### 编辑器

* 在编辑器旁边的空白区域右键单击时，新增了以下菜单项：
    * 切换行号显示
    * 切换行内标题显示
* 修复了引用块后缺少空格的问题。
* 修复了加粗链接的样式问题。
* 拖动链接时，图片大小不再被视为显示文本。

###### 其他

* 现在可以检测到白板文件中的反向链接。它们将显示在反向链接视图中，并在图谱视图中计为链接。
* “切换库…”已重命名为“管理库”。
* 新增了“切换库…”命令，可通过键盘快速在库之间切换。
* 新增了“打开库…”命令，可通过键盘打开现有库，同时保持当前库打开。
* 在文件管理器中，按住 Alt 键单击文件现在会将上一个活动项目添加到选区中。
* 快速切换器：现在支持将搜索结果拖出模态框。
* 新增了应用翻译。

##### 已修复

* **钥匙串**：增加了对某些 Linux 机器上加密功能不可用情况的处理。
* 修复了应用关闭时布局并非总能被保存的问题。
* 修复了在链接或标签附近选择文本时会错误触发链接或标签标记的问题。
* 修复了关闭带有活动通知的弹出窗口会导致通知转移到主窗口且永不消失的问题。
* 新增了 `unique` [URI 操作](https://help.obsidian.md/Extending+Obsidian/Obsidian+URI)。

##### 开发者相关

* 我们更新了翻译文件的创建方式以及与应用的打包方式。对于译者，请参阅 [我们翻译库中的更新说明](https://github.com/obsidianmd/obsidian-translations)。
* 增加了使用 `corner-shape` CSS 属性为角部形状提供主题支持。替换了 `-electron-corner-smoothing`。需要 Chromium 139 和 Obsidian 1.11 以上版本。
* **macOS**：新增了 `traffic-lights-offset-x` 和 `--traffic-lights-offset-y` CSS 变量，用于配置窗口框架中交通灯按钮的位置。
* 我们对 `BaseOption#shouldHide` 引入了一个破坏性的 API 变更。此函数不再接收配置作为参数。选项应通过 `BasesViewRegistration.options` 访问。

```ts
registerView('my-view-id', {
		name: 'View Name',
		icon: 'my-icon',
		factory: () => new MyView(),
		options: (config: BasesViewConfig) => ({
			// 配置在此处
		})
});
```

#### V1.12.0 移动端

##### 已改进

* 应用现在默认使用系统语言，并在首次启动引导过程中包含语言选择器。
* 新增了“创建唯一笔记”应用快捷操作（长按应用图标出现的菜单）。

##### 已修复

* 从文件删除提示中移除了“删除且不再询问”选项。
* **Obsidian 同步**：修复了在 Obsidian 保存最新同步状态之前关闭应用，导致文件被覆盖的问题。

#### V1.12.1 桌面端

##### 已修复

* 修复了当设备语言不是英语时，语言选择器不允许你选择“英语”的问题。
* **CLI**：如果包含库参数，它必须是第一个参数。
* 尝试打开应用的第二个实例（例如从 Windows 任务栏）现在将再次打开库启动器。
* **实时预览**：修复了 SVG 无法渲染的问题。
* `daily:prepend` CLI 命令现在将内容插入到 Frontmatter 之后，而非文件的最开头。

#### V1.12.1 移动端

* 包含了截至 Obsidian 桌面版 v1.12.1 的所有新功能和错误修复。

#### V1.12.2 桌面端

##### 已改进

###### CLI

* 新增了 `help <command>` 以获取特定命令的帮助信息。
* 新增了 `--help` 作为 `help` 命令的别名。
* 新增了 `daily:path` 命令，用于获取预期的每日笔记路径。
* 新增了 [`rename`](https://help.obsidian.md/cli#%60rename%60) 命令。
* 将 `search` 命令拆分为 `search` 和 [`search:context`](https://help.obsidian.md/cli#%60search+context%60)。
* 在帮助输出中为筛选参数添加了描述。
* CLI 命令现在默认以静默模式运行，且默认不期望有活动文件。
    * `all` 参数已被 `active` 取代（用于定位活动文件）
    * `silent` 参数已被 `open` 取代，用于打开目标
* CLI 现在会忽略以 `--` 开头的无法识别的标志。
* 将 CLI 设置中的取消按钮文字改为“跳过”，以表明该步骤是可选的。

###### 数据库

* 增加了通过拖放将文件导入数据库的功能。
* `file.linksTo()` 现在会将嵌入在白板中的文件视为链接。

###### 其他

* 在图片上右键单击时，新增了“复制图片”菜单项。
* 从编辑器复制文本时，现在会包含 HTML 格式，使其更容易粘贴到 Google Docs 等应用中。
* **Obsidian 同步**：现在会记录因文件过大而被跳过的文件信息。
* 改进了当查询包含空格时的模糊搜索结果。
* 在外部应用程序中打开文件时，现在会显示确认对话框以增加安全性。
* 尝试打开可执行文件时新增了警告提示。

##### 已修复

* 修复了通知在关闭后不再出现的错误。
* 修复了输入时大纲视图闪烁的问题。
* 修复了在数据库表格视图中更改行高后滚动位置未更新的问题。
* **数据库**：修复了搜索输入文本过长时与结果计数重叠的问题。
* 修复了在弹出窗口中点击“…”按钮时，“更多选项”菜单无法关闭的问题。
* 修复了应用重启有时会使其陷入异常退出状态的问题。
* 修复了如果未启用 CLI，`obsidian://` URI 无法工作的问题。
* 修复了右键单击列表项内的链接时，列表属性的右键菜单中不显示编辑和移除选项的问题。
* **CLI**：修复了命令无法处理 Unicode 字符的问题。
* **CLI**：修复了粘贴功能。
* **CLI**：修复了工作区加载完成前命令就运行的问题。
* **CLI**：修复了当指定的库未找到时，会错误地对当前库进行操作的问题。
* **CLI**：修复了在 Windows 上包含冒号的参数无法被正确处理的问题。
* **macOS**：CLI 调用期间不再显示 Dock 图标。

##### 开发者相关

* 如果你的主题或 CSS 片段使用新的 CSS 变量更新了 macOS 交通灯按钮的位置，这些偏移量现在会在应用加载时立即应用。

#### V1.12.2 移动端

* 包含了截至 Obsidian 桌面版 v1.12.2 的所有新功能和错误修复。

##### 新增功能

* **iOS**：新增了对原生分享菜单的支持。
* **iOS**：新的快捷指令操作“书签链接”，可将 URL 保存为 Obsidian 书签。

##### 已改进

* 改进了对平板设备上指针设备（例如妙控板）的支持：
    * 子菜单现在悬停时展开
    * 属性编辑器右键菜单在右键单击时显示。

##### 已修复

* **iOS**：修复了与侧边栏项目交互后有时会出现工具提示的问题。

## 插件新闻

### 社区插件



#### 新增

[Table Line Break Mobile](https://obsidian.md/plugins?id=table-line-break) By _marcelflymark_

> 通过快捷键或工具栏在移动设备上的表格中插入换行符 `<br>`。

[Source Mode Styling](https://obsidian.md/plugins?id=sourcemode-styling) By _Chris Howard_

> 在源码视图下提供可自定义的原始外观，使用单宽字体，以明显区别于实时预览。

![Weekly-2026-02-22-Pasted image 20260223205955|650](https://cdn.pkmer.cn/images/Weekly-2026-02-22-Pasted%20image%2020260223205955.png!pkmer)

![Weekly-2026-02-22-Pasted image 20260223210013|650](https://cdn.pkmer.cn/images/Weekly-2026-02-22-Pasted%20image%2020260223210013.png!pkmer)

[Floating Headings](https://obsidian.md/plugins?id=floating-headings) By _k0src_

> 在编辑器侧面显示一个浮动、可折叠的笔记标题大纲（类似 Notion 风格）。

![Weekly-2026-02-22-Pasted image 20260223210329|650](https://cdn.pkmer.cn/images/Weekly-2026-02-22-Pasted%20image%2020260223210329.png!pkmer)

[Decks](https://obsidian.md/plugins?id=decks) By _Xherdi Lika_

> 一个基于 FSRS 算法的间隔重复记忆卡片插件，助你在 Obsidian 中学习和记忆信息。

[Blueprint](https://obsidian.md/plugins?id=blueprint) By _François Vaux_

> Blueprint 是一款 Obsidian 模板插件。它让你能够强制执行每篇笔记的模板，支持 Frontmatter 属性插值、无损的连续应用等功能！Blueprint 模板使用 Nunjucks 模板引擎，并额外增加了功能。

[Typst Mate](https://obsidian.md/plugins?id=typst-mate) By _azyarashi_

> 用 [Typst](https://typst.app/) 代替 MathJax 在 [Obsidian](https://obsidian.md/) 中渲染数学表达式。

![Weekly-2026-02-22-Pasted image 20260223212212|650](https://cdn.pkmer.cn/images/Weekly-2026-02-22-Pasted%20image%2020260223212212.png!pkmer)

[Pandoc Extended Markdown](https://obsidian.md/plugins?id=pandoc-extended-markdown) By _ErrorTzy_

> 这款插件能让 Obsidian 渲染 [Pandoc扩展Markdown语法](https://pandoc.org/MANUAL.html#pandocs-markdown)，为你的笔记带来包括高级列表、上标、下标等在内的强大格式化功能。

[Mermaid Icons](https://obsidian.md/plugins?id=mermaid-icons) By _toshs_

> 在你的美人鱼图里使用 Font Awesome 和其他图标集。

![Weekly-2026-02-22-Pasted image 20260223221756|650](https://cdn.pkmer.cn/images/Weekly-2026-02-22-Pasted%20image%2020260223221756.png!pkmer)

[Hardcover](https://obsidian.md/plugins?id=hardcover) By _aliceinwaterdeep_

> 将你的 [Hardcover](https://hardcover.app/) 图书馆同步到 Obsidian 库

[Anki Helper](https://obsidian.md/plugins?id=anki-helper) By _Dusk_

> 一个与 obsidian_to_anki 配合使用的增强插件，围绕“用标题做题干、标题下文本做答案”的工作流，提供更顺手的制卡体验：自动插入牌组信息、生成标题级回链、清理标题字符、整理列表空行、快速进行 Cloze（填空）标记转换，并支持按路径控制作用范围。内置中英文设置界面与用于 obsidian_to_anki 的正则生成器。

## PKM 相关知识推荐

> [!INFO]
> 欢迎收藏 [PKMer 导航页](https://pkmer.cn/link/)，一键直通 PKMer 各社交平台账号，与热爱分享与知识管理的同好们交流，第一时间获取行业新鲜资讯！

[我写了个插件，一键从 Obsidian 发布到公众号后台]( https://pkmer.cn/show/8162 )

能自定义主题且能一键发布到公众号后台，省却无意义劳动。

> [!Warning] 声明
> 本栏目致力于为广大 Obsidian 中文用户汇总全面的官方资讯与插件、外观动态。为了保持信息的全面性，我们的**收录并不等同于推荐**，还请各位用户知悉并理解，根据自身需求进行判断和选择。
