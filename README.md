# Erik Rekola

Agent-readiness audits and advisory for product teams.

**turva.dev — my own reference build — is ranked #1 in the world on the public agent-readiness leaderboard, with 100/100 across every category. Measured 2026-05-28.**

| Scanner | Result |
|---|---|
| turva.dev agent-readiness scanner | 100 / 100 (A+) |
| isitagentready.com | 100 / 100 |
| startuphub.ai leaderboard | #1 of top 100 sites |
| Sub-scores (Discoverability, Content, Access Control, Capabilities, Commerce, Quality) | 100/100 each |

The Cloudflare Worker that produces these results is open source: [turvadev-pretender](https://github.com/busygoat/turvadev-pretender). You can read every line before you hire me.

## Why this matters

AI agents — ChatGPT search, Perplexity, Claude, Copilot — are now a discovery channel. They read sites and APIs through `/.well-known/` manifests, JSON-LD, head metadata, and protocol endpoints (MCP, x402, ACP, AP2). If those signals are wrong, missing, or contradicted by your CMS, your product is invisible inside the answer. Not de-ranked. Invisible.

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
