# Nanyang Technological University

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

Nanyang Technological University (NTU Singapore) is an autonomous public research university in Singapore, ranked in the top 15 of the QS World University Rankings. Its programmable footprint is small, indirect, and almost entirely research-infrastructure: NTU operates no public developer portal, publishes no API key self-service, and exposes no OAuth or OIDC authorization server on any host it owns. Exactly one machine-readable API is genuinely NTU-operated — DR-NTU (Data), a Dataverse 6.1 open research data repository that NTU self-hosts on its own network (researchdata.ntu.edu.sg CNAMEs to dataverse.ntu.edu.sg at 155.69.19.238, registered to Nanyang Technological University), backed by NTU's own DataCite client GDCC.NTU with 3,625 DOIs under prefix 10.21979. Everything else that carries NTU's name is a tenancy on someone else's platform. DR-NTU (Digital Repository), the far larger surface with 158,100 research profiles, a DSpace 7 REST API and a fully conformant OAI-PMH endpoint, answers on dr.ntu.edu.sg but CNAMEs to ntu-cris.4science.cloud — NTU's data and NTU's library administration running on 4Science's DSpace-CRIS platform. NTU's federated single sign-on is a live SAML 2.0 identity provider in eduGAIN, but the entityID and endpoints sit on SingAREN's SGAF proxy, not on ntu.edu.sg. NTU owns a live API gateway at api.ntu.edu.sg which returns a structured JSON 404 on every path and documents no route at all. This profile records the tenancies as the real institutional facts they are, and credits NTU only for what NTU actually operates.

**Areas:** University · Higher Education · Education · Singapore · Public Research University · Research Data · Research Repository · Identity Federation · Open Access · Course Catalog · Library · OAI-PMH

## Nanyang Technological University on APIs.io

