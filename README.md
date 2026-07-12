# Linkex Skills

Skills that give AI agents native access to [Linkex](https://linkex.ai) — the
unified AI API gateway and settlement layer for agents.

| Skill | Description |
|-------|-------------|
| [linkex-agents-pay](skills/linkex-agents-pay/) | Fund your agent's AI usage with stablecoins via x402 (BNB Smart Chain, Base). Balance checks, top-up orders, wallet handoff, settlement. |

## Install

```bash
npx skills add stablepay-llc/linkex-skills/skills/linkex-agents-pay
```

## Layout

Each skill is self-contained under `skills/<name>/` with a `SKILL.md`
(frontmatter + instructions), a `README.md`, and `references/` — the same
layout used by [binance-skills-hub](https://github.com/binance/binance-skills-hub),
so skills here can be submitted upstream unchanged.

## License

MIT
