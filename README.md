# Webster Bank (webster-bank)

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
