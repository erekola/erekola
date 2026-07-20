# Erik Rekola

Agent-readiness audits and advisory for product teams, and the wider work of making the data agents act on and the decisions they make reliable.

**turva.dev, my own reference build, scores 100/100 at Level 5 (Agent-Native) on isitagentready.com, Cloudflare's agent-readiness scanner. Measured 2026-07-20.**

| Scanner | Result |
|---|---|
| isitagentready.com (Cloudflare) | 100/100, Level 5 (Agent-Native) |


The Cloudflare Worker that produces these results is open source: [turva-worker](https://codeberg.org/erekola/turva-worker). You can read every line before you hire me.

## Web security

Agent-readiness is one axis. The domain's own web security is another, and I publish turva.dev's own scan results so a buyer can see the same house is in order, not just claimed. Measured on turva.dev on 2026-07-20.

| Scanner | Result |
|---|---|
| Hardenize | All 13 categories passed |
| Internet.nl | 98 / 100 |

On Internet.nl, IPv6, DNSSEC and RPKI pass in full. The single deduction is one HTTPS sub-test, the hash function for key exchange, which I document rather than hide.

## Why this matters

AI agents such as ChatGPT search, Perplexity, Claude, and Copilot are now a discovery channel. They read sites and APIs through `/.well-known/` manifests, JSON-LD, head metadata, and protocol endpoints (MCP, x402, ACP, AP2). If those signals are wrong or contradicted by your CMS, your product becomes invisible inside the answer rather than merely de-ranked.

The skill is knowing which signals each agent actually reads, in what order, and how to make them deterministic across CMS drift.

## Agent-readiness reference

A consolidated agent-readiness reference, with a short definition of each surface agents read and a link to its full guide, is in the open-source repository: [docs/agent-readiness.md](https://codeberg.org/erekola/turva-worker/src/branch/main/docs/agent-readiness.md).

## Agent-readiness guides

I publish plain-language guides on the surfaces agents read and how to make a site legible to them. Published on turva.dev.

* [Agent-readiness guides (index)](https://turva.dev/guides)
* [What an agent-readiness audit is](https://turva.dev/guides/agent-readiness-audit)
* [llms.txt explained](https://turva.dev/guides/llms-txt)
* [Serving markdown to agents](https://turva.dev/guides/markdown-for-agents)
* [Response headers that help agents](https://turva.dev/guides/response-headers-for-agents)
* [Sitemaps, robots.txt and agent access](https://turva.dev/guides/sitemaps-and-robots-for-agents)
* [Prerendering and why agents see empty pages](https://turva.dev/guides/prerendering-for-agents)
* [MCP server cards explained](https://turva.dev/guides/mcp-server-card)
* [What agents.json is](https://turva.dev/guides/agents-json)
* [The /.well-known directory for agents](https://turva.dev/guides/well-known-for-agents)
* [How agents authenticate](https://turva.dev/guides/agent-authentication)
* [JSON-LD and structured data for agents](https://turva.dev/guides/json-ld-structured-data)
* [x402 and agent payments](https://turva.dev/guides/x402-agent-payments)
* [SEO and agent-readiness are not the same](https://turva.dev/guides/seo-vs-agent-readiness)
* [Why agent-readiness should be measured, not asserted](https://turva.dev/guides/measurement-led-agent-readiness)
* [Common agent-readiness gaps on marketing sites](https://turva.dev/guides/agent-readiness-gaps)
* [Choosing an agent-readiness audit](https://turva.dev/guides/choosing-an-agent-readiness-audit)
* [How to get your site cited by AI assistants](https://turva.dev/guides/get-cited-by-ai-assistants)
* [Agent commerce discovery: A2A, AP2, and ACP](https://turva.dev/guides/agent-commerce-discovery)
* [Agent-readiness, AEO and GEO: how they relate](https://turva.dev/guides/agent-readiness-aeo-geo)
* [Agentic commerce readiness](https://turva.dev/guides/agentic-commerce-readiness)
* [Letting agents act on data: the decision envelope](https://turva.dev/guides/letting-agents-act-on-data)
* [AI agent use cases](https://turva.dev/guides/ai-agent-use-cases)
* [Open Knowledge Format (OKF) explained](https://turva.dev/guides/open-knowledge-format)
* [Agentic Resource Discovery and ai-catalog.json](https://turva.dev/guides/agentic-resource-discovery)

## Writing

Notes on AI agents, and the work of letting them read a site and act on a system safely. Anything that can be measured is checked against independent scanners rather than asserted. A selection is below, with the full index on turva.dev.

* [Blog index](https://turva.dev/blog)
* [Finishing the optional commerce checks](https://turva.dev/blog/finishing-the-optional-commerce-checks)
* [The twin is the page](https://turva.dev/blog/the-twin-is-the-page)
* [Every response promised a rate limit. Nothing enforced it.](https://turva.dev/blog/enforcing-the-rate-limit-i-advertised)
* [Microsoft said the patches would get bigger. I measured how much bigger.](https://turva.dev/blog/measuring-the-ai-patch-surge)
* [Auditing the auditor with four AI agents](https://turva.dev/blog/auditing-the-auditor)
* [What one agent-readiness scanner cannot tell you](https://turva.dev/blog/two-scanner-audit-method)
* [What an agent pays to read your site](https://turva.dev/blog/cheaper-pages-for-agents)
* [Passing the agent commerce checks without faking them](https://turva.dev/blog/honest-agent-commerce-checks)

## What I do

- **Audits.** Public scanner sweep, plus manual review of `/.well-known/` manifests, JSON-LD, head metadata, and protocol endpoints. Written report with prioritized gaps. Async-only.
- **Advisory.** Per-gap remediation notes your engineers can ship. Async-only.
- **Implementation.** Scoped repository write access per task if you want me to fix what I found. Same Worker pattern as turva.dev, adapted to your stack.
- **Agent operations.** Beyond readiness: making the data an agent acts on and the decisions it is allowed to make reliable. Scoped per engagement. Async-only.
- **MCP server design.** Read-only discovery tools and Streamable HTTP transport, no auth surface and no logging by default. The endpoint stays readable for agents without turning into an abuse vector. Async-only.

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
