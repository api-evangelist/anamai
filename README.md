# Anam.ai

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

Anam.ai is a real-time interactive AI avatar platform for building conversational video AI agents with photorealistic personas. Its proprietary CARA-4 avatar model streams over WebRTC with ultra-low latency (around 180ms) across 70+ languages, powering customer support, sales, tutoring, medical, and training use cases. The REST API (https://api.anam.ai/v1/) lets teams create and manage personas, avatars, voices, LLM configs, RAG knowledge groups, tools, share links, and sessions, and invite personas into Google Meet, Zoom, and Microsoft Teams calls via the Meetings API. Auth is a two-step Bearer flow (API key exchanged for a short-lived session token). Anam is HIPAA and SOC 2 certified. Surfaced as a Techstars portfolio company and enriched into the API Evangelist network.

**Areas:** Company · AI Avatars · Conversational AI · Real-Time Video · WebRTC · Digital Humans · Generative AI

## Anam.ai on APIs.io

Everything profiled for Anam.ai is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/anamai/](https://apis.io/providers/anamai/)** — or go straight to one of the APIs or properties below.

### APIs (10)

- [Anam.ai Avatars API](https://apis.io/apis/anamai/anamai-avatars-api/) — The Avatars API from Anam.ai — 2 operation(s) for avatars.
- [Anam.ai Engine API](https://apis.io/apis/anamai/anamai-engine-api/) — The Engine API from Anam.ai — 1 operation(s) for engine.
- [Anam.ai Knowledge API](https://apis.io/apis/anamai/anamai-knowledge-api/) — The Knowledge API from Anam.ai — 6 operation(s) for knowledge.
- [Anam.ai Meetings API](https://apis.io/apis/anamai/anamai-meetings-api/) — The Meetings API from Anam.ai — 2 operation(s) for meetings.
- [Anam.ai Personas API](https://apis.io/apis/anamai/anamai-personas-api/) — The Personas API from Anam.ai — 2 operation(s) for personas.
- [Anam.ai Sessions API](https://apis.io/apis/anamai/anamai-sessions-api/) — The Sessions API from Anam.ai — 9 operation(s) for sessions.
- [Anam.ai Share Links API](https://apis.io/apis/anamai/anamai-share-links-api/) — The Share Links API from Anam.ai — 2 operation(s) for share links.
- [Anam.ai Tools API](https://apis.io/apis/anamai/anamai-tools-api/) — The Tools API from Anam.ai — 2 operation(s) for tools.
- [Anam.ai Voices API](https://apis.io/apis/anamai/anamai-voices-api/) — The Voices API from Anam.ai — 3 operation(s) for voices.
- [Anam.ai LL Ms API](https://apis.io/apis/anamai/anamai-llms-api/) — The LLMs API from Anam.ai — 2 operation(s) for llms.

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### MCP servers (1)

Model Context Protocol servers that expose the API to agents.

- [anam](https://apis.io/servers/anamai/anam/)

#### Agentic access (1)

Which operations an agent can call, which act, and which need a human in the loop.

- [Anamai Agentic Access](https://apis.io/agentic-access/anamai/anamai-agentic-access/)

#### Collections (20)

Postman and Open Collection request collections.

- [Anam AI Avatars API](https://apis.io/collections/anamai/open-anamai-avatars-api/)
- [Anam AI Avatars Engine API](https://apis.io/collections/anamai/open-anamai-engine-api/)
- [Anam AI Avatars Knowledge API](https://apis.io/collections/anamai/open-anamai-knowledge-api/)
- [Anam AI Avatars LLMs API](https://apis.io/collections/anamai/open-anamai-llms-api/)
- [Anam AI Avatars Meetings API](https://apis.io/collections/anamai/open-anamai-meetings-api/)
- [Anam AI Avatars Personas API](https://apis.io/collections/anamai/open-anamai-personas-api/)
- [Anam AI Avatars Sessions API](https://apis.io/collections/anamai/open-anamai-sessions-api/)
- [Anam AI Avatars Share Links API](https://apis.io/collections/anamai/open-anamai-share-links-api/)
- [Anam AI Avatars Tools API](https://apis.io/collections/anamai/open-anamai-tools-api/)
- [Anam AI Avatars Voices API](https://apis.io/collections/anamai/open-anamai-voices-api/)
- [Anam AI Avatars API](https://apis.io/collections/anamai/postman-anamai-avatars-api/)
- [Anam AI Avatars Engine API](https://apis.io/collections/anamai/postman-anamai-engine-api/)
- [Anam AI Avatars Knowledge API](https://apis.io/collections/anamai/postman-anamai-knowledge-api/)
- [Anam AI Avatars LLMs API](https://apis.io/collections/anamai/postman-anamai-llms-api/)
- [Anam AI Avatars Meetings API](https://apis.io/collections/anamai/postman-anamai-meetings-api/)
- [Anam AI Avatars Personas API](https://apis.io/collections/anamai/postman-anamai-personas-api/)
- [Anam AI Avatars Sessions API](https://apis.io/collections/anamai/postman-anamai-sessions-api/)
- [Anam AI Avatars Share Links API](https://apis.io/collections/anamai/postman-anamai-share-links-api/)
- [Anam AI Avatars Tools API](https://apis.io/collections/anamai/postman-anamai-tools-api/)
- [Anam AI Avatars Voices API](https://apis.io/collections/anamai/postman-anamai-voices-api/)

#### Overlays (1)

OpenAPI overlays, including conversational phrasing for each operation.

- [Anamai Openapi Overlay](https://apis.io/overlays/anamai/anamai-openapi-overlay/)

#### Security (4)

Authentication, trust centre, and vulnerability disclosure.

- [Anamai Authentication](https://apis.io/security/anamai/anamai-authentication/)
- [Anamai Domain Security](https://apis.io/security/anamai/anamai-domain-security/)
- [Anamai Trust Center](https://apis.io/security/anamai/anamai-trust-center/)
- [Anamai Vulnerability Disclosure](https://apis.io/security/anamai/anamai-vulnerability-disclosure/)

#### Rate limits (1)

Published request limits.

- [Anamai Rate Limits](https://apis.io/rate-limits/anamai/anamai-rate-limits/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://anam.ai/)
- [Documentation](https://anam.ai/docs)
- [Getting started](https://anam.ai/docs/quickstart)
- [API reference](https://anam.ai/docs/api-reference)
- [Pricing](https://anam.ai/pricing)
- [Sign up](https://lab.anam.ai/register)
- [Blog](https://anam.ai/blog)
- [Security](https://anam.ai/.well-known/security.txt)
- [Compliance](https://trust.anam.ai/)
- [Terms of service](https://anam.ai/terms-of-service)
- [Privacy policy](https://anam.ai/privacy-policy)
- [GitHub](https://github.com/anam-org)
- [Status](https://status.anam.ai/)

## API Evangelist rating

**Kin Score 54.2** — developing · rubric 0.25.0 · scored 2026-10-23

| Facet | Score |
|---|---|
| Discoverability | 73.2 |
| Contract quality | 55.4 |
| Contract governance | 4.5 |
| Operational transparency | 71.1 |
| Developer ergonomics | 67.3 |
| Access clarity | 44.7 |

**Agent readiness 43.6** — agent-native

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | yes |
| Agentic Access | derived (partial credit) |
| Reversibility Documented | documented (partial credit) |
| MCP Server | — |
| Auth Clarity | bearer (partial credit) |
| Idempotency | verified |
| Error Semantics | verified |
| OpenAPI Examples | verified |
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
| Pagination Ratio | partial |
| Operation Distinctiveness | distinct |

**Regulatory alignment 28.2** — AI & Biometrics

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/anamai/](https://apis.io/providers/anamai/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for Anam.ai: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/anamai/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
