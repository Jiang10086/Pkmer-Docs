---
uid: 20260603002009
title: Obsidian Weekly 2026-05-31：史诗级更新前瞻！设置改在新窗口打开&全局设置搜索实装
tags: [Weekly, Obsidian]
description: Obsidian Weekly 2026-05-31：史诗级更新前瞻！设置改在新窗口打开&全局设置搜索实装
author: 淡水鱼,熊猫别熬夜,PKMer
type: other
draft: false
editable: false
modified: 20260603002043
---

# Obsidian Weekly 2026-05-31：史诗级更新前瞻！设置改在新窗口打开&全局设置搜索实装

> [!Abstract]
> **统计时间**：2026-021:00 ~ 2026-021:00
> **声明**：本栏目灵感来源于 _Eleanor Konik_ 女士于 2021 年 4 月至 2023 年 6 月期间写作发表的一系列 [Obsidian Roundup](https://www.eleanorkonik.com/tag/roundup/) 文章，如有兴趣可关注原作者的个人网站 [Obsidian Iceberg](https://www.eleanorkonik.com/)；内容来源于 Obsidian 官方 Discord 频道和相应项目在 Github 或其独立网站上的信息。描述中可能存在基于个人理解进行的修改，如有错谬欢迎指正。感谢 Obsidian 团队为我们带来如此优秀的软件。

## 官方资讯

### Obsidian v1.13.0 内测版现已发布

#### 桌面端

##### 新增

###### 设置

- 设置项现在会在新窗口中打开。你可以在“设置 → 界面”中关闭此功能。
- 添加了搜索功能。现在你可以按名称或描述搜索设置项。目前支持核心设置和核心插件。社区插件可迁移至新版设置 API 以出现在搜索结果中。
- 添加了键盘导航。使用方向键在项目间移动，按 Enter 打开设置选项卡，按 Ctrl/Cmd-F 重新聚焦搜索。同时支持 Vim 按键绑定。
- 部分设置已移至新的“界面”设置页面。多个设置页面已重新设计以改善导航。
- 增加了在不重新启用插件的情况下退出受限模式的功能。有助于调试你的库。

###### 安全性

- Obsidian URI 现在在执行操作前会显示确认对话框。选择“不再询问”可将该操作加入允许列表。允许列表可在设置中管理。
- 当资源来源指向网络驱动器时，尝试加载 HTML 资源前会显示警告。
- 选择通过 Obsidian Sync 同步插件时会增加警告对话框。

###### 其他

- 为“书签”视图添加了搜索功能。
- 新增一次性横幅，确认你想在库中渲染 Mermaid 代码块。
- 在桌面上，将文件夹拖入应用时会导入整个文件夹并保留目录结构。

##### 改进

###### 通用

- 现在所有平台上都支持使用 Ctrl-N 和 Ctrl-P 在建议列表中导航到上一项/下一项。
- 更新了打开已安装插件的未识别库时显示的对话框。优化了措辞以强调使用不受信任插件的风险。

###### 编辑器

- 实时预览：处理图像时的全新编辑器体验。现在可以通过键盘选择图像，并且图像不再自动展开显示文件名。选中图像后，按退格键或删除键可删除图像，按 Ctrl/Cmd-C / Ctrl/Cmd-X 可复制或剪切图像。同时也开箱即用地支持 Vim。
- 笔记重组：从文件中提取章节时，该章节中的链接将被重写为相对于新位置的链接。

###### 文件浏览器

- 按“Escape”取消文件重命名后，文件浏览器仍保持聚焦。
- 按“Escape”会清除当前选择。
- 重命名文件或文件夹时，“自动显示”将不再触发。
- 拖放行为小幅改进。

###### 属性

- 改进了全局属性视图中的键盘导航，按退格键可删除选中的属性。
- 属性菜单现在可区分某属性是否为自动类型分配。

###### Obsidian Sync

- 移除了状态栏图标的旋转动画，因为它在应用空闲时会影响电池续航。
- 同步视图中的文件现在会在上下文菜单中显示所有与文件相关的项目。
- 同步侧边栏视图中的文件现在可以拖放到其他视图或编辑器中。
- 为同步侧边栏视图添加了搜索菜单项。

###### macOS

- 更新了按钮和输入样式，以更好地匹配 macOS 26 的默认样式。

###### 白板

- 小幅渲染性能改进。

###### 其他

- 使用 Escape 键关闭快速切换器或命令面板后，现在能正确恢复之前的选中项。
- 按 Escape 键现在会隐藏侧边栏视图中的搜索输入框。
- 禁用代码片段后，该片段会从所有弹出窗口中移除。

##### 修复

- 修复了点击弹出窗口中的外部链接导致弹出窗口关闭的问题。
- 修复了桌面端功能栏按钮不响应触摸事件的问题。
- 修复了禁用 CSS 代码片段后，它们仍然应用于弹出窗口的问题。
- 文件浏览器：修复了将文件移动到新文件夹后，文件临时显示为错误缩进级别的罕见问题。
- 实时预览：修复了在嵌入的输入框（如嵌入式数据库表格中的单元格）中 Ctrl/Cmd-A 不起作用的问题。
- 属性：修复了全局属性视图不总是保存排序顺序的问题。
- 属性：修复了当属性名称包含大写字母时，“删除属性”菜单项无法可靠工作的问题。
- 属性：修复了“打开光标下的链接”热键在列表属性项上无效的问题。
- 数据库：修复了禁用并重新启用数据库核心插件时出现错误消息的问题。
- 数据库：修复了数字属性的自动列宽问题。

##### 开发者

- 新版设置 API 的文档和迁移指南。
- 添加了新的 ConfirmationModal 组件。
- CodeMirror 已升级。
- 基础颜色已迁移至 OKLCH 色彩空间。
- `--callout-color` 变量现在需要一个有效的 CSS 颜色值。这是一个破坏性变更：

```css
/* 之前，callout 颜色需要 RGB 三元组 */
--callout-color: 255,0,0;

/* 现在，任何有效的 CSS 颜色值均可 */
--callout-color: #ff0000;
--callout-color: rgb(255,0,0);
```

###### CLI

- 修复了 flatpak 安装中的 Obsidian CLI。

###### 第三方库

- 升级 Moment.js 至 2.30.1。
- 升级 Mermaid 至 11.13.0。

#### 移动端

_包含直至 Obsidian Desktop v1.13.0 的所有新功能和错误修复。_

##### 新增

- iOS：新增可配置位置的共享扩展面板。配置位置可以指向你任何库中的不同目标。
- iOS：共享扩展面板现在支持复制网页的完整内容，以及来自 YouTube 和社交网络等应用的内容。
- 现在可以在标签页切换器中重新排序标签页。滑动以关闭标签页。
- 平板：长按可调整分割区域和固定的侧边栏。
- 数据库：新增表格视图中调整列宽的菜单项。

##### 修复

- iOS：修复了在非英语设备上“删除文件”后不更新应用界面的问题。
- iOS：修复了更改设置值后设置页面滚动回顶部的问题。
- 修复了打开侧边栏时，搜索视图中的输入框有时会自动聚焦的问题。

##### 开发者

- 我们将最低 iOS 版本从 iOS 14.5 提升至 iOS 15。这不会影响任何受支持的设备。

## 插件新闻

### 社区插件

#### 新增

> [!Tip]
> 由于 AI 审核的引入，近期上架插件数量出现爆炸式增长，编者目前精力有限，故仅能选择性收录并简单介绍，详情可前往新版插件页面 [Obsidian Community](https://community.obsidian.md/) 获取。

##### 🤖 AI 与智能助手

- [Reasonian](https://obsidian.md/plugins?id=reasonian) By _reject-reality_

> 将 Reasonix (DeepSeek) 作为 AI 协作者嵌入你的库。具备完整的代理能力：文件读写、搜索、bash 命令以及多步骤工作流。

- [Copilot Personal](https://obsidian.md/plugins?id=copilot-personal) By _josefbelzer_

> 拥有 17 个工具、多提供商 LLM（11 个提供商）、RAG 语义搜索、PDF 提取、网页搜索和自主笔记创建的 AI 代理。

- [Copilot Auto Completion Plus](https://obsidian.md/plugins?id=copilot-auto-completion-plus) By _yetanotherrepo_

> 使用 OpenAI、Anthropic、Gemini、Azure OpenAI 或 Ollama 为 Obsidian 添加可配置的 AI 自动补全。

- [Auto LLM Wiki](https://obsidian.md/plugins?id=auto-llm-wiki) By _youzhixiaomutou_

> 通过 AI 辅助的摄入、查询、检查以及可预览的文件更改，维护一个 Karpathy 风格的大模型 Wiki。

- [InkPilot](https://obsidian.md/plugins?id=inkpilot) By _nicholas-yu_

> 借助 AI 辅助生成小说。管理角色、伏笔、世界构建和大纲。AI 完成 80% 的写作，你注入灵魂。

- [Literature Review Synthesizer](https://obsidian.md/plugins?id=literature-review-synthesizer) By _ibrh96-prog_

> 使用大模型将你的学术阅读笔记转化为结构化的文献综述输出。

- [Vir](https://obsidian.md/plugins?id=vir) By _djolex999_

> 在 Obsidian 侧边栏中为 Claude Code 提供大模型 Wiki。在工作时从你提炼的会话知识中浮现相关笔记。

- [Claude Code Bridge](https://obsidian.md/plugins?id=claude-code-bridge) By _radical7vii_

> 将选中的文本桥接到 Claude Code CLI，实现实时上下文共享。

- [WiseMindAI](https://obsidian.md/plugins?id=wisemindai) By _chris_

> 在本地利用 WiseMindAI 的摘要、知识卡片、AI 对话和双向同步功能。

- [Context Prism](https://obsidian.md/plugins?id=context-prism) By _stefanimp_

> 为 Obsidian 中的 AI 工作流提供多语言上下文路由。

- [Semantic Todoist Sync](https://obsidian.md/plugins?id=semantic-todoist-sync) By _neurocloud-activate_

> 自带密钥的语义/AI 库 搜索，Gemini/OpenAI 辅助的 Todoist 任务生成，使用笔记到 Todoist 和邮件到 Todoist（可选）工作流。

- [Local REST API Second Brain MCP Extension](https://obsidian.md/plugins?id=local-rest-api-second-brain-mcp-extension) By _ziadloo_

> 为本地 REST API 添加第二大脑 MCP 服务器的扩展。

- [DyResearch AI Sidecar](https://obsidian.md/plugins?id=dyresearch-sidecar) By _dylantartarini1996_

> 连接到基于 Google ADK 构建的 DyResearch 代理系统。

- [Pickle](https://obsidian.md/plugins?id=pickle) By _callumalpass_

> 本地优先、基于文件的代理收件箱，用于键入请求和响应。

- [Smart Review](https://obsidian.md/plugins?id=smart-review) By _jaycelu_

> 基于 Obsidian 属性 / YAML frontmatter 的智能复习系统，带有复习中心、间隔复习反馈、历史记录和 AI 有效载荷导出。

##### ✅ 任务与项目管理

- [Routine Streaks](https://obsidian.md/plugins?id=routine-streaks) By _holyhooly_

> 从标记的日记任务中追踪常规连续记录。

- [Simple Checklist](https://obsidian.md/plugins?id=simple-checklist) By _l-4553_

> 侧边面板显示整个库 中所有未完成的待办事项。

- [Checkers Hider](https://obsidian.md/plugins?id=checkers-hider) By _mr-asa_

> 在 Obsidian 中隐藏或显示已完成和自定义状态的清单项。

- [Context Nine](https://obsidian.md/plugins?id=context-nine) By _mderman_

> 任务笔记捕获、上下文路由、Vault 命令驾驶舱和附件清理工具。

- [Plan Panel](https://obsidian.md/plugins?id=plan-panel) By _xuhuaya0_

> 按艾森豪威尔象限显示和分类 Markdown 计划。

- [AgentBoard](https://obsidian.md/plugins?id=agent-board) By _aniruddh-jammoria_

> 一个与 Markdown 待办文件同步的可视化看板。可在看板上或通过 AI 代理编辑任务——更改即时反映在两侧。

- [Kandyban](https://obsidian.md/plugins?id=kandyban) By _dseaman_

> 基于 Markdown 的项目待办事项和里程碑的看板视图。直接读取粗体键元数据，允许在状态列之间拖拽卡片，行内编辑枚举，并将更改写回。

- [Kanban Archiver](https://obsidian.md/plugins?id=kanban-archiver) By _eiger3970_

> 将超过可配置天数的已完成看板卡片归档到单独的归档文件。自动记录完成日期，以便卡片始终可归档。

- [Sidebar Timer](https://obsidian.md/plugins?id=sidebar-timer) By _hornatx_

> 一个极简的浮动胶囊计时器，支持自定义时长、通知消息和拖拽位置保存。

- [Projects Planner](https://obsidian.md/plugins?id=projects-manager) By _wesswart77_

> 在纯 Markdown 中管理项目：通过看板风格的侧边栏视图跟踪状态、里程碑、任务和进度。

- [Meeting Notes Plus](https://obsidian.md/plugins?id=meeting-notes-plus) By _wesswart77_

> 一个会议笔记系统：捕获与会者、议程、决策和行动项，并自动提取。

- [Freelance Manager](https://obsidian.md/plugins?id=freelance-manager) By _wesswart77_

> 管理自由职业的客户、项目、时间日志和发票。纯 Markdown，无需外部服务。

- [Job Search Tracker](https://obsidian.md/plugins?id=job-search-tracker) By _wesswart77_

> 在管道视图中跟踪求职申请：公司、职位、申请阶段、联系人和面试笔记。

- [Travel Planner](https://obsidian.md/plugins?id=travel-planner) By _wesswart77_

> 在 Obsidian 中规划旅行：行程、打包清单、住宿笔记和目的地页面。

- [Order Manager](https://obsidian.md/plugins?id=ordermanager) By _je-bh91_

> 为创业者提供的会计管理：客户、供应商、库存、交易和债务。

##### 📅 日历与时间管理

- [Calendar Heatmap](https://obsidian.md/plugins?id=calendar-heatmap) By _deemsd_

> 在日历热图中可视化日记和写作活动。

- [Date List](https://obsidian.md/plugins?id=date-list) By _lumargh_

> 快速添加一个格式化日期列表。

- [Calendar Hub](https://obsidian.md/plugins?id=calendar-hub) By _hwy1dot0_

> 无论笔记存放在哪个文件夹，都可以在一个日历视图中找到指定日期创建的所有笔记。

- [Daily Day Nav](https://obsidian.md/plugins?id=daily-day-nav) By _antoineart_

> 打开前一个或后一个日历日记，如果尚不存在，则从模板创建。

- [Mood Quarter Calendar](https://obsidian.md/plugins?id=mood-quarter-calendar) By _linglingcai0314_

> 一个 Markdown 优先的情绪日历，带有自定义 SVG 表情、标签/frontmatter 输入以及清晰的按季度年份布局。

- [Luna Notes](https://obsidian.md/plugins?id=luna-notes) By _maiaalex_

> Obsidian 的生理周期规划器。

- [Daily Journal Plus](https://obsidian.md/plugins?id=daily-journal-plus) By _wesswart77_

> 一个日常日记系统，包含情绪跟踪、习惯记录、连续计数器和轮换反思提示。

##### ✍️ 写作与编辑

- [Regex Css Highlighter](https://obsidian.md/plugins?id=regex-css-highlighter) By _dlsdgj_

> 正则匹配 + CSS 高亮，支持实时预览和即时生效。

- [Table Formatter](https://obsidian.md/plugins?id=table-formatter) By _fangface-hub_

> 在文件保存时格式化 Markdown 表格。

- [Cornell Notes](https://obsidian.md/plugins?id=cornell-notes) By _bytetiles_

> 渲染两栏的康奈尔笔记布局。

- [Draft Paper](https://obsidian.md/plugins?id=draft-paper) By _mikuloverfan_

> 全屏草稿本，允许直接在 Markdown 文件上进行手写批注。

- [Discord Export](https://obsidian.md/plugins?id=discord-export) By _malweis_

> 为将笔记发布到 Discord 做准备：添加段落缩进，去除 frontmatter 和标签，并分成 2,000 或 4,000 字符的块，带有复制按钮。

- [Colorez](https://obsidian.md/plugins?id=colorez) By _didacd_

> 使用 Obsidian 主题颜色更改文本颜色。

- [Rune Scribe](https://obsidian.md/plugins?id=runescribe) By _imhlq_

> 一本写作统计魔法书，用于英文和 CJK 字数统计、文件夹和频率分析。

- [Manuscript Outliner](https://obsidian.md/plugins?id=manuscript-outliner) By _joe-iq_

> 从 Markdown 标题生成大纲。通过状态标签和每节的字数跟踪进度。

- [Screenwriter](https://obsidian.md/plugins?id=screenwriter) By _wesswart77_

> 在纯 Markdown 中开发剧本：故事梗概、大纲、角色弧线、场景卡片和布莱克·斯奈德的 15 个节拍表。

- [Songwriter](https://obsidian.md/plugins?id=songwriter) By _wesswart77_

> 一个词曲作者的笔记本：歌词、和弦、歌曲结构、主题、影响和录音笔记。

- [World Builder](https://obsidian.md/plugins?id=world-builder) By _wesswart77_

> 一个虚构世界构建工具包：角色、地点、阵营、传说条目和时间线事件。

- [Novel Profile](https://obsidian.md/plugins?id=novel-profile) By _hornatx_

> 将原生属性区域转换为优雅的角色资料卡。

- [Knomo](https://obsidian.md/plugins?id=knomo) By _banyanso_

> Obsidian 的轻量级备忘录条目：快速捕获、每日上下文、月度合集和本地优先控制。

- [Seamless Embeds](https://obsidian.md/plugins?id=seamless-embeds) By _5krus_

> 使嵌入/转载的笔记在视觉上与周围文本融为一体。

##### 📊 可视化与图表

- [Simple Image Slider](https://obsidian.md/plugins?id=simple-image-slider) By _xinworks_

> 将 Obsidian 图片嵌入渲染为轻量级滑块并显示图片标题。

- [Mandala Chart](https://obsidian.md/plugins?id=mandala-chart) By _gurio318_

> 用于结构化目标规划的交互式 9×9 曼陀罗图表——灵感来自大谷翔平的方法。支持 Markdown、5 种语言和打印导出。

- [Cerebro Mycelium](https://obsidian.md/plugins?id=cerebro-mycelium) By _colorpulse6_

> 将你的库 渲染为动画的 2D 活体真菌网络。

- [Brain Atlas](https://obsidian.md/plugins?id=brain-atlas) By _colorpulse6_

> 将你的库 渲染为动画的 3D 解剖大脑。

- [FlowScript Diagrams](https://obsidian.md/plugins?id=flowscript-diagrams) By _kilrkrow_

> 使用 FlowScript 将 ```flow 代码块渲染为内联 SVG 流程图。

- [Mermaid Block to Image](https://obsidian.md/plugins?id=mermaid-block-to-image) By _jcmexdev_

> 将 Mermaid 代码块转换为静态图像 URL（SVG、PNG 或 WebP）。

- [Tag Lens](https://obsidian.md/plugins?id=tag-lens) By _laximgqozazzzyt_

> 轻量级标签隶属关系可视化：连接矩阵、标签共现热图、UpSet、二分标签图。

- [Folder Graph View](https://obsidian.md/plugins?id=folder-graph-view) By _codaloc_

> 用遵循文件夹结构的图谱取代由链接形成的图谱视图。

- [Spectacles Sync](https://obsidian.md/plugins?id=spectacles-sync) By _r3d5_

> 将你的库 同步到 Spectacles AR 眼镜，以 3D 知识图谱的形式探索笔记。

- [Gallery View Dashboard](https://obsidian.md/plugins?id=gallery-view-dashboard) By _kawecz_

> 将库 的目录结构转化为流线型的卡片视觉网格，带有回退横幅和交互式元数据。

- [Simple Mindmap](https://obsidian.md/plugins?id=obsimap) By _creative781_

> 一个强大的以键盘为中心的思维导图插件，支持双向链接。

- [TradingView Widget](https://obsidian.md/plugins?id=tradingview-widget) By _themanuelml_

> 打开一个可自定义的股票视图，显示由 TradingView 免费可嵌入小部件提供支持的图表和小部件（热图、滚动条、代码摘要、高级图表等）。

##### 🔁 同步与备份

- [Thoth](https://obsidian.md/plugins?id=thoth-sync) By _macahmed_

> 通过兼容 S3 的对象存储进行轻量级库 同步。

- [Google Calendar and Tasks Sync](https://obsidian.md/plugins?id=google-sync) By _cordedmink2_

> 将库 中的事件和任务文件夹同步到 Google 日历和 Google Tasks。

##### 📥 导入与导出

- [Echo Notes](https://obsidian.md/plugins?id=echo-notes) By _anbang278_

> 将库 中的音频文件转换为链接的 Markdown 转录稿。

- [YouTube Search](https://obsidian.md/plugins?id=youtube-search) By _plasch_

> 通过链接搜索 YouTube 视频，并自动创建带有视频元数据的笔记。

- [Advanced PDF Export](https://obsidian.md/plugins?id=advanced-pdf-export) By _shrekbytes_

> 将笔记导出为像素完美的 PDF，支持实时预览、样式预设、手动分页、表格和完全布局控制。

- [DOCX Importer](https://obsidian.md/plugins?id=docx-importer) By _mayac5_

> 将 DOCX 文件作为 Markdown 导入到你的 Obsidian 库。

- [DOCX Exporter Plus](https://obsidian.md/plugins?id=docx-exporter-plus) By _michellegdyason_

> 将 Markdown 笔记导出为 DOCX，带有 Word 标题导航、在白纸上可见的颜色和有效链接。

- [Word Reader](https://obsidian.md/plugins?id=word-reader) By _shiva_

> 在 Obsidian 内以安全、只读文档的形式打开 .docx 文件。

- [Zotero Notes Sync](https://obsidian.md/plugins?id=zotero-notes-sync) By _lojeunhou_

> 将 Zotero 桌面笔记以 Markdown 形式同步到你的 Obsidian 库。

- [Share to Save](https://obsidian.md/plugins?id=share-to-save) By _chenxiccc_

> 将共享的网页内容保存到你的库。从移动端分享 URL，在桌面端下载并保存为 Markdown 笔记。

- [Copyparty Uploader](https://obsidian.md/plugins?id=copyparty-uploader) By _r3quisitevariety_

> 粘贴或拖放媒体文件，自动上传到你自托管的 Copyparty 服务器，并嵌入笔记。

- [ChatGPT Math Clipboard](https://obsidian.md/plugins?id=chatgpt-math-clipboard) By _vofen430_

> 以 Markdown 格式复制 ChatGPT Web Viewer 的回复，并严格进行 KaTeX 到 LaTeX 的转换。

- [Notes Exporter](https://obsidian.md/plugins?id=notes-exporter) By _anton_

> 用原生应用图标装饰导出的 Apple Notes 和 Bear Notes。在源应用中打开笔记。

- [Rich Link Resolver](https://obsidian.md/plugins?id=rich-link-resolver) By _almeidazs_

> 将粘贴或选中的 URL 转换为带有网站图标和标题的 Markdown 富链接。

##### 🗂️ 文件与附件管理

- [Consistent Attachments](https://obsidian.md/plugins?id=consistent-attachments) By _bueckerlars_

> 移动笔记时保持附件位置一致。

- [Vaultkeeper](https://obsidian.md/plugins?id=vaultkeeper) By _dudethatserin_

> 组织和管理附件、重命名粘贴的文件，并通过 OCR 提取文本——所有操作都在 Obsidian 库 内完成。

- [Markdown Image Manager](https://obsidian.md/plugins?id=md-image-manager) By _ytahml_

> 一个强大的 Obsidian 图像管理插件。浏览、优化、上传到图床并组织图片。非常适合将 Wiki 图像引用转换为标准 Markdown 格式。

- [Better Live Preview Image](https://obsidian.md/plugins?id=better-live-preview-image) By _ydd0729_

> 通过 Markdown 显示、调整大小和对齐工具改进实时预览中的图像编辑。

- [wk image caption](https://obsidian.md/plugins?id=wk-image-caption) By _bcs_

> 在实时预览和阅读模式下为图片显示优雅的标题。

- [LNS Directories](https://obsidian.md/plugins?id=lns-directories) By _hunchulchoi_

> 使用符号链接将外部目录和文件链接到库 中。

##### 🎓 学术与研究

- [Zotero Notes Sync](https://obsidian.md/plugins?id=zotero-notes-sync) By _lojeunhou_

> 将 Zotero 桌面笔记以 Markdown 形式同步到你的 Obsidian 库。

- [Literature Review Synthesizer](https://obsidian.md/plugins?id=literature-review-synthesizer) By _ibrh96-prog_

> 使用大模型将你的学术阅读笔记转化为结构化的文献综述输出。

- [Research Hub](https://obsidian.md/plugins?id=research-hub) By _wesswart77_

> 一个为 Obsidian 设计的专注研究工作区：捕获任何主题或项目的来源、证据、主张和综合笔记。

##### 🧠 知识管理

- [Keyword Notes Editor](https://obsidian.md/plugins?id=keyword-notes-editor) By _fengshuzi_

> 按关键词标签分组查看和编辑笔记，类似于 Logseq 的标签视图。

- [Smart Review](https://obsidian.md/plugins?id=smart-review) By _jaycelu_

> 基于 Obsidian 属性 / YAML frontmatter 的智能复习系统，带有复习中心、间隔复习反馈、历史记录和 AI 有效载荷导出。

- [Article Navigator](https://obsidian.md/plugins?id=article-navigator) By _ivanhanloth_

> 通过 frontmatter 属性为笔记添加上一篇/下一篇/另请参阅导航。支持浮动按钮或 VitePress 风格的内联导航。

- [Reference Note](https://obsidian.md/plugins?id=reference-note) By _rafaelmehdiyev_

> 通过从现有笔记克隆属性来创建新笔记。

- [VaultDex](https://obsidian.md/plugins?id=vaultdex) By _reggie86_

> 相关性评分的全文本库 搜索，支持 PARA 过滤、文件夹范围、短语和 AND 运算符。

- [Contextual Guides](https://obsidian.md/plugins?id=contextual-guides) By _chalas-ch_

> 在侧边栏中为活动笔记显示基于标签的上下文笔记。

- [Folder Bases](https://obsidian.md/plugins?id=folder-bases) By _scott-tomaszewski_

> 通过点击文件资源管理器中的文件夹来打开其关联的 Base，类似于文件夹笔记，但用于 Bases。

- [Simple Home Page](https://obsidian.md/plugins?id=simple-home) By _samyelkina_

> 打开一个简单的主页，包含文件名搜索、最近笔记、已删除笔记恢复和库 导航。

- [Study Vault](https://obsidian.md/plugins?id=study-vault) By _wesswart77_

> 一个用于课程和认证的学习系统：主题笔记、抽认卡复习、练习题和备考跟踪。

- [Book Tracker](https://obsidian.md/plugins?id=book-tracker) By _wesswart77_

> 追踪你的阅读生活：书籍、阅读状态、评分、评论、摘录和链接的主题。一个纯 Markdown 的个人图书馆。

- [Code Reference Library](https://obsidian.md/plugins?id=code-reference-library) By _wesswart77_

> 一个个人编码参考库：按语言和框架标记的模式和片段，全部使用纯 Markdown。

##### 🎨 界面与美化

- [Alert Banner](https://obsidian.md/plugins?id=alert-banner) By _samgg_

> 在带有特定标签的笔记顶部显示一个可配置的警告横幅。

- [WikiFlash](https://obsidian.md/plugins?id=wikiflash) By _paolinpaperin_

> 当你创建一个 wiki 链接或将光标移入其中时，闪烁显示 [[ ]] 括号——一个 Xcode 风格的括号匹配提示。颜色完全可自定义。

- [Novel Profile](https://obsidian.md/plugins?id=novel-profile) By _hornatx_

> 将原生属性区域转换为优雅的角色资料卡。

- [SoftView](https://obsidian.md/plugins?id=softview) By _icarsone_

> 在一个温暖、专注的阅读视图中打开当前的 Markdown 笔记。

- [Name Locker](https://obsidian.md/plugins?id=plugin-name-locker) By _agarcabin_

> 锁定已安装插件的自定义显示名称，使其在更新后保持不变。

- [Note Highlight](https://obsidian.md/plugins?id=note-highlight) By _wsqstar_

> 将方括号规划标签（如 [fact]、[trap] 和 [next]）渲染为可读的徽章。

- [Theme PADD](https://obsidian.md/plugins?id=theme-padd) By _jalad_

> 一个用于主题的 PADD（调色板、动画、装饰和密度）修改器。

- [Translucent BG](https://obsidian.md/plugins?id=translucent-bg) By _mellowmarsh-git_

> Windows 上的半透明窗口背景——亚克力模糊、云母和主题感知色调叠加。

- [Mobile Explorer](https://obsidian.md/plugins?id=mobile-explorer) By _marcpanu_

> 用类似 Apple Notes 的下钻导航器替换文件资源管理器。

- [Root Folder Order](https://obsidian.md/plugins?id=root-folder-order) By _chilohwei_

> 在文件资源管理器中以自定义顺序保留根级别文件夹。

- [Folder Sort](https://obsidian.md/plugins?id=folder-sort) By _t0masgutierrez_

> 按 A-Z 或 Z-A 排序文件夹。

- [Traystone](https://obsidian.md/plugins?id=traystone) By _tinswangtao-web_

> 将 Obsidian 运行到系统托盘，支持自定义窗口管理和全局快速笔记。

- [Desktop Sidebar Gestures](https://obsidian.md/plugins?id=desktop-sidebar-gestures) By _nth-chile_

> 用于打开和关闭 Obsidian 侧边栏的桌面方向性滑动手势。

- [Seamless Embeds](https://obsidian.md/plugins?id=seamless-embeds) By _5krus_

> 使嵌入/转载的笔记在视觉上与周围文本融为一体。

##### 💻 代码与开发

- [Calculator Pro](https://obsidian.md/plugins?id=calculator-pro) By _minhhoang_

> 一个设计简洁的科学计算器，支持 LaTeX 格式。

- [GhostTerm](https://obsidian.md/plugins?id=ghostterm) By _andyhtran_

> Obsidian 的 Ghostty 风格终端界面。

- [Developer Toolbox](https://obsidian.md/plugins?id=developer-toolbox) By _ckelsoe_

> 开发者工具，用于捕获带有结构化上下文的注释截图、实时重载插件，以及检查图标、CSS 变量和命令。

- [CSharp Snippet Runner](https://obsidian.md/plugins?id=csharp-snippet-runner) By _ohm-engineering, ivan_

> 使用自动安装的 CSharpRepl 运行时在 Obsidian 中运行 C# 代码块。

- [Dev Loader Updater](https://obsidian.md/plugins?id=dev-loader-updater) By _anonymisedfellow_

> 从用户定义的端点安装和更新私有开发插件，支持回退传输。

- [HTML Canvas](https://obsidian.md/plugins?id=html-canvas) By _x1han_

> 在 Obsidian 中打开本地 HTML 学习页面，使用原生浏览器渲染 CSS、MathML、SVG 图表和可视化笔记。

- [csvzall](https://obsidian.md/plugins?id=csvzall) By _vincentlaucsb_

> 一个用于 Obsidian 的快速 CSV 查看器、编辑器和图表插件。

- [Vim Cheatsheet](https://obsidian.md/plugins?id=vim-cheatsheet) By _rafaelmehdiyev_

> 应用内可搜索、分类的 Vim 命令参考。可与内置的 Vim 键绑定配合使用。

##### 🎵 多媒体

- [Echo Notes](https://obsidian.md/plugins?id=echo-notes) By _anbang278_

> 将库 中的音频文件转换为链接的 Markdown 转录稿。

- [Narrate](https://obsidian.md/plugins?id=narrate) By _jade_

> 通过本地 OpenAI 兼容的 TTS 服务器（如 OpenVox）朗读你的 Markdown 笔记。选择句子即可出现快速播放按钮，通过块预取实现无间断播放，带有可拖拽工具栏、表格/括号/代码过滤器以及 WAV 导出。

- [Draw Integration](https://obsidian.md/plugins?id=draw-integration) By _evolutiontrash_

> 将绘图应用程序集成到你的 Obsidian 工作流中，如 Krita、MyPaint、GIMP 等，一切以思维的速度进行。

##### 🌐 语言与翻译

- [Made Up Words](https://obsidian.md/plugins?id=made-up-words) By _obsidian-ttrpg-community, obsidian-ttrpg-community2_

> 一本为你自创的词汇准备的词典。浏览、搜索和查阅你发明的跨多种语言的词汇，带有悬停提示和侧面板词汇表。

- [DeepSeek Translator](https://obsidian.md/plugins?id=deepseek-translator) By _frankie18581_

> 使用 DeepSeek 的 AI 驱动的流式翻译，翻译选中的文本、整个文档，或使用侧边栏面板。

- [Language Learner](https://obsidian.md/plugins?id=language-learner) By _wesswart77_

> 通过词汇表、语法规则、词汇测验和按 CEFR 级别跟踪进度来学习语言。

##### 🔗 特定集成与服务

- [Private Quartz Publish](https://obsidian.md/plugins?id=private-quartz-publish) By _jagajaga_

> 选择性将单个笔记或整个文件夹从 Obsidian 发布到自托管的 Quartz 站点。每个 URL 都是一个不可猜测的随机标识符；共享文件链接只显示该文件，共享文件夹链接只显示其捆绑的笔记。

- [Share Hosted](https://obsidian.md/plugins?id=share-hosted) By _yut0takagi_

> 托管版的 org-share 替代方案：使用电子邮件登录，与组织/允许列表/公众分享笔记。无需 Cloudflare 设置。

- [Halo Plus](https://obsidian.md/plugins?id=halo-plus) By _hllshiro_

> 将 Obsidian 笔记发布到 Halo 博客，原生支持所有插件（Dataview、Tasks 等）的渲染。

- [isHistory CMS](https://obsidian.md/plugins?id=ishistory-cms) By _dr-ishaan_

> 用于 Astro 站点的 CMS，通过实时 frontmatter 模式验证和自动化发布工作流来管理文件集合。

- [HN Reader](https://obsidian.md/plugins?id=hn-reader) By _anliberant_

> 浏览 Hacker News 热门文章并将其保存到你的阅读列表。

- [Google Calendar and Tasks Sync](https://obsidian.md/plugins?id=google-sync) By _cordedmink2_

> 将库 中的事件和任务文件夹同步到 Google 日历和 Google Tasks。

- [Semantic Todoist Sync](https://obsidian.md/plugins?id=semantic-todoist-sync) By _neurocloud-activate_

> 自带密钥的语义/AI 库 搜索，Gemini/OpenAI 辅助的 Todoist 任务生成，使用笔记到 Todoist 和邮件到 Todoist（可选）工作流。

- [Zotero Notes Sync](https://obsidian.md/plugins?id=zotero-notes-sync) By _lojeunhou_

> 将 Zotero 桌面笔记以 Markdown 形式同步到你的 Obsidian 库。

- [Notes Exporter](https://obsidian.md/plugins?id=notes-exporter) By _anton_

> 用原生应用图标装饰导出的 Apple Notes 和 Bear Notes。在源应用中打开笔记。

- [TradingView Widget](https://obsidian.md/plugins?id=tradingview-widget) By _themanuelml_

> 打开一个可自定义的股票视图，显示由 TradingView 免费可嵌入小部件提供支持的图表和小部件（热图、滚动条、代码摘要、高级图表等）。

##### 🎲 游戏与桌面角色扮演 (TTRPG)

- [Heraldry Weaver](https://obsidian.md/plugins?id=heraldry-weaver) By _obsidian-ttrpg-community, obsidian-ttrpg-community2_

> 为世界构建者和 TTRPG 玩家提供的过程生成和自定义纹章。在代码块或表格中生成、保存和嵌入盾徽。

- [Town Forge](https://obsidian.md/plugins?id=town-forge) By _obsidian-ttrpg-community, obsidian-ttrpg-community2_

> 为桌面角色扮演游戏过程生成幻想景观和定居点地图，带有实时预览面板和可选的固定地图导出。

- [Trolls in the Cellar](https://obsidian.md/plugins?id=trolls-in-the-cellar) By _daren-thomas_

> 用于桌面角色扮演游戏准备的 Perchance 风格随机生成器。

- [RPG Detect Dice Roll](https://obsidian.md/plugins?id=rpg-detect-dice-roll) By _solorpgstudio_

> 检测笔记中的骰子公式，并提供自动掷骰子的方法。

- [Combat Ledger](https://obsidian.md/plugins?id=combat-ledger) By _snifer_

> 角色扮演游戏的战斗追踪器。从你的战斗人员笔记中读取 YAML 属性。

- [TTRPG Campaign Manager](https://obsidian.md/plugins?id=ttrpg-campaign-manager) By _wesswart77_

> 在纯 Markdown 中管理桌面角色扮演战役：NPC、地点、阵营、会话日志、任务和战利品。

- [stardew-valley-pals](https://obsidian.md/plugins?id=stardew-valley-pals) By _miaowuduck_

> 将星露谷物语的角色和宠物带入你的 Obsidian 库。

##### 🧩 其他实用工具

- [quizblock](https://obsidian.md/plugins?id=quizblock) By _olliecheng_

> 在笔记内渲染交互式多项选择测验块。

- [Tasting Notes](https://obsidian.md/plugins?id=tasting-notes) By _wesswart77_

> 记录葡萄酒和威士忌的品鉴笔记，包含评分、生产商信息、年份追踪和酒窖日志。

- [Design Portfolio](https://obsidian.md/plugins?id=design-portfolio) By _wesswart77_

> 管理你的设计作品集和灵感：案例研究、情绪板和客户工作日志，全部使用纯 Markdown。

- [Calculator Pro](https://obsidian.md/plugins?id=calculator-pro) By _minhhoang_

> 一个设计简洁的科学计算器，支持 LaTeX 格式。

#### 更新

[obsidian-attachment-management](obsidian://show-plugin?id=obsidian-attachment-management) By _trganda_

> - **0.12.1**（2026-05-26）：
>     - 修复：恢复 `${originalname}` 与其他变量混用时的存储持久化。
>     - 性能：为重命名提示加入防抖，避免 UI 刷屏。

[decks](obsidian://show-plugin?id=decks) By _dscherdi_

> - **1.13.2**（2026-05-30）：
>     - 修复：在窄侧边栏中，牌组名列始终保持可见和可点击。
> - **1.13.1**（2026-05-29）：
>     - 本地化修复：编辑卡片弹窗与 flashcard manager 中原本只显示英文的文案已全面翻译。
>     - 表头优化：牌组列表里的 "New / Due" 列不再因宽度过窄而截断。
>     - 移动端修复：牌组列表头部的编辑、网格、图表、刷新按钮现在能正常响应触摸。
> - **1.13.0**（2026-05-28）：
>     - 方案变更：`INTENSIVE` 配置被 `TRAINED` 取代；未训练时回退到 FSRS-6 默认值。
>     - 存储变更：训练权重从 `data.json` 迁移到数据库中的 `fsrs_weight_sets` 表，便于跨设备同步。
>     - 修复：评级按钮上的区间标签改为与实际调度一致。
> - **1.12.7**（2026-05-25）：
>     - 修复：移动端 tab 模式复习页面顶部多余空白带的问题。
> - **1.12.6**（2026-05-25）：
>     - 修复：tab 模式下的 Bury / Suspend / Reset 动作与快捷键现在和 modal 模式一致。
> - **1.12.5**（2026-05-25）：
>     - 新增 Bury / Suspend / Reset 三种卡片动作，review modal 和 flashcard manager 都加入了对应按钮与快捷键。
>     - 新增 `Is suspended` / `Is buried` 过滤字段，并支持在自定义卡组中使用。
>     - 同步、本地化和底层结构同步更新：动作可跨设备同步，新增 13 语种翻译，schema 升级到 v21，并新增 18 个测试。

[Easy Copy](obsidian://show-plugin?id=easy-copy) By _Moy_

> - **1.7.1**（2026-05-28）：
>     - 新增 " 显示名称：正则替换 " 选项，可对复制出的标题/笔记链接显示文本做正则查找替换，并支持捕获组引用。
> - **1.7.0**（2026-05-26）：
>     - 代码块检测改为 " 最内层优先 "，嵌套 fenced code block 中会复制光标所在的最内层块。
>     - 设置页调整：`onChange` 中的 `async/await` 改为 `void`，并更新 SettingGroup 分组。
>     - `package.json` 的 `name` 字段已从 `obsidian-sample-plugin` 修正为 `easy-copy`。
> - **1.6.5**（2026-05-26）：
>     - 修复代码块检测在两个 fenced code blocks 之间误判的问题。
>     - 增强不同长度围栏的嵌套支持。

[Quiet Outline](obsidian://show-plugin?id=obsidian-quiet-outline) By _guopenghui_

> - **0.5.14** (2026-05-28)：
>     - 新增：支持显示 PDF 视图的标题。

[Notebook Navigator](obsidian://show-plugin?id=notebook-navigator) By _johansan_

> - **3.0.2** (2026-05-29)：
>     - 新增：支持 Obsidian 1.13 的新设置 API，包括新的设置窗口与设置搜索。
>     - 改进：文件标签与属性胶囊现在遵循导航面板的排序；如启用相关设置，被着色的项目仍会优先显示。
>     - 改进：文件分组现在改用每个文件的真实父文件夹，后代标题会显示相对所选文件夹的完整路径。
>     - 修复：属性视图里开启 "Show parent folder" 时，缺失父文件夹标签的问题。
>     - 修复：在启用文件夹分组与后代笔记时，删除操作会选中错误下一条笔记的问题。
> - **3.0.1** (2026-05-25)：
>     - 新增：列表面板现在可以合并笔记，可通过右键多个文件或分组标题创建新笔记，也可用 "Merge notes" 命令。
>     - 新增：文件可显示字符数（含空格或不含空格），可在 Notes > Word and character count 中开启。
>     - 新增：启动调试日志设置，遇到启动缓慢时可开启并上传生成的 markdown 调试文件。
>     - 改进：搜索快捷方式现在可以从右键菜单重命名。
>     - 改进：列表面板的 "Edit sort order..." 现在完整支持键盘导航，包括 `CMD+↑/↓`。
>     - 变更：设置结构重写，便于从首层设置页直接进入所有子页面。
>     - 修复：修正了 Obsidian 打开时复制文件夹后，导航面板出现重复文件夹行的问题。

[Excalidraw](obsidian://show-plugin?id=obsidian-excalidraw-plugin) By _zsviczian_

> - **2.23.8** (2026-05-31)：
>     - 新增：可嵌入链接现在支持附加 ontology 元数据，便于被 Dataview 标签与 ExcaliBrain 等工具识别和渲染。
>     - 修复：安全修复后的回归问题，部分情况下 " 将 markdown 作为图片嵌入 " 会失败。
>     - 修复：把 markdown 作为图片嵌入时，默认字体设置现在会包含所有可用字体。
>     - ExcalidrawAutomate 新增：`ea.zoomToElements()` 支持可选的 margin 参数，用于控制缩放后元素周围留白。
>     - ExcalidrawAutomate 新增：`ea.cloneElements()`，可克隆元素并重新映射新 ID 与关联关系。
>     - 另外还补充了相应的类型定义说明。
> - **2.23.7** (2026-05-26)：
>     - 修复：部分 Excalidraw Script 图标会以过粗线条加载。
>     - 修复：Shade Master 脚本在编辑嵌套 Excalidraw 图时，颜色重映射界面无法正常显示。
>     - 修复：`fix(editor)` 相关的过度耗电问题。

[YOLO](obsidian://show-plugin?id=obsidian-yolo) By _Lapis0x0_

> - **1.5.10** (2026-05-31)：
>     - 新增：冻结 system prompt 以保持前缀缓存，避免中途修改 Memory 让整段缓存失效。
>     - 新增：每条外发消息都会携带当前时间作为轻量上下文。
>     - 新增：聊天输入框支持拖入文件夹作为上下文。
>     - 体验优化：长对话压缩改由主模型生成结构化摘要。
>     - 体验优化：更新提示改为左下角极简卡片，支持中英 changelog 切换、折叠/展开、一键更新与当前版本静默。
>     - 体验优化：聊天输入区选区高亮、模型菜单滚动条、聊天历史设置、选区块高亮显示、知识库网络韧性等都做了调整。
>     - 变更：精简 Agent 工具集，移除了 `context_prune_tool_results` 及相关链路，并统一了文件写入/删除工具。
>     - 变更：Skill frontmatter 不再使用独立 `id`，改为以 `name` 作为唯一标识。
>     - 修复：独立窗口里的 ChatUI 渲染失败问题。
>     - 修复：切换 root 目录或同步中断后，聊天记录无法加载的问题。
>     - 修复：上下文圆环上重复显示提示框的问题。
> - **1.5.9.4** (2026-05-27)：
>     - 新增：上下文占用面板把 " 思考过程 " 单独拆分出来显示。
>     - 体验优化：独立窗口聊天后输入框自动聚焦。
>     - 体验优化：点击 RAG 来源角标时，优先在已有分屏中打开笔记/PDF。
>     - 体验优化：桌面端自动请求模式不再回退到 Obsidian `requestUrl`。
>     - 修复：聊天面板弹成独立窗口后无法输入的问题。
> - **1.5.9.3** (2026-05-27)：
>     - 新增：RAG 结果现在支持可点击的内联引用标记，可跳转到对应笔记与位置。
>     - 新增：Agent system prompt 可在全屏编辑器中打开，便于长提示词阅读与编辑。
>     - 体验优化：即使未配置上下文长度，context ring 也会显示。
>     - 体验优化：Quick Ask 重写高亮与关闭面板时的高亮清理行为都做了调整。
>     - 修复：Mention 选择计数单位显示错误。
>     - 修复：外部脚本模式下 UMD 库加载失败、调试错误被笼统显示为连接错误的问题。
>     - 修复：Agent 工具开关在卡片页与详情页不同步。
>     - 修复：删除/重命名 MCP 服务器后，工具数量显示滞后的问题。
> - **1.5.9.2** (2026-05-25)：
>     - 新增：`js_eval` 内置工具，可在隔离沙箱中执行模型生成的 JavaScript。
>     - 新增：Cursor Chat 快捷指令支持拖动排序与隐藏。
>     - 体验优化：精简默认系统提示词，降低开销。
>     - 体验优化：移动端/桌面端样式做了多处打磨。
>     - 修复：非中文用户的历史标题乱码问题。
>     - 修复：Cursor Chat 中 " 使用助手=跟随当前选择 " 时未正确跟随的问题。
>     - 修复：Quick Ask 里的助手切换下拉样式异常。

### PKMer 出品

> [!INFO]
> **PKMer**（[PKMer.cn](https://pkmer.cn/)、[PKMer.net](https://pkmer.net/)）旨在打造东半球强大的知识管理社区。Personal Knowledge Management (PKM) + "er"，其中 "er" 表示人，专注、喜爱个人知识管理工作、追求效率的人们，都可以划入这个行列，希望社区凝聚更多这样的人。

#### Thino 已更新至 [v3.0.13](https://github.com/Quorafind/Obsidian-Thino/releases/tag/3.0.13)

- 修复：焦点模式和某些渲染器的问题

> [!Warning] 声明
> 本栏目致力于为广大 Obsidian 中文用户汇总全面的官方资讯与插件、外观动态。为了保持信息的全面性，我们的**收录并不等同于推荐**，还请各位用户知悉并理解，根据自身需求进行判断和选择。
