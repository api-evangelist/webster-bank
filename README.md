# Webster Bank (webster-bank)

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

Webster Bank, N.A. is a nationally chartered commercial bank (National Association) and the principal banking subsidiary of Webster Financial Corporation (NYSE: WBS), a Delaware-incorporated bank and financial holding company headquartered in Stamford, Connecticut. A values-based super-regional institution with roughly $84 billion in assets, Webster serves businesses, individuals, and families across the Northeast and operates the HSA Bank division, a leading national provider of health savings accounts and consumer-directed benefit administration.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/webster-bank/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/webster-bank/refs/heads/main/apis.yml)

## Tags

- Financial Services
- Banking
- United States
- Commercial Banking
- Super-Regional Bank
- Open Finance
- FDX
- Data Aggregation
- Health Savings Accounts

## Timestamps

- **Created:** 2026-07-23
- **Modified:** 2026-07-23

## APIs

Webster Bank publishes **no first-party public developer API**. There is no `developer.websterbank.com` portal (the host does not resolve), `websterbank.com/developers` returns HTTP 404, and `api.websterbank.com` returns HTTP 403 with no public documentation. No downloadable OpenAPI or Swagger definition is published.

Webster's open-finance posture is **consumer- and commercial-permissioned data sharing through aggregators**, not a direct first-party API:

- **FDX-aligned data access via Plaid Core Exchange.** In June 2026 Webster Bank went live on [Prolific Banking's FI-Streams Connector](https://www.businesswire.com/news/home/20260611592775/en/Webster-Bank-Implements-Prolific-Bankings-FI-Streams-Connector-to-Enable-Commercial-Client-Financial-Data-Connectivity), leveraging Plaid's FDX-aligned Core Exchange specification to give commercial clients secure, tokenized connectivity to the Plaid network of 7,000+ apps and services, synchronized with the bank's digital banking entitlements and user authorization.
- **Aggregator access.** Consumer account data (balances, transactions, account holder info, authentication) is reachable through Plaid and Finicity rather than a Webster-hosted API.

This is the honest, non-fabricated reality for most US super-regional banks: open finance is delivered via the aggregator layer and an FDX-aligned data-access standard, not a self-serve developer program.

## Common Properties

- [Website](https://www.websterbank.com/)
- [LinkedIn](https://www.linkedin.com/company/webster-bank)
- [Documentation](https://www.websterbank.com/commercial-banking/online-access/)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
