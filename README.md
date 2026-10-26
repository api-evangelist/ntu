# Nanyang Technological University (ntu)

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

Nanyang Technological University (NTU Singapore) is an autonomous public research university in Singapore, ranked in the top 15 of the QS World University Rankings. This repository catalogs NTU's public, machine-readable footprint as an [APIs.json](http://apisjson.org/) profile, with **operator attribution on every surface**. A university is a federation of buyers, not a producer, and NTU is a clean example: of the four surfaces recorded here, exactly **one is NTU-operated** — DR-NTU (Data), a Dataverse 6.1 research data repository NTU self-hosts on its own network. The larger and better-known DR-NTU (Digital Repository), its OAI-PMH endpoint, and NTU's federated single sign-on are all **tenancies on vendor platforms**: NTU's data and NTU's branding, someone else's engineering. NTU operates no developer portal and publishes no API documentation of its own.

- APIs.json: https://raw.githubusercontent.com/api-evangelist/ntu/refs/heads/main/apis.yml
- Run it with Naftiko: https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=ntu-api-evangelist&utm_content=repo

## Type

- **Type:** Index
- **Position:** Consumer
- **Access:** 3rd-Party

## Tags

University, Higher Education, Education, Singapore, Public Research University, Research Data, Research Repository, Identity Federation, Open Access, Course Catalog, Library, OAI-PMH

## APIs

Every entry carries `x-operator` — who runs the thing the contract describes.

- **DR-NTU (Data) — Dataverse API** · `x-operator: institution`
  - The only API NTU actually operates. Dataverse 6.1, self-hosted: `researchdata.ntu.edu.sg` CNAMEs to
    `dataverse.ntu.edu.sg` → `155.69.19.238`, whois org-name *Nanyang Technological University* (NTUNET1, SG).
    Backed by NTU's own DataCite client `GDCC.NTU`, 3,625 DOIs under prefix `10.21979`.
  - Docs: https://libguides.ntu.edu.sg/drntudataguidespolicies/APITermsOfUse
  - Base URL: `https://researchdata.ntu.edu.sg/api`
- **DR-NTU (Digital Repository) — DSpace-CRIS REST API** · `x-operator: tenant`
  - 158,100 research profiles, records back to 2008 — but `dr.ntu.edu.sg` CNAMEs to
    `ntu-cris.4science.cloud`. DSpace 7.6.3 / cris-2023.02.07 on 4Science's platform. No OpenAPI is
    registered under NTU for this surface; the DSpace contract belongs to the platform.
  - Base URL: `https://dr.ntu.edu.sg/server/api`
- **DR-NTU (Digital Repository) — OAI-PMH** · `x-operator: tenant`
  - Fully conformant OAI-PMH 2.0, 11 metadata formats, OpenAIRE CERIF-CRIS 1.1 compatible.
    Administered by NTU Library (`library@ntu.edu.sg`), operated by the vendor platform.
  - Base URL: `https://dr.ntu.edu.sg/server/oai/request`
- **NTU Identity Provider — SGAF / eduGAIN** · `x-operator: tenant`
  - Live SAML 2.0 IdP metadata, eduGAIN entity 879352, registered by SingAREN under the Singapore
    Access Federation, asserting scope `ntu.edu.sg`. The surface class universities operate that almost
    never gets catalogued — recorded as tenant because the entityID sits on SingAREN's proxy.
  - Metadata: `https://ntu-entra.singaren.net.sg/simplesaml/saml2/idp/metadata.php`

Not credited: `api.ntu.edu.sg` is a live NTU-owned gateway that returns `{"statusCode":404,"message":"Resource
not found"}` on every path probed and documents no route. `ntumods.org` is a student "NTUMODS Dev Team"
project with no stated NTU affiliation and no public API.

## Plans, Rate Limits, and FinOps

- Plans / Pricing: [plans/ntu-plans-pricing.yml](plans/ntu-plans-pricing.yml)
- Rate Limits: [rate-limits/ntu-rate-limits.yml](rate-limits/ntu-rate-limits.yml)
- FinOps: [finops/ntu-finops.yml](finops/ntu-finops.yml)

## Timestamps

- **Created:** 2026-06-03
- **Modified:** 2026-08-19

## Common Properties

- Website: https://www.ntu.edu.sg/
- GitHub: https://github.com/NTUsg (zero public repositories)
- Terms of Service: https://www.ntu.edu.sg/legal/terms-of-use
- Privacy: https://www.ntu.edu.sg/legal/privacy-statement
- Course Catalog: https://wis.ntu.edu.sg/webexe/owa/aus_subj_cont.main
- Identity Federation: https://ntu-entra.singaren.net.sg/simplesaml/saml2/idp/metadata.php
- AI Policy: https://www.ntu.edu.sg/research/resources/use-of-gai-in-research
- LinkedIn: https://www.linkedin.com/school/nanyang-technological-university/
- Review: [review.yml](review.yml)

## Notes

Re-profiled 2026-08-19 under the API Evangelist university pipeline, which settles operator attribution before
saving any contract.

**What changed.** Four of six OpenAPIs were removed as host-collision fabrications. `refine-openapis` had merged
three source specs spanning *two different hosts* by tag and stamped every output with the first spec's
`servers[]`, so DSpace paths (`/`, `/core/items/{uuid}`, `/discover/search/objects`) and the OAI-PMH `/request`
path were all asserting `researchdata.ntu.edu.sg` as their host — a host that never served them. The two
genuinely-Dataverse specs were kept and their titles corrected. The archived tenant contracts under
`openapi/_original/` now carry `x-operator: tenant` so a future refine run cannot silently promote them.

**Coverage.** `researchdata.ntu.edu.sg` could not be re-probed: Citrix bot management returns HTTP 403 with a
`/trap.html` honeypot on *every* path, including the site root and `robots.txt`, and a browser User-Agent plus a
persisted cookie jar did not clear it. That is a block on us, not a dead service — NTU's DataCite client minted a
DOI on 2026-08-17, and re3data independently lists the REST, OAI-PMH and SWORD endpoints as current. Every other
surface was read live.

**Absences are findings.** No open data portal (`data.ntu.edu.sg` and `opendata.ntu.edu.sg` do not resolve). No
HPC or research-computing service catalog. No `llms.txt`, `security.txt` or sitemap on the main site. No status
page. No deprecation policy or changelog for any surface. The official `NTUsg` GitHub organization exists but
still has zero public repositories. Course and timetable information is published as HTML only, at
`wis.ntu.edu.sg`. Nothing in this catalog was fabricated, and nothing NTU does not operate is credited to it.

## Maintainers

- Kin Lane — kin@apievangelist.com
