# Bank OZK (bank-ozk)

Bank OZK is a regional bank headquartered in Little Rock, Arkansas, tracing its charter to 1903 and today operating roughly 265 offices across Arkansas, Georgia, Florida, North Carolina, Texas, and New York. It is a state-chartered commercial bank, the wholly owned subsidiary of Bank OZK holding company, publicly traded on the Nasdaq Global Select Market under the symbol OZK, with about $40.8 billion in total assets as of year-end 2025 and a national reputation in commercial real estate lending.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/bank-ozk/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/bank-ozk/refs/heads/main/apis.yml)

## Open Finance / API Posture

Bank OZK runs **no first-party public developer portal** and publishes **no downloadable OpenAPI/Swagger specifications**. Probes of `developer.ozk.com` do not resolve, and `api.ozk.com` returns HTTP 404. The bank is **not a documented FDX (Financial Data Exchange) participant** and has **not published a specific CFPB Section 1033 (Personal Financial Data Rights) posture**.

Consumer-permissioned account data is reached only indirectly through third-party open-finance aggregators. Per open-banking directories, **Plaid** is the documented aggregator supporting Bank OZK account connectivity. This is the honest reality for many US regional banks: open-finance access exists only via aggregators, not through a first-party API.

This repository is therefore an **identity-only** profile with no public API surface to catalog.

## Tags

- Financial Services
- Banking
- United States
- Regional Bank
- Commercial Real Estate Lending
- Open Finance
- Data Aggregation

## Timestamps

- **Created:** 2026-07-23
- **Modified:** 2026-07-23

## APIs

None. Bank OZK exposes no documented public API. Data access is available only through third-party aggregators (Plaid).

## Common Properties

- [Website](https://www.ozk.com/)
- [Support](https://www.ozk.com/contact-us/)
- [Privacy Policy](https://www.ozk.com/privacy/)
- [Terms of Service](https://www.ozk.com/privacy/)
- [Blog / Learning Center](https://www.ozk.com/learning-center/)
- [LinkedIn](https://www.linkedin.com/company/bank-ozk)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
