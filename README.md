# Erik Rekola

Agent-readiness audits and advisory for product teams, and the wider work of making the data agents act on and the decisions they make reliable.

turva.dev is my own reference build. It scores 100/100, Level 5 (Agent-Native), on isitagentready.com, Cloudflare's agent-readiness scanner, measured 2026-07-28. Its own web security is published on the same principle: Hardenize passes all 13 categories and Internet.nl reads 98/100, the one deduction being a single HTTPS sub-test I document rather than hide.

The Cloudflare Worker behind those results is open source: [turva-worker](https://github.com/erekola/turva-worker). You can read every line before you hire me, starting with the [agent-readiness reference](https://github.com/erekola/turva-worker/blob/main/docs/agent-readiness.md) that defines every surface below.

## Why this matters

AI agents such as ChatGPT search, Perplexity, Claude and Copilot are now a discovery channel. They read sites and APIs through `/.well-known/` manifests, JSON-LD, head metadata and protocol endpoints (MCP, x402, ACP, AP2). If those signals are wrong or contradicted by your CMS, your product becomes invisible inside the answer rather than merely de-ranked.

The skill is knowing which signals each agent actually reads, in what order, and how to make them deterministic across CMS drift.

## Guides

* [What an agent-readiness audit is](https://turva.dev/guides/agent-readiness-audit)
* [Why agent-readiness should be measured, not asserted](https://turva.dev/guides/measurement-led-agent-readiness)
* [llms.txt explained](https://turva.dev/guides/llms-txt)
* [The /.well-known directory for agents](https://turva.dev/guides/well-known-for-agents)

## Writing

* [Every response promised a rate limit. Nothing enforced it.](https://turva.dev/blog/enforcing-the-rate-limit-i-advertised)
* [Microsoft said the patches would get bigger. I measured how much bigger.](https://turva.dev/blog/measuring-the-ai-patch-surge)
* [What an agent pays to read your site](https://turva.dev/blog/cheaper-pages-for-agents)

## What I do

Audits, advisory, implementation, agent operations and MCP server design. Fixed scope per engagement, written before any payment.

## How I work

* Async-only. No calls, no calendar links.
* Open source reference implementation, so you verify the work against the same scanner I do.

---

Guide and post indexes are at [turva.dev](https://turva.dev), along with the fixed prices.

Tell me your domain and what you want audited: info@turva.dev, reply within one business day.
