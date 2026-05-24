# OSINT Skills

> A single `CLAUDE.md` for OSINT (Open-Source Intelligence) research methodology — multi-wave investigative spiral with structured intel briefing output.

## The methodology

Five waves, each narrows focus + increases depth:

1. **Surface map** — what's publicly known
2. **Context** — affiliations, timeline, geography
3. **Patterns** — recurring themes + anomalies
4. **Predictions** — likely next moves + watch signals
5. **Briefing** — structured deliverable

The pattern: don't dump all available information. Distill, layer, structure.

Full content: [`CLAUDE.md`](CLAUDE.md).

## Scope

**In scope**:
- Public web, news media, government records, court filings
- Academic publications, think-tank analyses
- Public social media, corporate filings
- Public statements (interviews, podcasts, articles, talks)

**Out of scope**:
- Paywalled databases, social engineering, hacking
- Doxxing of private individuals
- Information requiring credentials or subterfuge

## Install

```bash
curl -o CLAUDE.md https://raw.githubusercontent.com/HermeticOrmus/osint-skills/main/CLAUDE.md
```

Or as a [Claude Code skill](skills/osint/) or [Cursor rule](.cursor/rules/osint.mdc).

## When to use

- Pre-partnership due diligence
- Pre-investment subject research
- Competitive intelligence
- Journalism research
- Historical research on a person, company, or event

## When NOT to use

- "Look up my ex" / personal stalking — not OSINT, won't help
- Anything requiring real-time monitoring (different discipline: media monitoring)
- Anything requiring access to private data (out of scope by construction)

## Anti-patterns the methodology prevents

- Confirmation bias (run a steel-man for the alternative)
- Source laundering (trace claims to primary sources)
- Currency confusion (always stamp source date)
- Single-signal extrapolation (one anomaly is data, a pattern is signal)
- Going past public sources

## See also

- [`hermetic-laws-skills`](https://github.com/HermeticOrmus/hermetic-laws-skills) — the principle framing
- [`vibe-engineer-skills`](https://github.com/HermeticOrmus/vibe-engineer-skills) — direct AI codegen well

## License

MIT. The methodology is yours to use; the ethics are yours to honor.


---

## Part of the Libre Open-Source Stack for Claude Code

This repository is part of a growing family of open-source toolkits for Claude Code.

### Libre suite — comprehensive plugin bundles

- [LibreUIUX-Claude-Code](https://github.com/HermeticOrmus/LibreUIUX-Claude-Code) — UI/UX development (152 agents, 70 plugins, 76 commands, 74 skills)
- [LibreArch-Claude-Code](https://github.com/HermeticOrmus/LibreArch-Claude-Code) — Software architecture and system design
- [LibreCopy-Claude-Code](https://github.com/HermeticOrmus/LibreCopy-Claude-Code) — Technical writing and documentation engineering
- [LibreDevOps-Claude-Code](https://github.com/HermeticOrmus/LibreDevOps-Claude-Code) — DevOps engineering and infrastructure automation
- [LibreEmbed-Claude-Code](https://github.com/HermeticOrmus/LibreEmbed-Claude-Code) — Embedded systems, firmware, and IoT development
- [LibreFinTech-Claude-Code](https://github.com/HermeticOrmus/LibreFinTech-Claude-Code) — Financial technology development
- [LibreGEO-Claude-Code](https://github.com/HermeticOrmus/LibreGEO-Claude-Code) — AI-search optimization (ChatGPT, Perplexity, Gemini, Google AI Overviews)
- [LibreGameDev-Claude-Code](https://github.com/HermeticOrmus/LibreGameDev-Claude-Code) — Game development across Godot, Unity, Unreal
- [LibreMLOps-Claude-Code](https://github.com/HermeticOrmus/LibreMLOps-Claude-Code) — ML engineering and AI operations
- [LibreMobileDev-Claude-Code](https://github.com/HermeticOrmus/LibreMobileDev-Claude-Code) — Mobile app development (Flutter, React Native, native iOS, native Android)
- [LibreSecOps-Claude-Code](https://github.com/HermeticOrmus/LibreSecOps-Claude-Code) — Security operations

### Skills mini-repos — single CLAUDE.md drop-ins

- [vibe-engineer-skills](https://github.com/HermeticOrmus/vibe-engineer-skills) — Direct AI codegen well (hypothesis → scope → validate → reject working-but-wrong)
- [markdown-discipline-skills](https://github.com/HermeticOrmus/markdown-discipline-skills) — Strip AI-slop from markdown (no em dashes, no marketing fluff)
- [shell-safety-skills](https://github.com/HermeticOrmus/shell-safety-skills) — `set -euo pipefail` discipline + 15 failure-mode examples
- [commit-standard-skills](https://github.com/HermeticOrmus/commit-standard-skills) — Ormus Commit Standard v1.0 + commit-msg hook + commitlint
- [unwoke-skills](https://github.com/HermeticOrmus/unwoke-skills) — Strip AI theater (ten sins to eliminate, symmetric engagement)
- [python-conventions-skills](https://github.com/HermeticOrmus/python-conventions-skills) — Modern Python 3.11+ (types, pathlib, async, ruff, mypy, uv)
- [typescript-conventions-skills](https://github.com/HermeticOrmus/typescript-conventions-skills) — TypeScript strict mode, discriminated unions, Result types
- [hermetic-laws-skills](https://github.com/HermeticOrmus/hermetic-laws-skills) — Seven Hermetic Principles applied to engineering
- [riper-workflow-skills](https://github.com/HermeticOrmus/riper-workflow-skills) — Research / Innovate / Plan / Execute / Review systematic dev
- [six-day-cycle-skills](https://github.com/HermeticOrmus/six-day-cycle-skills) — Sustainable shipping cadence with mandatory rest
- [token-optimization-skills](https://github.com/HermeticOrmus/token-optimization-skills) — Claude Code token + context optimization
- [calcinate-skills](https://github.com/HermeticOrmus/calcinate-skills) — Stage 1 of the Magnum Opus (burn project bloat)
- [claude-md-overhaul-skills](https://github.com/HermeticOrmus/claude-md-overhaul-skills) — Audit CLAUDE.md and MEMORY.md against caps
- [session-handoff-skills](https://github.com/HermeticOrmus/session-handoff-skills) — Session handoff + pickup discipline
- [naming-skills](https://github.com/HermeticOrmus/naming-skills) — Product naming methodology (mine the brand's vocabulary)
- [magnum-opus-skills](https://github.com/HermeticOrmus/magnum-opus-skills) — Seven-stage alchemy applied to project transformation

### Template source

- [andrej-karpathy-skills](https://github.com/HermeticOrmus/andrej-karpathy-skills) — the canonical single-file CLAUDE.md pattern (fork of jiayuan_jy's original)

Star the family, not just one — that's how the suite stays coherent.
