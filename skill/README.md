# AI Topic Radar Skill

一个面向 AI 内容创作者的选题筛选 Skill。

## 文件
- `SKILL.md`：核心规则，可直接复制给支持自定义 Skill / 系统提示词的 AI。
- `config.json`：默认信息源、模式与优先级配置。
- `example_prompts.md`：今日精选、周报、公众号、短视频等调用示例。

## 怎么用
### 方式 1：直接复制 Skill
打开 `SKILL.md`，复制完整内容，粘贴到支持自定义 Skill、System Prompt、Project Instructions 或 Agent Instructions 的 AI 工具里。

### 方式 2：整包复用
把整个 `skill/` 目录下载或克隆到你的项目中，让 Agent 同时读取 `SKILL.md`、`config.json` 和 `example_prompts.md`。

## 适用场景
- 每日 AI 新闻精选
- 每周 AI 周报
- AI 设计 / 生图 / 视频专项选题
- 公众号选题
- 小红书选题
- 短视频选题

## 默认信息源
- AIHOT
- 鱼皮 AI 导航 News
- FutureTools News

> 提醒：这个 Skill 本身定义筛选逻辑。要获取实时新闻，调用它的 AI 仍需具备联网搜索或网页访问能力。
