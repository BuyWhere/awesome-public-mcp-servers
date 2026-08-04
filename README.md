# Awesome Public MCP Servers

<p align="center">
  <strong>Public MCP servers, organized around what you want to connect.</strong>
</p>

<p align="center">
  <a href="https://awesome.re"><img alt="Awesome" src="https://awesome.re/badge.svg"></a>
  <img alt="Model Context Protocol" src="https://img.shields.io/badge/MCP-servers-13795b">
  <a href="LICENSE"><img alt="CC0 1.0 license" src="https://img.shields.io/badge/license-CC0%201.0-555555"></a>
</p>

Discover MCP servers that connect assistants and agents to useful tools, data,
and workflows. Every entry should link to an official connection page,
endpoint, or public source repository and provide enough context to evaluate
how the server works before connecting.

Created and maintained by [0mcp.io](https://0mcp.io).

> This directory is being built. Contributions are welcome; please read
> [CONTRIBUTING.md](CONTRIBUTING.md) before adding a server.

## Contents

- [Servers](#servers)
- [Categories](#categories)
- [Legend](#legend)
- [Contributing](#contributing)
- [Maintainer](#maintainer)

## Servers

These entries are hosted MCP servers published and maintained by the linked
providers. Check each provider's documentation for plan requirements,
permissions, rate limits, and data-handling terms before connecting.

### Developer Tools

| Provider / server | Connection details | Capabilities | Transport | Auth | Tags |
| --- | --- | --- | --- | --- | --- |
| GitHub MCP Server | [Remote server setup](https://github.com/github/github-mcp-server/blob/main/docs/remote-server.md) (`https://api.githubcopilot.com/mcp/`) | Repositories, issues, pull requests, code search, and Actions | Streamable HTTP | GitHub OAuth or PAT | `official` `repositories` `issues` |

### Finance and Commerce

| Provider / server | Connection details | Capabilities | Transport | Auth | Tags |
| --- | --- | --- | --- | --- | --- |
| AgentServices | [MCP details](https://agentservices.to) (`https://api.agentservices.to/mcp`) | x402-paid crypto and market data APIs — BTC indicators, DeFi stats, macro data, exchange analytics, 54 services, and 37 MCP tools | Streamable HTTP | No API key; x402 USDC payment for paid tools | `official` `market-data` `crypto` |
| Stripe MCP Server | [MCP documentation](https://docs.stripe.com/mcp) (`https://mcp.stripe.com/`) | Payments, billing, products, customers, and Stripe documentation | Streamable HTTP | Stripe OAuth or restricted API key | `official` `payments` `billing` |

### Productivity

| Provider / server | Connection details | Capabilities | Transport | Auth | Tags |
| --- | --- | --- | --- | --- | --- |
| Linear MCP Server | [MCP server guide](https://linear.app/docs/mcp) (`https://mcp.linear.app/mcp`) | Issues, projects, comments, and planning workflows | Streamable HTTP | Linear OAuth or API key | `official` `project-management` `issues` |
| Notion MCP | [Connection guide](https://developers.notion.com/guides/mcp/get-started-with-mcp) (`https://mcp.notion.com/mcp`) | Workspace search, pages, and content management | Streamable HTTP | Notion account (OAuth) | `official` `knowledge-base` `documents` |

### Design and Creative

| Provider / server | Connection details | Capabilities | Transport | Auth | Tags |
| --- | --- | --- | --- | --- | --- |
| Figma MCP Server | [Remote server setup](https://developers.figma.com/docs/figma-mcp-server/remote-server-installation/) (`https://mcp.figma.com/mcp`) | Design context, code generation, canvas editing, and FigJam | Streamable HTTP | Figma account (OAuth) | `official` `design` `figjam` |

## Categories

Use the category that best describes the primary job a server helps someone
complete. Add a new category only when an existing one is not a good fit.

| Category | Includes |
| --- | --- |
| AI and LLM | Model providers, inference, evaluation, and agent tooling |
| Browser and Automation | Browsing, scraping, testing, and workflow automation |
| Communication | Email, chat, meetings, and notifications |
| Data and Databases | SQL, search, vector stores, analytics, and data platforms |
| Developer Tools | Code hosting, repositories, CI/CD, packages, and APIs |
| Files and Storage | Documents, object storage, content management, and file systems |
| Finance and Commerce | Payments, accounting, markets, shopping, and commerce |
| Productivity | Calendars, project management, notes, and collaboration |
| Search and Research | Web search, knowledge bases, retrieval, and citations |
| Cloud and Infrastructure | Hosting, observability, deployment, and infrastructure |
| Monitoring and Security | Security analysis, incident response, and operational tooling |
| Design and Creative | Design systems, media, graphics, and content creation |

## Legend

**Transport** identifies how a client connects to the server, such as
Streamable HTTP, SSE, or stdio. **Auth** identifies the credentials or account
needed to use it; `none` should be used only when the server truly requires no
authentication.

The `official` tag means the provider publishes or maintains the linked
server. Other tags should describe the server's primary capability, not serve
as a second category system.

Links point to the provider's official endpoint, connection documentation, or
source repository. Each provider retains ownership of its software,
trademarks, data, and licenses.

## Contributing

Contributions are welcome. Read [CONTRIBUTING.md](CONTRIBUTING.md) for the
acceptance criteria and pull request format.

## Maintainer

0mcp.io creates and maintains Awesome Public MCP Servers. This curated list is
dedicated to the public domain under [CC0 1.0 Universal](LICENSE). Linked MCP
servers and documentation remain subject to their respective owners' licenses
and terms.
