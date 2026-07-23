# Atlantic Union Bank (atlantic-union-bank)

Atlantic Union Bank is a Virginia state-chartered commercial bank with roots going back to 1902, and the principal banking subsidiary of Atlantic Union Bankshares Corporation (NYSE: AUB), a Richmond, Virginia bank holding company. It is the largest regional bank headquartered in Virginia, with roughly $37 billion in assets and a branch network across Virginia, Maryland, and North Carolina, offering consumer and business checking, savings, lending, mortgages, credit cards, and wealth management.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/atlantic-union-bank/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/atlantic-union-bank/refs/heads/main/apis.yml)

## Open-Finance & API Posture

The United States has no single mandated open-banking contract; open finance here is voluntary and fragmented. Consistent with most US regional banks, Atlantic Union Bank publishes **no first-party public developer portal and no documented public API**:

- Conventional developer/API hosts (`developer.`, `developers.`, `api.atlanticunionbank.com`) do not resolve, and the public site returns 404 for `/developers` and `/api`.
- No downloadable OpenAPI/Swagger, SDKs, or sandbox are published.
- Consumer-permissioned account and transaction data appears reachable only **indirectly through third-party aggregators** — Plaid, Finicity (by Mastercard), MX, and Teller — as listed in external aggregator coverage directories, not via a first-party bank API.
- No direct FDX-conformant data-access endpoint, Akoya Data Access Network participation, or published CFPB Section 1033 posture was found on the bank's own properties.

This is an honest identity-only, aggregator-only record. See [`review.yml`](review.yml) for the full reviewer finding and probe log.

## Tags

- Financial Services
- Banking
- United States
- Regional Bank
- Virginia
- Open Finance
- Data Aggregation

## Timestamps

- **Created:** 2026-07-23
- **Modified:** 2026-07-23

## APIs

None. Atlantic Union Bank exposes no documented first-party public API. Data access is aggregator-mediated only.

## Common Properties

- [Website](https://www.atlanticunionbank.com/)
- [Investor Relations](https://investors.atlanticunionbank.com/)
- [LinkedIn](https://www.linkedin.com/company/atlantic-union-bank)
- [Privacy Policy](https://www.atlanticunionbank.com/about/helpful-links/privacy)
- [Terms of Service](https://www.atlanticunionbank.com/about/helpful-links/terms-of-use)
- [Security](https://www.atlanticunionbank.com/about/helpful-links/security-fraud-center)
- [Support](https://www.atlanticunionbank.com/about/contact-us)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
