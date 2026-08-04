# Contributing to Awesome Public MCP Servers

Thank you for helping build a useful directory of MCP servers. Contributions
should make it easier to discover a server, understand what it does, and
connect to it safely.

## Inclusion Criteria

A submission must:

- Link to an MCP server's official endpoint, connection documentation, or
  publicly maintained source repository.
- Be publicly accessible or publicly installable without a private invitation.
- Clearly identify the server's capabilities and supported MCP transport.
- Be maintained by the provider, a verified organization, or an identifiable
  open-source maintainer.
- Add material value beyond an existing entry.

Do not submit:

- Private, invite-only, or abandoned servers.
- Unofficial wrappers, scraped directories, or duplicate listings.
- Links that require affiliate, referral, tracking, or URL-shortener redirects.
- Entries that hide required credentials, pricing, rate limits, or material
  data-handling terms.
- Servers that expose sensitive actions without clear documentation or an
  appropriate warning.

An upstream API may require the contributor's own credentials. If it does,
say so in the `Auth` column; public availability does not mean that the
upstream service is free or anonymous.

## Adding an Entry

1. Choose the closest category.
2. Add one table row in alphabetical order by server name or provider.
3. Link to the official connection page or repository, not a copied listing.
4. Record the authentication requirement accurately and link to documentation
   that identifies the supported MCP transport.
5. Add concise capability tags and use `official` only when the provider
   publishes or maintains the server.
6. Check that every changed link works and that the Markdown table renders.

Use this row format:

```markdown
| Provider / server | [Connection details](SERVER_URL) | Search, retrieval | API key | `official` `research` |
```

## Pull Requests

Keep each pull request focused. In the description, include:

- The provider or maintainer's official website or repository.
- The connection method and supported transport.
- Whether authentication, an account, payment, or a separate API key is
  required.
- The date on which you verified the link.

By contributing, you agree that your changes to this curated list are
available under [CC0 1.0 Universal](LICENSE). Linked servers, software, and
documentation remain subject to their respective owners' licenses and terms.

## Corrections and Removals

Open an issue or pull request when a link breaks, ownership changes, a server
becomes private, its capabilities materially change, or an entry no longer
meets the inclusion criteria. Include a replacement official source when one
exists.
