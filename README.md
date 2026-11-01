# Sigma Computing

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

Sigma Computing is a warehouse-first analytics and business-application platform. Instead of extracting data into its own store, Sigma queries the customer's cloud data warehouse live — Snowflake, Databricks, BigQuery, Redshift, Amazon Athena, PostgreSQL and ClickHouse — and puts a spreadsheet-style interface, governed data models, input tables with write-back, pixel-perfect paginated reports, embedded white-label analytics and AI agents on top of it. The developer surface is a 274-operation REST API (OpenAPI 3.1) covering workbooks, data models, reports, connections, members, teams, workspaces, permissions, user attributes, tenants, templates and API connectors; a first-party Rust CLI generated from that same OpenAPI; a remote OAuth-protected MCP server that lets AI assistants search, describe and query governed data in natural language; JavaScript embed and plugin SDKs; and three Apache-2.0 agent skills Sigma publishes for Claude Code, Cursor, Codex and Snowflake Cortex Code.

**Areas:** Business Intelligence · Analytics · Embedded Analytics · Data Modeling · Data Warehouse · Reporting · Spreadsheets · MCP · AI Agents · Snowflake · Databricks · Data Governance

## Sigma Computing on APIs.io

Everything profiled for Sigma Computing is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/sigma-computing/](https://apis.io/providers/sigma-computing/)** — or go straight to one of the APIs or properties below.

### APIs (36)

- [Sigma MCP Server](https://apis.io/apis/sigma-computing/sigma-mcp-server/) — Sigma's first-party remote Model Context Protocol server. AI assistants such as Claude, ChatGPT, Codex, Cursor and Snowflake Cortex Code connect over HTTP…
- [Sigma Embed API](https://apis.io/apis/sigma-computing/sigma-embed-api/) — Secure embedding of Sigma workbooks, pages and individual elements into a host application. Embed URLs are signed with JSON Web Tokens carrying the viewing…
- [Sigma Computing Auth API](https://apis.io/apis/sigma-computing/sigma-computing-auth-api/) — The Auth API from Sigma Computing — 1 operation(s) for auth.
- [Sigma Computing Connections API](https://apis.io/apis/sigma-computing/sigma-computing-connections-api/) — The Connections API from Sigma Computing — 13 operation(s) for connections.
- [Sigma Computing Credentials API](https://apis.io/apis/sigma-computing/sigma-computing-credentials-api/) — The Credentials API from Sigma Computing — 2 operation(s) for credentials.
- [Sigma Computing Datasets API](https://apis.io/apis/sigma-computing/sigma-computing-datasets-api/) — The Datasets API from Sigma Computing — 7 operation(s) for datasets.
- [Sigma Computing Deployment Policies API](https://apis.io/apis/sigma-computing/sigma-computing-deploymentpolicies-api/) — The deploymentPolicies API from Sigma Computing — 7 operation(s) for deploymentpolicies.
- [Sigma Computing Favorites API](https://apis.io/apis/sigma-computing/sigma-computing-favorites-api/) — The Favorites API from Sigma Computing — 3 operation(s) for favorites.
- [Sigma Computing Files API](https://apis.io/apis/sigma-computing/sigma-computing-files-api/) — The Files API from Sigma Computing — 2 operation(s) for files.
- [Sigma Computing Grants API](https://apis.io/apis/sigma-computing/sigma-computing-grants-api/) — The Grants API from Sigma Computing — 2 operation(s) for grants.
- [Sigma Computing Members API](https://apis.io/apis/sigma-computing/sigma-computing-members-api/) — The Members API from Sigma Computing — 9 operation(s) for members.
- [Sigma Computing Organizations API](https://apis.io/apis/sigma-computing/sigma-computing-organizations-api/) — The Organizations API from Sigma Computing — 4 operation(s) for organizations.
- [Sigma Computing Plugins API](https://apis.io/apis/sigma-computing/sigma-computing-plugins-api/) — The plugins API from Sigma Computing — 2 operation(s) for plugins.
- [Sigma Computing Query API](https://apis.io/apis/sigma-computing/sigma-computing-query-api/) — The Query API from Sigma Computing — 1 operation(s) for query.
- [Sigma Computing Reports API](https://apis.io/apis/sigma-computing/sigma-computing-reports-api/) — The Reports API from Sigma Computing — 26 operation(s) for reports.
- [Sigma Computing SAML API](https://apis.io/apis/sigma-computing/sigma-computing-saml-api/) — The SAML API from Sigma Computing — 5 operation(s) for saml.
- [Sigma Computing Shortcuts API](https://apis.io/apis/sigma-computing/sigma-computing-shortcuts-api/) — The shortcuts API from Sigma Computing — 1 operation(s) for shortcuts.
- [Sigma Computing Source Swap Policies API](https://apis.io/apis/sigma-computing/sigma-computing-sourceswappolicies-api/) — The sourceSwapPolicies API from Sigma Computing — 2 operation(s) for sourceswappolicies.
- [Sigma Computing Tags API](https://apis.io/apis/sigma-computing/sigma-computing-tags-api/) — The Tags API from Sigma Computing — 3 operation(s) for tags.
- [Sigma Computing Teams API](https://apis.io/apis/sigma-computing/sigma-computing-teams-api/) — The Teams API from Sigma Computing — 6 operation(s) for teams.
- [Sigma Computing Templates API](https://apis.io/apis/sigma-computing/sigma-computing-templates-api/) — The Templates API from Sigma Computing — 4 operation(s) for templates.
- [Sigma Computing Tenants API](https://apis.io/apis/sigma-computing/sigma-computing-tenants-api/) — The Tenants API from Sigma Computing — 6 operation(s) for tenants.
- [Sigma Computing Translations API](https://apis.io/apis/sigma-computing/sigma-computing-translations-api/) — The Translations API from Sigma Computing — 3 operation(s) for translations.
- [Sigma Computing Webhooks API](https://apis.io/apis/sigma-computing/sigma-computing-webhooks-api/) — The Webhooks API from Sigma Computing — 2 operation(s) for webhooks.
- [Sigma Computing Whoami API](https://apis.io/apis/sigma-computing/sigma-computing-whoami-api/) — The Whoami API from Sigma Computing — 1 operation(s) for whoami.
- [Sigma Computing Workbooks API](https://apis.io/apis/sigma-computing/sigma-computing-workbooks-api/) — The Workbooks API from Sigma Computing — 44 operation(s) for workbooks.
- [Sigma Computing Workspaces API](https://apis.io/apis/sigma-computing/sigma-computing-workspaces-api/) — The Workspaces API from Sigma Computing — 5 operation(s) for workspaces.
- [Sigma Computing Allowed Ips API](https://apis.io/apis/sigma-computing/sigma-computing-allowedips-api/) — The allowedIps API from Sigma Computing — 1 operation(s) for allowedips.
- [Sigma Computing Allowed Ips\:batch Create API](https://apis.io/apis/sigma-computing/sigma-computing-allowedips-batchcreate-api/) — The allowedIps\:batchCreate API from Sigma Computing — 1 operation(s) for allowedips\:batchcreate.
- [Sigma Computing Allowed Ips\:batch Delete API](https://apis.io/apis/sigma-computing/sigma-computing-allowedips-batchdelete-api/) — The allowedIps\:batchDelete API from Sigma Computing — 1 operation(s) for allowedips\:batchdelete.
- [Sigma Computing API Connectors API](https://apis.io/apis/sigma-computing/sigma-computing-api-connectors-api/) — The api-connectors API from Sigma Computing — 2 operation(s) for api-connectors.
- [Sigma Computing API Credentials API](https://apis.io/apis/sigma-computing/sigma-computing-api-credentials-api/) — The api-credentials API from Sigma Computing — 2 operation(s) for api-credentials.
- [Sigma Computing Shared Templates API](https://apis.io/apis/sigma-computing/sigma-computing-shared-templates-api/) — The shared_templates API from Sigma Computing — 3 operation(s) for shared_templates.
- [Sigma Computing User Attributes API](https://apis.io/apis/sigma-computing/sigma-computing-user-attributes-api/) — The user-attributes API from Sigma Computing — 8 operation(s) for user-attributes.
- [Sigma Computing Account Types API](https://apis.io/apis/sigma-computing/sigma-computing-account-types-api/) — The Account Types API from Sigma Computing — 3 operation(s) for account types.
- [Sigma Computing Data models API](https://apis.io/apis/sigma-computing/sigma-computing-data-models-api/) — The Data models API from Sigma Computing — 19 operation(s) for data models.

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### AsyncAPI (1)

Event-driven and webhook contracts.

- [Sigma Computing Webhooks](https://apis.io/asyncapis/sigma-computing/sigma-computing-webhooks/)

#### MCP servers (1)

Model Context Protocol servers that expose the API to agents.

- [Sigma MCP Server](https://apis.io/servers/sigma-computing/sigma-mcp-server/)

#### Overlays (35)

OpenAPI overlays, including conversational phrasing for each operation.

- [Sigma Computing Account Types Api Phrasing Overlay](https://apis.io/overlays/sigma-computing/sigma-computing-account-types-api-phrasing-overlay/)
- [Sigma Computing Allowedips Api Phrasing Overlay](https://apis.io/overlays/sigma-computing/sigma-computing-allowedips-api-phrasing-overlay/)
- [Sigma Computing Allowedips Batchcreate Api Phrasing Overlay](https://apis.io/overlays/sigma-computing/sigma-computing-allowedips-batchcreate-api-phrasing-overlay/)
- [Sigma Computing Allowedips Batchdelete Api Phrasing Overlay](https://apis.io/overlays/sigma-computing/sigma-computing-allowedips-batchdelete-api-phrasing-overlay/)
- [Sigma Computing Api Connectors Api Phrasing Overlay](https://apis.io/overlays/sigma-computing/sigma-computing-api-connectors-api-phrasing-overlay/)
- [Sigma Computing Api Credentials Api Phrasing Overlay](https://apis.io/overlays/sigma-computing/sigma-computing-api-credentials-api-phrasing-overlay/)
- [Sigma Computing Auth Api Phrasing Overlay](https://apis.io/overlays/sigma-computing/sigma-computing-auth-api-phrasing-overlay/)
- [Sigma Computing Connections Api Phrasing Overlay](https://apis.io/overlays/sigma-computing/sigma-computing-connections-api-phrasing-overlay/)
- [Sigma Computing Credentials Api Phrasing Overlay](https://apis.io/overlays/sigma-computing/sigma-computing-credentials-api-phrasing-overlay/)
- [Sigma Computing Data Models Api Phrasing Overlay](https://apis.io/overlays/sigma-computing/sigma-computing-data-models-api-phrasing-overlay/)
- [Sigma Computing Datasets Api Phrasing Overlay](https://apis.io/overlays/sigma-computing/sigma-computing-datasets-api-phrasing-overlay/)
- [Sigma Computing Deploymentpolicies Api Phrasing Overlay](https://apis.io/overlays/sigma-computing/sigma-computing-deploymentpolicies-api-phrasing-overlay/)
- [Sigma Computing Favorites Api Phrasing Overlay](https://apis.io/overlays/sigma-computing/sigma-computing-favorites-api-phrasing-overlay/)
- [Sigma Computing Files Api Phrasing Overlay](https://apis.io/overlays/sigma-computing/sigma-computing-files-api-phrasing-overlay/)
- [Sigma Computing Grants Api Phrasing Overlay](https://apis.io/overlays/sigma-computing/sigma-computing-grants-api-phrasing-overlay/)
- [Sigma Computing Members Api Phrasing Overlay](https://apis.io/overlays/sigma-computing/sigma-computing-members-api-phrasing-overlay/)
- [Sigma Computing Organizations Api Phrasing Overlay](https://apis.io/overlays/sigma-computing/sigma-computing-organizations-api-phrasing-overlay/)
- [Sigma Computing Plugins Api Phrasing Overlay](https://apis.io/overlays/sigma-computing/sigma-computing-plugins-api-phrasing-overlay/)
- [Sigma Computing Query Api Phrasing Overlay](https://apis.io/overlays/sigma-computing/sigma-computing-query-api-phrasing-overlay/)
- [Sigma Computing Reports Api Phrasing Overlay](https://apis.io/overlays/sigma-computing/sigma-computing-reports-api-phrasing-overlay/)
- [Sigma Computing Rest Api Overlay](https://apis.io/overlays/sigma-computing/sigma-computing-rest-api-overlay/)
- [Sigma Computing Saml Api Phrasing Overlay](https://apis.io/overlays/sigma-computing/sigma-computing-saml-api-phrasing-overlay/)
- [Sigma Computing Shared Templates Api Phrasing Overlay](https://apis.io/overlays/sigma-computing/sigma-computing-shared-templates-api-phrasing-overlay/)
- [Sigma Computing Shortcuts Api Phrasing Overlay](https://apis.io/overlays/sigma-computing/sigma-computing-shortcuts-api-phrasing-overlay/)
- [Sigma Computing Sourceswappolicies Api Phrasing Overlay](https://apis.io/overlays/sigma-computing/sigma-computing-sourceswappolicies-api-phrasing-overlay/)
- …and 10 more published on APIs.io

#### Security (4)

Authentication, trust centre, and vulnerability disclosure.

- [Sigma Computing Authentication](https://apis.io/security/sigma-computing/sigma-computing-authentication/)
- [Sigma Computing Domain Security](https://apis.io/security/sigma-computing/sigma-computing-domain-security/)
- [Sigma Computing Trust Center](https://apis.io/security/sigma-computing/sigma-computing-trust-center/)
- [Sigma Computing Vulnerability Disclosure](https://apis.io/security/sigma-computing/sigma-computing-vulnerability-disclosure/)

#### OAuth scopes (1)

The permissions the API asks for.

- [Sigma Computing Scopes](https://apis.io/scopes/sigma-computing/sigma-computing-scopes/)

#### Plans and pricing (1)

Published plans, tiers and prices.

- [Sigma Computing Plans Pricing](https://apis.io/plans/sigma-computing/sigma-computing-plans-pricing/)

#### Rate limits (1)

Published request limits.

- [Sigma Computing Rate Limits](https://apis.io/rate-limits/sigma-computing/sigma-computing-rate-limits/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://www.sigmacomputing.com/)
- [Documentation](https://help.sigmacomputing.com/docs/get-started-with-sigmas-api)
- [Getting started](https://help.sigmacomputing.com/reference/get-started-sigma-api)
- [API reference](https://help.sigmacomputing.com/reference/get-started-sigma-api)
- [Pricing](https://www.sigmacomputing.com/company/contact-us)
- [Sign up](https://www.sigmacomputing.com/go/free-trial)
- [Support](https://help.sigmacomputing.com/docs/sigma-support)
- [Changelog](https://help.sigmacomputing.com/changelog)
- [Blog](https://www.sigmacomputing.com/blog)
- [Security](https://www.sigmacomputing.com/product/vdp)
- [Terms of service](https://www.sigmacomputing.com/legal/terms-of-service)
- [Privacy policy](https://www.sigmacomputing.com/legal/privacy-policy)
- [GitHub](https://github.com/sigmacomputing)
- [Status](https://status.sigmacomputing.com)

## API Evangelist rating

**Kin Score 72.4** — exemplar · rubric 0.25.0 · scored 2026-10-23

| Facet | Score |
|---|---|
| Discoverability | 80.0 |
| Contract quality | 60.1 |
| Contract governance | 18.2 |
| Operational transparency | 92.1 |
| Developer ergonomics | 85.7 |
| Access clarity | 60.5 |

**Agent readiness 58.3** — agent-ready (gated down from agent-native)

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | yes |
| Agentic Access | — |
| Reversibility Documented | documented (partial credit) |
| MCP Server | documented (partial credit) |
| Auth Clarity | served (partial credit) |
| Idempotency | documented (partial credit) |
| Error Semantics | derived (partial credit) |
| OpenAPI Examples | partial |
| Rate Limit Signal | documented (partial credit) |
| Event Surface Described | yes |
| Agent Skills | yes |
| Well Known Catalog | yes |
| Consent Identity | — |
| Agent Card | — |
| Dry Run Mode | yes |
| Delegated Identity | served (partial credit) |
| Protected Resource Metadata | verified |
| Dynamic Client Registration | yes |
| Agentic Commerce | — |
| Pagination Ratio | — |
| Operation Distinctiveness | distinct |

**Regulatory alignment 45.1** — Horizontal (data, software, accessibility, platform)

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/sigma-computing/](https://apis.io/providers/sigma-computing/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for Sigma Computing: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/sigma-computing/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
