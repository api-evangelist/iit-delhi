# Indian Institute of Technology Delhi (iit-delhi)

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
