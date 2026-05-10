# LLM Overview — mcp-servers
*Updated: 2026-05-10 07:35 UTC | Tier: micro | Auto-updated: daily cron*

## What This Is
<p align="center"> <a href="https://docs.mcp-agent.com"><img src="https://github.com/user-attachments/assets/c8d059e5-bd56-4ea2-a72d-807fb4897bde" alt="Logo" width="300" /></a>

## Current State
*Status: 🟢 active from local git history* — 1 commits in the rolling window; last commit 9 minutes ago.

## Key Commands
- `npm run build  # tsc && node -e "require('fs').chmodSync('dist/index.js', '755')"`
- `npm run dev  # npm run build && npx @modelcontextprotocol/inspector node dist/index.js`
- `npm run lint  # eslint src/**/*.ts`
- `npm run lint:fix  # eslint src/**/*.ts --fix`
- `npm run format  # prettier --write .`

## Gotchas
- Keep changes small and verify against local docs before assuming project intent.
