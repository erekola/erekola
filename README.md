# Erik Rekola

I build and audit websites and APIs that AI agents can find and use.

At [turva.dev](https://turva.dev), I help Shopify stores and product teams find what blocks agents and decide what to fix first.

## Start here

Three repos, one site.

| Project | What it does | Explore |
| --- | --- | --- |
| [turva-worker](https://github.com/erekola/turva-worker) | The Cloudflare Worker behind turva.dev: HTML for people, Markdown for agents, and the site's discovery metadata and protocol endpoints. | [Live reference](https://turva.dev) · [Technical reference](https://github.com/erekola/turva-worker/blob/main/docs/agent-readiness.md) |
| [llms-txt-validator](https://github.com/erekola/llms-txt-validator) | Check llms.txt structure from the command line, Node or CI, with readable results and JSON output. | [Try the hosted validator](https://turva.dev/llms-txt-validator) |
| [turva-mcp](https://github.com/erekola/turva-mcp) | A public, read-only MCP server exposing turva.dev's services and published evidence. No API key required. | [Client configuration](https://github.com/erekola/turva-mcp#connect) |

Try the validator on a domain: `npx turva-llms-txt-validator example.com`.

MCP endpoint: `https://mcp.turva.dev/mcp`.

## Reference build

turva.dev is my own reference implementation. It recorded **100/100, Level 5 (Agent-Native)** on [isitagentready.com](https://isitagentready.com/), Cloudflare's agent-readiness scanner, on **2026-09-06**.

The [source code and verification instructions](https://github.com/erekola/turva-worker) are public. You can inspect the implementation and repeat the checks before deciding whether to work with me.

The site's published web-security checks recorded passes in all 24 categories on [Hardenize](https://www.hardenize.com/report/turva.dev) and 98/100 on [Internet.nl](https://internet.nl/site/turva.dev/). Measurement dates and the documented exceptions are in the [reference repository](https://github.com/erekola/turva-worker#web-security).

## What I do

Shopify agent storefront check, audit, advisory, implementation, agent operations and MCP server design. The two diagnoses come with documented findings and prioritized fixes, and the rest is scoped per engagement.

The work covers content agents can retrieve and parse, interfaces they can call, and the data and decision boundaries they rely on when acting. AI-search visibility is measured separately from whether an agent can use a site's tools or purchase flows.

[Service scopes and prices](https://turva.dev/services)

## How I work

- Async-only: everything in writing.
- A fixed scope agreed before payment.
- Findings and verification steps your team can use directly.
- Replies within one business day.

## Guides

- [What an agent-readiness audit is](https://turva.dev/guides/agent-readiness-audit)
- [Choosing an agent-readiness audit](https://turva.dev/guides/choosing-an-agent-readiness-audit)
- [llms.txt explained](https://turva.dev/guides/llms-txt)
- [The /.well-known directory for agents](https://turva.dev/guides/well-known-for-agents)

## Writing

- [Thirty days after the brief: 210 sites rescanned, four moved](https://turva.dev/blog/thirty-days-after-the-brief)
- [What four AI assistants call an agent readiness audit](https://turva.dev/blog/what-ai-assistants-call-an-agent-readiness-audit)
- [Website agent readiness, measured on 567 company sites](https://turva.dev/blog/website-agent-readiness-567-sites)

## Contact

Based in Tampere, Finland.

Email [info@turva.dev](mailto:info@turva.dev) with your domain and what you want agents to be able to do.

[Website](https://turva.dev) · [LinkedIn](https://www.linkedin.com/in/erikrekola) · [All guides](https://turva.dev/guides) · [All writing](https://turva.dev/blog)