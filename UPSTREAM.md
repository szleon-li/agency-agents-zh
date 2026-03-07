# Upstream Tracking

This file tracks which version of the upstream [agency-agents](https://github.com/msitarzewski/agency-agents) each translation is based on.

## Current Baseline

- **Upstream repo**: https://github.com/msitarzewski/agency-agents
- **Upstream commit**: `5e32f1d` (2026-03-07)
- **Upstream agent count**: 77

## Translation Coverage

| Category | Upstream | Translated | Coverage |
|----------|----------|------------|----------|
| design | 7 | 3 | 43% |
| engineering | 7 | 6 | 86% |
| marketing | 11 | 3 | 27% |
| product | 3 | 3 | 100% |
| project-management | 5 | 0 | 0% |
| spatial-computing | 6 | 0 | 0% |
| specialized | 7 | 1 | 14% |
| strategy | 16 | 0 | 0% |
| support | 6 | 3 | 50% |
| testing | 7 | 4 | 57% |

## China-Market Originals (not translations)

These agents are original creations for the Chinese market, not translations of upstream agents:

- `marketing/marketing-xiaohongshu-operator.md` - 小红书运营
- `marketing/marketing-douyin-strategist.md` - 抖音策略师
- `marketing/marketing-wechat-operator.md` - 微信公众号运营
- `specialized/prompt-engineer.md` - Prompt 工程师

## Sync Policy

- Translations track the upstream `main` branch
- New upstream agents are translated as time permits, priority given to high-demand categories
- Upstream breaking changes (renames, restructures) are synced within one week
