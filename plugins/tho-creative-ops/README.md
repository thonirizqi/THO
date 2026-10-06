# THO Creative Ops

A toolkit for music, event, and brand-partnership work: campaign planning, social content, sponsorship proposals and outreach, competitive benchmarking, decision support, inbox triage, and web-based business dashboards. Nothing in it needs a paid API.

## What's inside

**Skills (work in chat, Cowork, and Claude Code)**

| Area | Skills |
|---|---|
| Marketing & content | `marketing-campaign`, `content-engine`, `article-writing`, `crosspost` |
| Sponsorship & proposals | `investor-materials`, `investor-outreach` (say "for a sponsor" when using these) |
| Research & strategy | `market-research`, `competitive-platform-analysis` → `benchmark-methodology` → `competitive-report-structure`, `council`, `product-lens` |
| Operations | `email-ops` |
| Dashboards & visuals | `dashboard-web-app`, `frontend-design-direction`, `make-interfaces-feel-better`, `frontend-slides` |

**Agents (Cowork and Claude Code only; chat ignores them)**

- `marketing-agent`: campaign strategist and copywriter
- `seo-specialist`: SEO audits and content/keyword mapping
- `agent-evaluator`: scores a finished output on accuracy, completeness, clarity, actionability, and conciseness

## How to use

Describe the task in plain language ("buat dashboard sponsor dari Notion", "draft follow-up email ke calon sponsor", "benchmark 5 festival pesaing"). Claude loads the matching skill. To pick one yourself, type `/` and search for `tho-creative-ops`.

## Data

The plugin itself sends nothing anywhere and stores nothing. Skills only use the connectors you have already connected (for example Google Drive, Notion, or Gmail), and only when a task asks for them.

## Credits

All skills except `dashboard-web-app`, and all three agents, come from [ECC (Everything Claude Code)](https://github.com/affaan-m/ECC) by Affaan Mustafa, MIT License (see `LICENSE-ECC`). `dashboard-web-app` was written for this plugin.
