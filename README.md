# Mountain America Credit Union (mountain-america)

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
