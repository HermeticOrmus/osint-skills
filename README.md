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
