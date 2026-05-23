# CLAUDE.md

OSINT (Open-Source Intelligence) research methodology. Multi-wave investigative spiral that produces structured intel briefings from publicly available sources.

**Scope**: publicly available information only. No paid databases, no hacking, no social engineering. Public web, government records, court filings, academic publications, public social media, corporate filings.

**Tradeoff**: bias toward depth over breadth. A focused investigation of one subject beats a wide skim of many.

## The Investigative Spiral

Five waves, each narrows focus + increases depth:

### Wave 1 — Surface map

**Goal**: identify what's publicly known.

- Name + canonical identifiers (full legal name, registered company name, domains)
- Primary public presence (website, LinkedIn, Crunchbase, Wikipedia)
- One-paragraph summary from public sources
- List of secondary identifiers (aliases, AKAs, prior names)

**Done when**: you can name the subject in a sentence backed by 2-3 public sources.

### Wave 2 — Context

**Goal**: situate the subject in their network and timeline.

- Affiliations (employers, boards, advisory roles, co-founders, investors)
- Timeline (key dates: founded, hired, raised, exited, departed)
- Geographic context (where based, where operates)
- Public statements (interviews, podcasts, articles authored, conference talks)

**Done when**: you have a labeled timeline + a network diagram with named edges.

### Wave 3 — Patterns

**Goal**: find what's consistent and what's anomalous.

- Recurring themes in public statements
- Patterns in business decisions (acquisition style, hiring style, technology choices)
- Anomalies (gaps in timeline, abrupt pivots, unusual partnerships)
- Comparison to similar subjects (peer companies, similar roles)

**Done when**: you can name 3-5 patterns with evidence from multiple sources.

### Wave 4 — Predictions

**Goal**: from patterns, derive what's likely next.

- Most likely next moves (based on pattern × timeline)
- Alternative scenarios with probabilities
- Specific things to watch for that would confirm or refute each scenario
- Signal sources (where to monitor)

**Done when**: you have a prediction matrix with named scenarios + watch signals.

### Wave 5 — Briefing

**Goal**: produce the deliverable.

- Executive summary (3-4 sentences)
- Key findings (5-10 bullets with citations)
- Network diagram
- Timeline
- Pattern analysis (with evidence)
- Prediction matrix
- Source list (all URLs, dates accessed)

**Done when**: a stranger reading the briefing has the same model of the subject as you do.

## Ethics + scope

- **Public sources only**. If it requires login, credentials, payment for access to non-public records, or any kind of subterfuge, it's outside scope.
- **No doxxing**. If the subject is a private individual, focus on their public-facing role; do not surface home address, family details, personal phone numbers, etc., even if technically findable.
- **No grey-area scraping**. Respect robots.txt and rate limits.
- **Cite everything**. Every claim in the briefing traces to a public URL.
- **Currency stamp**. Note when each source was accessed. Public information ages.

## Wave-skip mode

For quick lookups (e.g., "who is this person, just give me 2 sentences"):

- Wave 1 only, then stop.
- Don't pretend the briefing is comprehensive if you only did Wave 1.

For deep investigations (e.g., due diligence before a partnership):

- All 5 waves. Allow days.
- Probably involve a second researcher to cross-check the prediction matrix.

## Anti-patterns

- **Confirmation bias**. Going in with a hypothesis and only collecting evidence for it. Run a steel-man for the alternative scenario.
- **Source laundering**. "Multiple sources say X" when those sources all cite the same original source. Trace claims back to the primary.
- **Currency confusion**. Treating 5-year-old data as current. Always stamp the date.
- **Reading too much into one signal**. A single anomaly is data; a pattern is signal.
- **Going past public**. The minute you reach for paywalled records, social engineering, or anything requiring credentials, you're out of OSINT and into something else.

## Hermetic framing

The methodology aligns with Mentalism (Wave 1: clear intention) and Correspondence (Waves 2-3: patterns flow through levels). Pattern → prediction (Wave 4) is Cause and Effect. The briefing (Wave 5) is the generative output completing the Gender pair.

You don't need the framing; the methodology stands alone. But if you've adopted [`hermetic-laws-skills`](https://github.com/HermeticOrmus/hermetic-laws-skills), the principles map directly.

---

**License**: MIT.
