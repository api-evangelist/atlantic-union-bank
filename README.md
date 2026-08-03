# Atlantic Union Bank (atlantic-union-bank)

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
