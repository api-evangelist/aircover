# Aircover

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

Aircover is an AI-native revenue agent platform for sales teams: specialist AI agents work before, during and after every customer conversation, joining Zoom, Microsoft Teams, Google Meet and Webex calls to surface real-time coaching, objection handling, battlecards and technical answers from live transcription (no recording by default), then generating notes, follow-ups, MEDDPICC-style qualification scoring and CRM updates into Salesforce, HubSpot and ServiceNow. For developers and agents the company publishes a remote Model Context Protocol server at https://api.aircover.ai/mcp (Streamable HTTP, OAuth 2.0 with PKCE and RFC 7591 dynamic client registration, twelve read tools over meetings, transcripts, agent results, deals, teams, reports and documents), an OpenAPI 3.0.3 contract for the public agent API, an MCP registry server.json manifest, llms.txt, markdown content negotiation on every page, four open-source Claude/ChatGPT Skills and a PyPI-published Python pipeline CLI. The full customer REST API and webhooks are customer-only.

**Areas:** Sales Enablement · Conversation Intelligence · Sales Coaching · Revenue Intelligence · AI Agents · MCP · Agent-Native · CRM · Meetings · Transcription · Authentication

## Aircover on APIs.io

Everything profiled for Aircover is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/aircover/](https://apis.io/providers/aircover/)** — or go straight to one of the APIs or properties below.

### APIs (4)

- [Aircover MCP Server](https://apis.io/apis/aircover/aircover-mcp-server/) — Remote Model Context Protocol server over Streamable HTTP at https://api.aircover.ai/mcp. An authenticated Aircover user's agent can list and read meetings…
- [Aircover Discovery API](https://apis.io/apis/aircover/aircover-discovery-api/) — Machine-readable discovery metadata
- [Aircover MCP API](https://apis.io/apis/aircover/aircover-mcp-api/) — Model Context Protocol server (Streamable HTTP transport)
- [Aircover OAuth API](https://apis.io/apis/aircover/aircover-oauth-api/) — OAuth 2.0 authorization server (authorization code + PKCE, dynamic client registration)

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### MCP servers (3)

Model Context Protocol servers that expose the API to agents.

- [ai.aircover/mcp](https://apis.io/servers/aircover/ai-aircover-mcp/)
- [aircover-mcp.yml](https://apis.io/servers/aircover/aircover-mcp-yml/)
- [mcp.json](https://apis.io/servers/aircover/mcp-json/)

#### JSON Schema (4)

The data models the API reads and writes.

- [Aircover Pipeline — agent-outputs/agent_<meeting_id>.json (v1.0)](https://apis.io/schemas/aircover/aircover-pipeline-agent-output-1.0/)
- [Aircover Pipeline — failures.json (v1.0)](https://apis.io/schemas/aircover/aircover-pipeline-failures-1.0/)
- [Aircover Pipeline — meetings.json (v1.0)](https://apis.io/schemas/aircover/aircover-pipeline-meetings-1.0/)
- [Aircover Pipeline — summary.json (v1.0)](https://apis.io/schemas/aircover/aircover-pipeline-summary-1.0/)

#### Overlays (1)

OpenAPI overlays, including conversational phrasing for each operation.

- [Aircover Openapi Overlay](https://apis.io/overlays/aircover/aircover-openapi-overlay/)

#### Security (3)

Authentication, trust centre, and vulnerability disclosure.

- [Aircover Authentication](https://apis.io/security/aircover/aircover-authentication/)
- [Aircover Domain Security](https://apis.io/security/aircover/aircover-domain-security/)
- [Aircover Trust Center](https://apis.io/security/aircover/aircover-trust-center/)

#### OAuth scopes (1)

The permissions the API asks for.

- [Aircover Scopes](https://apis.io/scopes/aircover/aircover-scopes/)

#### Plans and pricing (1)

Published plans, tiers and prices.

- [Aircover Plans Pricing](https://apis.io/plans/aircover/aircover-plans-pricing/)

#### Rate limits (1)

Published request limits.

- [Aircover Rate Limits](https://apis.io/rate-limits/aircover/aircover-rate-limits/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://www.aircover.ai/)
- [Documentation](https://www.aircover.ai/developers)
- [Getting started](https://www.aircover.ai/developers)
- [API reference](https://www.aircover.ai/developers)
- [Pricing](https://www.aircover.ai/pricing)
- [Support](https://www.aircover.ai/contact-us)
- [Changelog](https://github.com/Aircover/aircover-pipeline/blob/main/CHANGELOG.md)
- [Blog](https://www.aircover.ai/blog)
- [Compliance](https://www.aircover.ai/trust-center)
- [Trust centre](https://www.aircover.ai/trust-center)
- [Terms of service](https://www.aircover.ai/terms-and-conditions)
- [Privacy policy](https://www.aircover.ai/privacy-policy)
- [GitHub](https://github.com/Aircover)

## API Evangelist rating

**Kin Score 55.8** — strong · rubric 0.25.0 · scored 2026-10-23

| Facet | Score |
|---|---|
| Discoverability | 75.0 |
| Contract quality | 55.1 |
| Contract governance | 18.2 |
| Operational transparency | 18.4 |
| Developer ergonomics | 78.6 |
| Access clarity | 53.9 |

**Agent readiness 48.1** — agent-ready (gated down from agent-native)

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | yes |
| Agentic Access | — |
| Reversibility Documented | — |
| MCP Server | documented (partial credit) |
| Auth Clarity | served (partial credit) |
| Idempotency | — |
| Error Semantics | verified |
| OpenAPI Examples | — |
| Rate Limit Signal | documented (partial credit) |
| Event Surface Described | — |
| Agent Skills | yes |
| Well Known Catalog | — |
| Consent Identity | — |
| Agent Card | — |
| Dry Run Mode | — |
| Delegated Identity | served (partial credit) |
| Protected Resource Metadata | verified |
| Dynamic Client Registration | yes |
| Agentic Commerce | — |
| Pagination Ratio | na |
| Operation Distinctiveness | distinct |

**Regulatory alignment 43.1** — Horizontal (data, software, accessibility, platform)

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/aircover/](https://apis.io/providers/aircover/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for Aircover: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/aircover/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
