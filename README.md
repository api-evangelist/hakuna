# Hakuna

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

hakuna AG is a Swiss digital time-tracking and personnel-management platform for SMEs. The browser- and mobile-based product centralizes workforce administration: time recording with a running timer, absence and vacation management, expense processing, project and client tracking, task categorization, shift planning, personnel records, and compliance monitoring against Swiss labor-law requirements. hakuna is "100% Swiss" — all data is stored in Switzerland under Swiss data-protection law (DSG) — and requires no additional hardware terminals or badges. It exposes a token-authenticated REST API (X-Auth-Token) over JSON at app.hakuna.ch/api/v1 covering the timer, time entries, absences, projects, tasks, clients, users, company settings, and an organization-wide presence status endpoint, with admin-only management endpoints and a documented 100 requests/minute rate limit.

**Areas:** Company · Time Tracking · Human Resources · Workforce Management · Absence Management · Project Tracking · Software-as-a-Service · Switzerland · Small Business

## Hakuna on APIs.io

Everything profiled for Hakuna is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/hakuna/](https://apis.io/providers/hakuna/)** — or go straight to one of the APIs or properties below.

### APIs (10)

- [Hakuna Absences API](https://apis.io/apis/hakuna/hakuna-absences-api/) — Absence records and absence categories
- [Hakuna Company API](https://apis.io/apis/hakuna/hakuna-company-api/) — Account-wide settings
- [Hakuna Management API](https://apis.io/apis/hakuna/hakuna-management-api/) — Admin-only management of projects, clients and tasks
- [Hakuna Organization API](https://apis.io/apis/hakuna/hakuna-organization-api/) — Organization-wide presence and absence status
- [Hakuna Overview API](https://apis.io/apis/hakuna/hakuna-overview-api/) — Aggregate metrics for the authenticated user
- [Hakuna Projects API](https://apis.io/apis/hakuna/hakuna-projects-api/) — Active and archived projects
- [Hakuna Tasks API](https://apis.io/apis/hakuna/hakuna-tasks-api/) — Categorization tasks
- [Hakuna Time Entries API](https://apis.io/apis/hakuna/hakuna-time-entries-api/) — Recorded blocks of worked time
- [Hakuna Timer API](https://apis.io/apis/hakuna/hakuna-timer-api/) — The single running timer for the authenticated user
- [Hakuna Users API](https://apis.io/apis/hakuna/hakuna-users-api/) — Users of the account

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### MCP servers (1)

Model Context Protocol servers that expose the API to agents.

- [hakuna](https://apis.io/servers/hakuna/hakuna/)

#### Agentic access (1)

Which operations an agent can call, which act, and which need a human in the loop.

- [Hakuna Agentic Access](https://apis.io/agentic-access/hakuna/hakuna-agentic-access/)

#### Collections (10)

Postman and Open Collection request collections.

- [hakuna Time Tracking Absences API](https://apis.io/collections/hakuna/open-hakuna-absences-api/)
- [hakuna Time Tracking Absences Company API](https://apis.io/collections/hakuna/open-hakuna-company-api/)
- [hakuna Time Tracking Absences Management API](https://apis.io/collections/hakuna/open-hakuna-management-api/)
- [hakuna Time Tracking Absences Organization API](https://apis.io/collections/hakuna/open-hakuna-organization-api/)
- [hakuna Time Tracking Absences Overview API](https://apis.io/collections/hakuna/open-hakuna-overview-api/)
- [hakuna Time Tracking Absences Projects API](https://apis.io/collections/hakuna/open-hakuna-projects-api/)
- [hakuna Time Tracking Absences Tasks API](https://apis.io/collections/hakuna/open-hakuna-tasks-api/)
- [hakuna Time Tracking Absences Time Entries API](https://apis.io/collections/hakuna/open-hakuna-time-entries-api/)
- [hakuna Time Tracking Absences Timer API](https://apis.io/collections/hakuna/open-hakuna-timer-api/)
- [hakuna Time Tracking Absences Users API](https://apis.io/collections/hakuna/open-hakuna-users-api/)

#### Overlays (1)

OpenAPI overlays, including conversational phrasing for each operation.

- [Hakuna Openapi Overlay](https://apis.io/overlays/hakuna/hakuna-openapi-overlay/)

#### Security (2)

Authentication, trust centre, and vulnerability disclosure.

- [Hakuna Authentication](https://apis.io/security/hakuna/hakuna-authentication/)
- [Hakuna Domain Security](https://apis.io/security/hakuna/hakuna-domain-security/)

#### Rate limits (1)

Published request limits.

- [Hakuna Rate Limits](https://apis.io/rate-limits/hakuna/hakuna-rate-limits/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://www.hakuna.ch)
- [Documentation](https://www.hakuna.ch/docs)
- [API reference](https://app.hakuna.ch/api_docs)
- [Pricing](https://www.hakuna.ch/preise)
- [Sign up](https://app.hakuna.ch/sign_up)
- [Support](https://www.hakuna.ch/kontakt)
- [Blog](https://www.hakuna.ch/blog)
- [Terms of service](https://www.hakuna.ch/rechtliches/agb)
- [Privacy policy](https://www.hakuna.ch/rechtliches/datenschutz)

## API Evangelist rating

**Kin Score 33.4** — thin · rubric 0.24.0 · scored 2026-10-17

| Facet | Score |
|---|---|
| Discoverability | 73.2 |
| Contract quality | 17.2 |
| Contract governance | 4.5 |
| Operational transparency | 21.1 |
| Developer ergonomics | 47.0 |
| Access clarity | 44.7 |

**Agent readiness 23.9** — agent-aware

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | yes |
| Agentic Access | derived (partial credit) |
| Reversibility Documented | — |
| MCP Server | — |
| Auth Clarity | bearer (partial credit) |
| Idempotency | — |
| Error Semantics | derived (partial credit) |
| OpenAPI Examples | — |
| Rate Limit Signal | verified |
| Event Surface Described | — |
| Agent Skills | derived (partial credit) |
| Well Known Catalog | — |
| Consent Identity | — |
| Agent Card | — |
| Dry Run Mode | — |
| Delegated Identity | — |
| Protected Resource Metadata | — |
| Dynamic Client Registration | — |
| Agentic Commerce | — |

**Regulatory alignment 24.5** — Employment & Payroll

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/hakuna/](https://apis.io/providers/hakuna/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for Hakuna: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/hakuna/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
