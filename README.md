# Mountain America Credit Union (mountain-america)

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

Mountain America Credit Union (MACU) is a federally chartered, member-owned not-for-profit financial cooperative headquartered in Sandy, Utah, founded in 1936 and regulated and insured by the National Credit Union Administration (NCUA). It is one of the largest credit unions in the United States, with roughly $21.9 billion in assets, more than 1.4 million members, and over 100 branches serving Utah, Idaho, Montana, Nevada, and Arizona.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/mountain-america/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/mountain-america/refs/heads/main/apis.yml)

## Open Finance / API Posture

Mountain America exposes **no public first-party developer API and no developer portal**. Probing found no `developer.macu.com` (NXDOMAIN) and no reachable `api.macu.com`, and every path under `macu.com` (including `/developers`, `/api`, `/open-banking`) returns the same ~1.1 KB client-rendered application shell — a soft-404 rather than a documented API surface.

This is the honest and typical reality for a US credit union. US open finance is voluntary and fragmented (unlike the mandated UK/AU regimes). Consumer-permissioned data access for MACU is intermediated through its core banking provider and data aggregators (Plaid, MX, Finicity, Akoya) rather than a directly published API. No public Financial Data Exchange (FDX) participation and no stated CFPB Section 1033 (Personal Financial Data Rights) data-access posture were found for this institution at the time of review.

No OpenAPI/Swagger specifications were harvested because none are publicly published.

## Tags

- Financial Services
- Banking
- United States
- Credit Union
- Consumer Banking
- Open Finance
- Data Aggregation

## Timestamps

- **Created:** 2026-07-23
- **Modified:** 2026-07-23

## APIs

No public APIs are documented for this institution.

## Common Properties

- [Website](https://www.macu.com/)
- [LinkedIn](https://www.linkedin.com/company/mountain-america-credit-union)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
