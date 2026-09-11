# Erik Rekola

I help people make their websites and APIs work with AI agents. I run [turva.dev](https://turva.dev), where I test what an agent can access and work out what needs changing when it gets stuck.

I also build the tools below. The code is open source so you can try it on your own site or see how mine works.

## Start here

| Project | What it does | Try it |
| --- | --- | --- |
| [markdown-parity-check](https://github.com/erekola/markdown-parity-check) | Compares the main content of HTML and Markdown pages, with source locations for differences and JSON output for CI. | [npm package](https://www.npmjs.com/package/markdown-parity-check) · [Hosted check, turva.dev pages only](https://turva.dev/markdown-parity-check) |
| [llms-txt-validator](https://github.com/erekola/llms-txt-validator) | Checks llms.txt structure from the command line or Node, with JSON output for CI. | [npm package](https://www.npmjs.com/package/turva-llms-txt-validator) · [Hosted validator](https://turva.dev/llms-txt-validator) |
| [turva-worker](https://github.com/erekola/turva-worker) | Runs my website, serving HTML and Markdown from shared content sources. It also publishes the site's discovery metadata. | [Live site](https://turva.dev) |
| [turva-mcp](https://github.com/erekola/turva-mcp) | Gives MCP clients read-only access to turva.dev's published information and evidence. | [Connect your client](https://github.com/erekola/turva-mcp#connect) |

The two command-line tools are available on npm. With Node.js 22 or newer installed, replace the example addresses with your own domain and page:

```sh
npx --yes turva-llms-txt-validator example.com
npx --yes markdown-parity-check --url https://example.com/page
```

The first command checks llms.txt structure. The second compares a page's HTML and Markdown responses. For a separate Markdown address, add `--markdown-url https://example.com/page.md` to the second command. Use the command for your own site, since the hosted comparison only accepts turva.dev pages.

## My website is part of the work

I use turva.dev as a reference implementation. Its [source code and verification instructions](https://github.com/erekola/turva-worker) are public, along with [dated measurements and their limits](https://github.com/erekola/turva-worker#scanner-results). You can inspect the implementation and repeat the checks.

## Guides and writing

I write about what I build and what happens when agents try to use websites.

- [llms.txt explained](https://turva.dev/guides/llms-txt).
- [The /.well-known directory for agent discovery](https://turva.dev/guides/well-known-for-agents).
- [What a website and API agent-readiness audit covers](https://turva.dev/guides/agent-readiness-audit).
- [The twin is the page](https://turva.dev/blog/the-twin-is-the-page).
- [Thirty-day follow-up: 201 comparable readings from 210 sites](https://turva.dev/blog/thirty-days-after-the-brief).
- [What four AI assistants call an agent readiness audit](https://turva.dev/blog/what-ai-assistants-call-an-agent-readiness-audit).
- [Website agent readiness, measured on 567 company sites](https://turva.dev/blog/website-agent-readiness-567-sites).

[All guides](https://turva.dev/guides) · [All writing](https://turva.dev/blog)

## Working with me

I'm based in Tampere, Finland. I work in writing and explain the findings so the people maintaining a site can follow the reasoning and test the changes themselves.

Send me your website and tell me what you're trying to do. That's enough to start: [info@turva.dev](mailto:info@turva.dev).

[Website](https://turva.dev) · [LinkedIn](https://www.linkedin.com/in/erikrekola)
