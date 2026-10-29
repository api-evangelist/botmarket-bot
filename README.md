# KOA Labs

<!-- API-EVANGELIST-PROVENANCE:BEGIN -->
> ### About this repository
>
> **This is not our API.** This repository is an independent, third-party profile of a company's
> **publicly available** API surface, maintained by [API Evangelist](https://apievangelist.com).
> API Evangelist does not operate, host, resell, or support this company's APIs, and is not
> affiliated with or endorsed by the company unless stated on the profile.
>
> **Where the information came from.** Everything here is assembled from material a member of the
> public can reach with a browser and no credentials — the company's own website, developer portal
> and documentation, the specifications it publishes for public use (OpenAPI, AsyncAPI, JSON Schema,
> `apis.json`, `llms.txt` and similar), its public repositories, and its public status, pricing and
> changelog pages. **Nothing here is obtained by breaching a system, defeating an access control, or
> using credentials of any kind.**
>
> **The rating is an independent assessment.** The Kin Score and Agent Readiness rating are
> independently calculated scores of a company's *public* API artifacts, produced by API Evangelist
> against a published rubric. They are not certifications, endorsements, security assessments, or
> audits, and they score published artifacts — not the quality, safety, or security of the software.
>
> **Corrections, re-scores, and removal are free.** No partnership, contract, or purchase is
> required, and you do not need to justify the request.
>
> - **Something wrong?** Open an issue on this repository, or email
>   [info@apievangelist.com](mailto:info@apievangelist.com).
> - **Published something new?** Ask for a re-score and we will re-run the rating.
> - **Want the listing taken down?** Say so and we will honor it. The profile is reduced to your
>   company name, a factual description, and a link to your own site, and the company is recorded as
>   **unrated** — never scored zero for having asked.
>
> **Response times.** Acknowledgement within **one business day**; removal or restriction within
> **two business days**; corrections and re-scores within **five business days**.
>
> **Not from the company, and here with a question?** You are welcome here — we would rather be the
> front line and point you the right way than have a good report go nowhere. What this repository
> can answer is narrow, though, so it is worth knowing who you are actually looking for:
>
> - **A question about how the API works, an account, billing, or a bug in the service** — that is
>   the company's own support, not us. We profile this API; we do not operate it and cannot see
>   your account.
> - **A bug in an open-source project we only catalog** — file it on that project's own repository.
>   This has happened with a real and correct bug report that reached us instead of the people who
>   could fix it, which helped nobody.
> - **Anything about this listing itself** — the description, the tags, the rating, a missing or
>   wrong artifact — is ours. Open an issue here.
> - **Not sure, or something general about API Evangelist or APIs.io** — open an issue on the
>   [APIs.io Inbox](https://github.com/api-search/inbox) and we will route it.
>
> **This repository contains no software, and we will never ask you to download anything.** There is
> no build, release, installer, or binary here — only text and machine-readable API descriptions, so
> there is nothing here that can be "corrupt" or need "repairing". Any issue, comment, or email
> claiming otherwise and offering a download link is not from us and is hostile. Do not follow the
> link; it is a lure. Report it to GitHub and, if you like, tell us at
> [info@apievangelist.com](mailto:info@apievangelist.com) so we can take it down.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

KOA Labs is a one-person "solo + AI" software studio in Mexico City (koalabs.ai) that builds open protocols, registries and directories, and BotMarket (botmarket.bot) is its free, non-profit marketplace and registry for AI agents and MCP servers — 115,065 MCP servers, 3,615 A2A-style agents and 25 agent and payment protocols re-gathered hourly from public catalogs (Glama, mcp.so, Smithery, the Official MCP Registry, Hugging Face, Docker, x402 Bazaar) with every record credited to its source. The surface is anonymous and rate-limited per IP (10/s, 100/min, 1,000/h) with no signup and no token: a documented but unspecified REST read surface at https://botmarket.bot/v1 plus POST /v1/submit with a dry_run flag, and a live remote MCP server at https://botmarket.bot/mcp (protocol 2025-06-18, six read-only tools with real inputSchemas). Discovery is published as llms.txt, an OpenAI ai-plugin.json, an OpenSearch description, an MCP server card and an agent card at /.well-known/agent-card.json that is served and owned but not A2A conformant (capabilities is an array, no protocolVersion, no skills, no A2A endpoint). The OpenAPI both llms.txt and ai-plugin.json advertise at /openapi.json is not served (404), so no machine-readable REST contract exists. Optional tipping over x402 / MTP is advertised in a response header; nothing is paywalled.

**Areas:** Agents · MCP · A2A · Agent Discovery · Marketplace · Directory · Protocol · x402 · Open Data · Agent-Native · Non-Profit · Mexico

## KOA Labs on APIs.io

Everything profiled for KOA Labs is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/botmarket-bot/](https://apis.io/providers/botmarket-bot/)** — or go straight to one of the APIs or properties below.

### APIs (2)

- [BotMarket REST API](https://apis.io/apis/botmarket-bot/botmarket-rest-api/) — Anonymous JSON read surface for the BotMarket directory at https://botmarket.bot/v1 — documented in llms.txt rather than in a contract: GET /v1/mcps?q=,…
- [BotMarket MCP Server](https://apis.io/apis/botmarket-bot/botmarket-mcp-server/) — Remote Model Context Protocol server at https://botmarket.bot/mcp (JSON-RPC 2.0 over HTTP, POST only, protocol version 2025-06-18, serverInfo botmarket…

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### MCP servers (1)

Model Context Protocol servers that expose the API to agents.

- [botmarket-bot-mcp.yml](https://apis.io/servers/botmarket-bot/botmarket-bot-mcp-yml/)

#### Security (2)

Authentication, trust centre, and vulnerability disclosure.

- [Botmarket Bot Authentication](https://apis.io/security/botmarket-bot/botmarket-bot-authentication/)
- [Botmarket Bot Domain Security](https://apis.io/security/botmarket-bot/botmarket-bot-domain-security/)

#### Plans and pricing (1)

Published plans, tiers and prices.

- [Botmarket Bot Plans Pricing](https://apis.io/plans/botmarket-bot/botmarket-bot-plans-pricing/)

#### Rate limits (1)

Published request limits.

- [Botmarket Bot Rate Limits](https://apis.io/rate-limits/botmarket-bot/botmarket-bot-rate-limits/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://botmarket.bot/)
- [Documentation](https://botmarket.bot/llms.txt)
- [Pricing](https://botmarket.bot/llms.txt)
- [Blog](https://botmarket.bot/blog/)
- [GitHub](https://github.com/koalabs-ai)

## API Evangelist rating

**Kin Score 26.1** — emerging · rubric 0.25.0 · scored 2026-10-23

| Facet | Score |
|---|---|
| Discoverability | 75.0 |
| Contract quality | 0.0 |
| Contract governance | 18.2 |
| Operational transparency | 36.8 |
| Developer ergonomics | 23.8 |
| Access clarity | 31.6 |

**Agent readiness 12.8** — agent-aware

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | — |
| Agentic Access | — |
| Reversibility Documented | — |
| MCP Server | documented (partial credit) |
| Auth Clarity | bearer (partial credit) |
| Idempotency | — |
| Error Semantics | documented (partial credit) |
| OpenAPI Examples | — |
| Rate Limit Signal | documented (partial credit) |
| Event Surface Described | — |
| Agent Skills | — |
| Well Known Catalog | — |
| Consent Identity | — |
| Agent Card | flavored (partial credit) |
| Dry Run Mode | — |
| Delegated Identity | — |
| Protected Resource Metadata | — |
| Dynamic Client Registration | — |
| Agentic Commerce | — |
| Pagination Ratio | na |
| Operation Distinctiveness | na |

**Regulatory alignment 16.7** — Government & Public Sector

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/botmarket-bot/](https://apis.io/providers/botmarket-bot/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for KOA Labs: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/botmarket-bot/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