Everything profiled for Nanyang Technological University is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/ntu/](https://apis.io/providers/ntu/)** — or go straight to one of the APIs or properties below.

### APIs (8)

- [DR-NTU (Data) — Dataverse API](https://apis.io/apis/ntu/ntu-drntu-data/) — NTU's institutional open research data repository, running Dataverse 6.1 self-hosted on NTU's own network. The publicly documented, unauthenticated read…
- [DR-NTU (Digital Repository) — DSpace-CRIS REST API](https://apis.io/apis/ntu/ntu-drntu-repository/) — NTU's institutional publications and research-profile repository — 158,100 research profiles, records back to 2008 — served from NTU's own hostname but…
- [DR-NTU (Digital Repository) — OAI-PMH](https://apis.io/apis/ntu/ntu-drntu-repository-oai/) — A fully conformant OAI-PMH 2.0 metadata harvesting endpoint over DR-NTU, serving 11 metadata formats and declaring OpenAIRE CERIF-CRIS 1.1 compatibility on…
- [NTU Identity Provider — SGAF / eduGAIN](https://apis.io/apis/ntu/ntu-identity-federation/) — NTU's SAML 2.0 identity provider, registered in the Singapore Access Federation (SGAF) by SingAREN and interfederated into eduGAIN, asserting the scope…
- [Nanyang Technological University Discover API](https://apis.io/apis/ntu/ntu-discover-api/) — The Discover API from Nanyang Technological University — 1 operation(s) for discover.
- [Nanyang Technological University Items API](https://apis.io/apis/ntu/ntu-items-api/) — The Items API from Nanyang Technological University — 1 operation(s) for items.
- [Nanyang Technological University OAI PMH API](https://apis.io/apis/ntu/ntu-oai-pmh-api/) — The OAI-PMH API from Nanyang Technological University — 1 operation(s) for oai-pmh.
- [Nanyang Technological University Root API](https://apis.io/apis/ntu/ntu-root-api/) — The Root API from Nanyang Technological University — 1 operation(s) for root.

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### Agentic access (1)

Which operations an agent can call, which act, and which need a human in the loop.

- [Ntu Agentic Access](https://apis.io/agentic-access/ntu/ntu-agentic-access/)

#### JSON Schema (2)

The data models the API reads and writes.

- [DR-NTU (Data) Dataset Search Item](https://apis.io/schemas/ntu/ntu-dataset/)
- [DR-NTU (Digital Repository) Item](https://apis.io/schemas/ntu/ntu-item/)

#### JSON Structure (2)

Data models expressed in JSON Structure.

- [Ntu Dataset Structure](https://apis.io/json-structure/ntu/ntu-dataset-structure/)
- [Ntu Item Structure](https://apis.io/json-structure/ntu/ntu-item-structure/)

#### JSON-LD (1)

Linked-data contexts for the provider's vocabulary.

- [Ntu Context](https://apis.io/jsonld/ntu/ntu-context/)

#### Vocabulary (1)

The provider's domain terms, defined.

- [NTU Repository & Research Data Vocabulary](https://apis.io/vocabularies/ntu/ntu-vocabulary/)

#### Examples (2)

Example requests and responses.

- [Ntu Discover Example](https://apis.io/examples/ntu/ntu-discover-example/)
- [Ntu Search Example](https://apis.io/examples/ntu/ntu-search-example/)

#### Collections (2)

Postman and Open Collection request collections.

- [DR-NTU (Data) Dataverse Discover Info API](https://apis.io/collections/ntu/open-ntu-info-api/)
- [DR-NTU (Data) Dataverse Discover Search API](https://apis.io/collections/ntu/open-ntu-search-api/)

#### Governance rules (2)

Spectral rulesets for the provider's contracts.

- [Nanyang Technological University — jsonschema rules](https://apis.io/rules/ntu/ntu-jsonschema-spectral-rules/)
- [Nanyang Technological University API Rules](https://apis.io/rules/ntu/ntu-rules/)

#### Security (2)

Authentication, trust centre, and vulnerability disclosure.

- [Ntu Authentication](https://apis.io/security/ntu/ntu-authentication/)
- [Ntu Domain Security](https://apis.io/security/ntu/ntu-domain-security/)

#### OAuth scopes (1)

The permissions the API asks for.

- [Ntu Scopes](https://apis.io/scopes/ntu/ntu-scopes/)

#### Plans and pricing (1)

Published plans, tiers and prices.

- [Ntu Plans Pricing](https://apis.io/plans/ntu/ntu-plans-pricing/)

#### Rate limits (1)

Published request limits.

- [Ntu Rate Limits](https://apis.io/rate-limits/ntu/ntu-rate-limits/)

#### FinOps (1)

What the API costs to run, by operation.

- [Ntu Finops](https://apis.io/finops/ntu/ntu-finops/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://www.ntu.edu.sg/)
- [Documentation](https://libguides.ntu.edu.sg/drntudataguidespolicies/APITermsOfUse)
- [Support](https://www.ntu.edu.sg/life-at-ntu/internet-account-and-policy/contact-service-desk)
- [Blog](https://www.ntu.edu.sg/admissions/graduate/coursework/articles)
- [Terms of service](https://www.ntu.edu.sg/legal/terms-of-use)
- [Privacy policy](https://www.ntu.edu.sg/legal/privacy-statement)
- [GitHub](https://github.com/NTUsg)

## API Evangelist rating

**Kin Score 32.6** — thin · rubric 0.24.0 · scored 2026-10-17

| Facet | Score |
|---|---|
| Discoverability | 71.4 |
| Contract quality | 52.7 |
| Contract governance | 9.8 |
| Operational transparency | 7.9 |
| Developer ergonomics | 16.7 |
| Access clarity | 26.3 |

**Agent readiness 20.7** — agent-aware

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | yes |
| Agentic Access | derived (partial credit) |
| Reversibility Documented | na |
| MCP Server | — |
| Auth Clarity | — |
| Idempotency | na |
| Error Semantics | — |
| OpenAPI Examples | partial |
| Rate Limit Signal | derived (partial credit) |
| Event Surface Described | — |
| Agent Skills | — |
| Well Known Catalog | — |
| Consent Identity | — |
| Agent Card | — |
| Dry Run Mode | na |
| Delegated Identity | — |
| Protected Resource Metadata | — |
| Dynamic Client Registration | — |
| Agentic Commerce | — |

**Regulatory alignment 28.4** — Education & Research

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/ntu/](https://apis.io/providers/ntu/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for Nanyang Technological University: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/ntu/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
