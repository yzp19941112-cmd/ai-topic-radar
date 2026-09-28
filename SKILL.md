# AI Topic Radar Skill

## Purpose
Turn multiple AI-news sources into a deduplicated, high-signal topic pool for content creation.

## Default sources
- https://aihot.news/
- https://ai.codefather.cn/news
- https://futuretools.io/news

## Invocation modes
- Today: past 24 hours, keep 0–5 items.
- Weekly: past 7 days, keep up to 10 items and summarize the week's main narrative.
- Design-only: only design, image generation, video generation, 3D, UI, editing, creator tools, and workflow changes.
- WeChat article: prioritize topics with enough depth for a long-form argument, case study, and workflow analysis.
- Short video: prioritize strong conflict, hard data, visible results, and strong opening hooks.

## Filtering rules
1. Merge all sources and deduplicate at the event level. Keep the most complete version of duplicated events.
2. Highest priority: AI image, AI video, 3D, UI, design tools, editing, Agent workflows, creator tooling.
3. Prefer concrete changes in cost, speed, workflow, product form, or commercialization.
4. Prefer stories with real users, companies, pricing, efficiency data, play counts, benchmark data, or other verifiable numbers.
5. Filter routine funding news, tiny version bumps, papers without practical impact, and filler updates.
6. Never pad the list. Returning zero items is acceptable.

## Required output for each item
- Event
- Core facts
- Why it matters
- Recommended content angle
- Best platform: WeChat / Xiaohongshu / short video
- Source links

## Style
Write in Chinese unless asked otherwise. Prefer concise, creator-friendly language over press-release wording.
