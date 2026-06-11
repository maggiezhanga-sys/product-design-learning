# Product Design Learning Log

This repository is the publishing directory for the automated product-design learning workflow.

## Latest Records

- 2026-06-11 19:13: 先别急着自动成交，先把采购上下文接起来。见 `public/records/2026-06-11-1913.html`。
- 2026-06-10 18:47: 先补信息差，再谈 AI 代采成交。见 `public/records/2026-06-10-1847.html`。
- 2026-06-10 16:08: 供应商可信表达，不是把证书堆满。见 `public/records/2026-06-10-1608.html`。
- 2026-06-10 15:31: 把询盘做深：B2B 跨境 AI 的第一落点。见 `public/records/2026-06-10-1531.html`。

## Record Format

Each new note should stay practical and scenario-driven:

- What changed in product, UX, B2B commerce, or desktop tooling
- Why it matters to real users
- Which product opportunity it suggests
- What should be validated next
- How the idea could be shared online for free

## Current Constraints

- Only write inside this repository
- Do not modify system configuration
- Do not install dependencies
- Do not delete or move user files
- Do not change unrelated project code

## Static Publishing

Recommended deployment settings:

- Build command: leave empty
- Build output directory: `public`
- Production branch: `main`
- Deploy command: `npx wrangler deploy --assets public`
- Non-production branch deploy command: `npx wrangler versions upload --assets public`

Do not publish the repository root directly.
