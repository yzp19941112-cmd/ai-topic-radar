# AI Topic Radar Skill

## Purpose
将多个 AI 新闻源整理成去重、高信号、适合内容创作的选题池。

## Default sources
- https://aihot.news/
- https://ai.codefather.cn/news
- https://futuretools.io/news

## Invocation modes
- Today：过去 24 小时，保留 0–5 条。
- Weekly：过去 7 天，最多 10 条，并总结本周主线。
- Design-only：仅保留设计、生图、视频、3D、UI、剪辑、创作者工具与工作流变化。
- WeChat article：优先适合公众号长文、有案例和观点空间的内容。
- Short video：优先强冲突、强数据、强结果感、强开头钩子的内容。

## Filtering rules
1. 合并所有来源，并在事件层面去重；同一事件保留信息最完整的一条。
2. 最高优先级：AI 生图、AI 视频、3D、UI、设计工具、剪辑、Agent 工作流、创作者工具。
3. 优先保留成本、速度、工作流、产品形态或商业化发生明显变化的事件。
4. 优先保留含真实用户、公司、价格、效率、播放量、评测数据等可核验信息的内容。
5. 默认过滤纯融资、小版本更新、缺少实际影响的论文和凑数新闻。
6. 不强行凑数，0 条也可以。

## Required output for each item
- 事件
- 核心事实
- 为什么值得关注
- 推荐内容角度
- 最适合的平台：公众号 / 小红书 / 短视频
- 来源链接

## Style
默认使用中文。语言简洁、面向创作者，避免新闻稿腔和官方套话。
