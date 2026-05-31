# Erik Rekola

Agent-readiness audits and advisory for product teams.

**turva.dev, my own reference build, is ranked #1 in the world on the public startuphub.ai agent-readiness leaderboard, scoring 100/100 (A+) across all six categories. On the Cloudflare Agent-Ready scanner it scores 100/100 at Level 5 (Agent-Native). Measured 2026-06-01.**

| Scanner | Result |
|---|---|
| Cloudflare Agent-Ready / isitagentready.com | 100 / 100, Level 5 (Agent-Native) |
| startuphub.ai leaderboard | 100 / 100 (A+), #1 of top 100 sites |
| turva.dev agent-readiness scanner | 100 / 100 (A+) |

startuphub.ai sub-scores (Discoverability, Content, Access Control, Capabilities, Commerce, Quality): 100/100 each.

The Cloudflare Worker that produces these results is open source: [turvadev-pretender](https://github.com/busygoat/turvadev-pretender). You can read every line before you hire me.

## Web security

Agent-readiness is one axis. The domain's own web security is another, and I publish turva.dev's own scan results so a buyer can see the same house is in order, not just claimed. Measured on turva.dev on 2026-05-30.

| Scanner | Result |
|---|---|
| Hardenize | All 13 categories passed |
| Internet.nl | 98 / 100 |

The missing 2 points on Internet.nl are a deliberate tradeoff. TLS 1.2 stays enabled for broad client compatibility, and I document the choice rather than hide it.

## Why this matters

AI agents such as ChatGPT search, Perplexity, Claude, and Copilot are now a discovery channel. They read sites and APIs through `/.well-known/` manifests, JSON-LD, head metadata, and protocol endpoints (MCP, x402, ACP, AP2). If those signals are wrong or contradicted by your CMS, your product becomes invisible inside the answer rather than merely de-ranked.

The skill is knowing which signals each agent actually reads, in what order, and how to make them deterministic across CMS drift.

## What I do

- **Audits.** Public scanner sweep across the leaderboards above, plus manual review of `/.well-known/` manifests, JSON-LD, head metadata, and protocol endpoints. Written report with prioritised gaps. Async-only.
- **Advisory.** Per-gap remediation notes your engineers can ship. Async-only.
- **Implementation.** Scoped repository write access per task if you want me to fix what I found. Same Worker pattern as turva.dev, adapted to your stack.

## How I work

- Async-only. No calls, no calendar links, no discovery meetings.
- Reply within one business day.
- Fixed scope per engagement, written before any payment.
- Open-source reference implementation means you verify the work against the same scanners I do.

## Contact

- Email: [info@turva.dev](mailto:info@turva.dev)
- Web: [turva.dev](https://turva.dev)
- LinkedIn: [in/erikrekola](https://www.linkedin.com/in/erikrekola)

Tell me your domain and what you want audited. I respond within one business day.
