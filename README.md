# Indian Institute of Technology Delhi (iit-delhi)

Indian Institute of Technology Delhi (IIT Delhi) is a public technical and research university in Hauz Khas, New Delhi, an Institute of National Importance and Institution of Eminence ranked #118 in the QS World University Rankings 2025. This repository catalogs IIT Delhi's public developer/API footprint as an [APIs.json](https://apisjson.org) profile.

- APIs.json: https://raw.githubusercontent.com/api-evangelist/iit-delhi/refs/heads/main/apis.yml
- Run it with Naftiko: https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=iit-delhi-api-evangelist&utm_content=repo

## Type

- Index
- Consumer
- 3rd-Party

## Tags

Education, Higher Education, University, Research, India, Open Access, Library

## APIs

- **IIT Delhi Institutional Repository DSpace REST API** — DSpace 8.0 REST/HAL API for the Central Library institutional repository. [Docs](https://ir.iitd.ac.in/server/api)
- **IIT Delhi Institutional Repository OAI-PMH** — OAI-PMH 2.0 metadata-harvesting interface for theses, dissertations, and scholarly output. [Docs](https://ir.iitd.ac.in/server/oai/request?verb=Identify)
- **IIT Delhi OAuth 2 Authentication Server** — OAuth 2 authorization server for campus apps; login/CAPTCHA gated. [Docs](https://oauth.iitd.ac.in/)
- **IITD Connect API (DevClub)** — Student-built campus/mobile app backend with Postman docs and Bearer-token auth. [Docs](https://documenter.getpostman.com/view/11367216/SzmmUEKQ)

## Plans, Rate Limits & FinOps

- [Plans / Pricing](plans/iit-delhi-plans-pricing.yml)
- [Rate Limits](rate-limits/iit-delhi-rate-limits.yml)
- [FinOps](finops/iit-delhi-finops.yml)

## Timestamps

- Created: 2026-06-03
- Modified: 2026-06-03

## Common Properties

- Website: https://home.iitd.ac.in/
- GitHub (official org): https://github.com/iit-delhi
- Source Code (DevClub): https://github.com/devclub-iitd
- LinkedIn: https://www.linkedin.com/school/iitdelhi/
- Authentication: https://oauth.iitd.ac.in/

## Notes

IIT Delhi has no centralized, productized public API portal. All entries reflect only surfaces verified live during cataloging (2026-06-03): the DSpace REST root and OAI-PMH Identify endpoint both returned HTTP 200, the DSpace items endpoint returned 401 (auth required), and the OAuth 2 server is live but gated. The IITD Connect API is a student DevClub project requiring a Bearer token. The legacy `eprint.iitd.ac.in` EPrints/OAI host did not resolve during probing. No endpoints were fabricated.

## Maintainers

- Kin Lane — kin@apievangelist.com
