# Nanyang Technological University (ntu)

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
