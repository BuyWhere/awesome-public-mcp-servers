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

| Provider / server | Connection details | Capabilities | Auth | Tags |
| --- | --- | --- | --- | --- |
| GitHub | [Remote server setup](https://github.com/github/github-mcp-server/blob/main/docs/remote-server.md) (`https://api.githubcopilot.com/mcp/`) | Repositories, issues, pull requests, code search, and Actions | GitHub OAuth or PAT | `official` `repositories` `issues` |
| LaunchDarkly | [Hosted MCP server documentation](https://launchdarkly.com/docs/home/getting-started/mcp-hosted) (`https://mcp.launchdarkly.com/mcp/launchdarkly`) | Feature flags, AgentControl configs, observability logs, traces, errors, dashboards, and metrics | LaunchDarkly OAuth; hosted server excludes federal and EU environments | `official` `feature-flags` `observability` |
| Postman | [Remote MCP server setup](https://learning.postman.com/latest-v-12/docs/reference/postman-api/postman-mcp-server/postman-mcp-remote-server) (`https://mcp.postman.com/mcp`) | Workspaces, collections, specifications, mocks, monitors, environments, and API workflows | Postman OAuth on the US remote server; API key required for the EU remote server | `official` `api-testing` `workspaces` |
| Twilio | [MCP server documentation](https://www.twilio.com/docs/ai/mcp) (`https://mcp.twilio.com/docs`) | Search Twilio, SendGrid, and Segment API documentation and retrieve endpoint schemas across 1,800+ endpoints | None; public API specifications only | `official` `api-docs` `schemas` |

### Finance and Commerce

| Provider / server | Connection details | Capabilities | Auth | Tags |
| --- | --- | --- | --- | --- |
| AgentServices | [MCP details](https://agentservices.to) (`https://api.agentservices.to/mcp`) | x402-paid crypto and market data APIs — BTC indicators, DeFi stats, macro data, exchange analytics, 54 services, and 37 MCP tools | No API key; x402 USDC payment for paid tools | `official` `market-data` `crypto` |
| Klaviyo | [MCP server documentation](https://developers.klaviyo.com/en/docs/klaviyo_mcp_server) (`https://mcp.klaviyo.com/mcp`) | Campaigns, flows, performance reports, templates, and Klaviyo account data | Klaviyo OAuth; Owner, Admin, or Manager role required | `official` `marketing` `campaigns` |
| Shopify Storefront MCP | [Storefront MCP server documentation](https://shopify.dev/docs/apps/build/storefront-mcp/servers/storefront) (`https://{shop}.myshopify.com/api/mcp`) | Store catalogs, product search, policies, carts, and storefront commerce flows; UCP catalog tools use `/api/ucp/mcp` | None for Storefront MCP/cart endpoints; checkout and customer-account flows may require auth | `official` `commerce` `shopping` |
| Stripe | [MCP documentation](https://docs.stripe.com/mcp) (`https://mcp.stripe.com/`) | Payments, billing, products, customers, and Stripe documentation | Stripe OAuth or restricted API key | `official` `payments` `billing` |

### Productivity

| Provider / server | Connection details | Capabilities | Auth | Tags |
| --- | --- | --- | --- | --- |
| Asana | [MCP integration guide](https://developers.asana.com/docs/integrating-with-asanas-mcp-server) (`https://mcp.asana.com/v2/mcp`) | Work graph, tasks, projects, and planning workflows | Asana OAuth 2.0 (MCP app) | `official` `project-management` `tasks` |
| Atlassian Rovo | [Rovo MCP overview](https://developer.atlassian.com/cloud/rovo-mcp/) (`https://mcp.atlassian.com/v1/mcp`) | Jira issues, Confluence pages, Compass components, Bitbucket, and cross-product search | Atlassian OAuth 2.1 or API token | `official` `jira` `confluence` |
| HubSpot | [MCP server documentation](https://developers.hubspot.com/ai-tools/mcp) (`https://mcp.hubspot.com`) | CRM objects, engagements, contacts, companies, deals, tickets, and commerce records | HubSpot OAuth 2.0 (user-level MCP app) | `official` `crm` `sales` |
| Linear | [MCP server guide](https://linear.app/docs/mcp) (`https://mcp.linear.app/mcp`) | Issues, projects, comments, and planning workflows | Linear OAuth or API key | `official` `project-management` `issues` |
| monday.com | [MCP integration guide](https://developer.monday.com/api-reference/docs/integrate-with-monday-mcp) (`https://mcp.monday.com/mcp`) | Boards, items, documents, and workflows through 60+ read/write tools | monday.com OAuth 2.0 or personal API token | `official` `project-management` `workflows` |
| Notion | [Connection guide](https://developers.notion.com/guides/mcp/get-started-with-mcp) (`https://mcp.notion.com/mcp`) | Workspace search, pages, and content management | Notion account (OAuth) | `official` `knowledge-base` `documents` |
| Salesforce Hosted MCP | [Hosted MCP server documentation](https://developer.salesforce.com/docs/platform/hosted-mcp-servers/guide/hosted-mcp-servers-overview.html) (`https://api.salesforce.com/platform/mcp/v1/platform/sobject-all`) | Salesforce object CRUD, queries, search, Data 360, Tableau, and configurable Apex/Flow tools across hosted servers | Salesforce OAuth 2.0 with PKCE; an org admin must enable the server; URLs vary by org and server | `official` `crm` `enterprise` |
| ServiceNow | [MCP server documentation](https://www.servicenow.com/docs/r/intelligent-experiences/create-mcp-server.html) (`https://<instance>.service-now.com/sncapps/mcp-server/mcp/<server-name>`) | Configurable tools for IT, HR, and business workflows exposed from a ServiceNow instance | ServiceNow subscription/entitlement, admin-created server, and OAuth inbound integration | `official` `itsm` `automation` |

### Design and Creative

| Provider / server | Connection details | Capabilities | Auth | Tags |
| --- | --- | --- | --- | --- |
| Canva | [MCP documentation](https://www.canva.dev/docs/mcp/) (`https://mcp.canva.com/mcp`) | Design creation and editing, asset and brand management, library search, exports, and comments | Canva OAuth (per-user) | `official` `design` `assets` |
| Figma | [Remote server setup](https://developers.figma.com/docs/figma-mcp-server/remote-server-installation/) (`https://mcp.figma.com/mcp`) | Design context, code generation, canvas editing, and FigJam | Figma account (OAuth) | `official` `design` `figjam` |
| Miro | [MCP server documentation](https://developers.miro.com/docs/miro-mcp) (`https://mcp.miro.com/`) | Search and summarize boards, create diagrams, and add board content such as frames, cards, shapes, and tables | Miro OAuth | `official` `whiteboards` `collaboration` |
| Webflow | [MCP server documentation](https://developers.webflow.com/mcp/reference/how-it-works) (`https://mcp.webflow.com/mcp`) | Site authoring, CMS content, styles, components, variables, pages, assets, and Designer context | Webflow OAuth; the Bridge App is required for live Designer capabilities | `official` `website-builder` `design` |

### Browser and Automation

| Provider / server | Connection details | Capabilities | Auth | Tags |
| --- | --- | --- | --- | --- |
| Zapier | [MCP client guide](https://help.zapier.com/hc/en-us/articles/36265392843917-Use-Zapier-MCP-with-your-client) (`https://mcp.zapier.com/api/v1/connect`) | Connect AI clients to actions across Zapier's 9,000+ app ecosystem | Zapier connection token (Bearer) | `official` `automation` `workflows` |

### Communication

| Provider / server | Connection details | Capabilities | Auth | Tags |
| --- | --- | --- | --- | --- |
| Intercom | [MCP guide](https://developers.intercom.com/docs/guides/mcp) (`https://mcp.intercom.com/mcp`) | Conversations, contacts, companies, users, and Help Center articles | Intercom OAuth or bearer token; US-hosted workspaces | `official` `customer-support` `conversations` |
| Slack | [MCP server overview](https://docs.slack.dev/ai/slack-mcp-server/) (`https://mcp.slack.com/mcp`) | Search messages, files, users, and channels; read and send messages; manage canvases and reactions | Slack OAuth with a registered app | `official` `messaging` `collaboration` |

### Data and Databases

| Provider / server | Connection details | Capabilities | Auth | Tags |
| --- | --- | --- | --- | --- |
| Airtable | [MCP server guide](https://support.airtable.com/v1/docs/using-the-airtable-mcp-server) (`https://mcp.airtable.com/mcp`) | Bases, tables, schemas, records, comments, and workspace data | Airtable OAuth or PAT | `official` `databases` `no-code` |
| Neon | [MCP server overview](https://neon.com/docs/ai/neon-mcp-server) (`https://mcp.neon.tech/mcp`) | Projects, branches, databases, SQL, schema changes, and branch-based migrations | Neon OAuth or API key for remote agents | `official` `postgres` `database` |
| Snowflake | [Snowflake-managed MCP server documentation](https://docs.snowflake.com/en/user-guide/snowflake-cortex/cortex-agents-mcp) (`https://<account_url>/api/v2/databases/<database>/schemas/<schema>/mcp-servers/<name>`) | Cortex Analyst, Cortex Search, Cortex Agents, custom tools, and governed SQL execution | Snowflake OAuth by default or External OAuth; account/database/schema/server setup required | `official` `data-warehouse` `analytics` |
| Supabase | [MCP server documentation](https://supabase.com/docs/guides/ai-tools/mcp) (`https://mcp.supabase.com/mcp`) | Project-scoped database, docs, debugging, development, functions, branching, and storage tools | Supabase OAuth or PAT | `official` `database` `backend` |

### Files and Storage

| Provider / server | Connection details | Capabilities | Auth | Tags |
| --- | --- | --- | --- | --- |
| Box | [MCP server guide](https://developer.box.com/guides/box-mcp) (`https://mcp.box.com`) | Files, folders, search, collaboration, Box AI queries, hubs, and document generation | Box OAuth; admin enablement may be required | `official` `documents` `enterprise` |
| Dropbox | [Remote MCP setup](https://help.dropbox.com/integrations/connect-dropbox-mcp-server) (`https://mcp.dropbox.com/mcp`) | File and folder search, content extraction, file creation, sharing, revisions, restore, and transcription | Dropbox OAuth; custom clients need app credentials | `official` `files` `storage` |

### Cloud and Infrastructure

| Provider / server | Connection details | Capabilities | Auth | Tags |
| --- | --- | --- | --- | --- |
| Cloudflare API | [Managed MCP server documentation](https://developers.cloudflare.com/agents/model-context-protocol/cloudflare/servers-for-cloudflare/) (`https://mcp.cloudflare.com/mcp`) | DNS, Workers, R2, Zero Trust, and other Cloudflare API operations through search and execute tools | Cloudflare OAuth or scoped API token | `official` `cloud` `workers` |
| Vercel | [MCP server documentation](https://vercel.com/docs/agent-resources/vercel-mcp) (`https://mcp.vercel.com`) | Documentation search, project and deployment management, and deployment-log analysis | Vercel OAuth | `official` `hosting` `deployments` |

### Monitoring and Security

| Provider / server | Connection details | Capabilities | Auth | Tags |
| --- | --- | --- | --- | --- |
| Datadog | [MCP server documentation](https://docs.datadoghq.com/mcp_server/) (`https://mcp.datadoghq.com/v1/mcp`, US1) | APM, logs, metrics, monitors, dashboards, security signals, and observability workflows | Datadog OAuth 2.0, PAT/SAT, or API/application keys | `official` `observability` `monitoring` |
| Grafana Cloud | [Cloud MCP server documentation](https://grafana.com/docs/grafana-cloud/ai-tools/mcp-servers/cloud-mcp/) (`https://mcp.grafana.com/mcp`) | Metrics, logs, dashboards, alerts, incidents, investigations, and other Grafana Cloud observability data | Grafana OAuth 2.1; Grafana Cloud role/permission and Assistant access required | `official` `observability` `metrics` |
| Sentry | [MCP server documentation](https://mcp.sentry.dev/) (`https://mcp.sentry.dev/mcp`) | Error issues, events, traces, performance, projects, releases, and debugging workflows | Sentry OAuth | `official` `error-tracking` `observability` |

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

**Auth** identifies the credentials or account needed to use a server; `none`
should be used only when the server truly requires no authentication.

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
