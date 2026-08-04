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
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

Nanyang Technological University (NTU Singapore) is a public research university in Singapore, ranked #15 in the QS World University Rankings 2025. This repository catalogs NTU's public, machine-readable developer/API footprint as an [APIs.json](http://apisjson.org/) profile. NTU's confirmed public APIs are concentrated in its library and research infrastructure: DR-NTU (Data), a Dataverse research data repository, and DR-NTU (Digital Repository of NTU), a DSpace 7 institutional repository with REST and OAI-PMH access.

- APIs.json: https://raw.githubusercontent.com/api-evangelist/ntu/refs/heads/main/apis.yml
- Run it with Naftiko: https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=ntu-api-evangelist&utm_content=repo

## Type

- **Type:** Index
- **Position:** Consumer
- **Access:** 3rd-Party

## Tags

Education, Higher Education, University, Singapore, Research Data, Open Data, Repository, Library

## APIs

- **DR-NTU (Data) Dataverse API** — Dataverse 6.1 HTTP API for searching and downloading NTU's open research datasets.
  - Docs: https://libguides.ntu.edu.sg/drntudataguidespolicies/APITermsOfUse
  - Dataverse API guide: https://guides.dataverse.org/en/latest/api/
  - Base URL: `https://researchdata.ntu.edu.sg/api`
- **DR-NTU (Digital Repository) DSpace REST API** — DSpace 7.6.3 / DSpace-CRIS HAL REST API for the institutional repository.
  - Docs: https://dr.ntu.edu.sg/home
  - DSpace REST docs: https://wiki.lyrasis.org/display/DSDOC7x/REST+API
  - Base URL: `https://dr.ntu.edu.sg/server/api`
- **DR-NTU (Digital Repository) OAI-PMH** — OAI-PMH 2.0 metadata harvesting endpoint for the institutional repository.
  - Docs: https://dr.ntu.edu.sg/home
  - Base URL: `https://dr.ntu.edu.sg/oai/request`

## Plans, Rate Limits, and FinOps

- Plans / Pricing: [plans/ntu-plans-pricing.yml](plans/ntu-plans-pricing.yml)
- Rate Limits: [rate-limits/ntu-rate-limits.yml](rate-limits/ntu-rate-limits.yml)
- FinOps: [finops/ntu-finops.yml](finops/ntu-finops.yml)

## Timestamps

- **Created:** 2026-06-03
- **Modified:** 2026-06-03

## Common Properties

- Website: https://www.ntu.edu.sg/
- GitHub: https://github.com/NTUsg
- LinkedIn: https://www.linkedin.com/school/nanyang-technological-university/
- Review: [review.yml](review.yml)

## Notes

All endpoints in this profile were probed live on 2026-06-03. The Dataverse API (`/api/info/version`, `/api/search`), the DSpace REST API (`/server/api`, reporting DSpace 7.6.3 with DSpace-CRIS), and the OAI-PMH `Identify` verb all returned HTTP 200. The official NTUsg GitHub organization exists but had no public repositories at review time. No publicly documented course/timetable/student-information or mobile-app backend APIs were found; such systems exist but are not exposed as open, documented APIs. Nothing in this catalog was fabricated.

## Maintainers

- Kin Lane — kin@apievangelist.com
