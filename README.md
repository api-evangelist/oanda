# OANDA

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
> **Not from the company, and here with a question?** You are welcome here — we would rather be the
> front line and point you the right way than have a good report go nowhere. What this repository
> can answer is narrow, though, so it is worth knowing who you are actually looking for:
>
> - **A question about how the API works, an account, billing, or a bug in the service** — that is
>   the company's own support, not us. We profile this API; we do not operate it and cannot see
>   your account.
> - **A bug in an open-source project we only catalog** — file it on that project's own repository.
>   This has happened with a real and correct bug report that reached us instead of the people who
>   could fix it, which helped nobody.
> - **Anything about this listing itself** — the description, the tags, the rating, a missing or
>   wrong artifact — is ours. Open an issue here.
> - **Not sure, or something general about API Evangelist or APIs.io** — open an issue on the
>   [APIs.io Inbox](https://github.com/api-search/inbox) and we will route it.
>
> **This repository contains no software, and we will never ask you to download anything.** There is
> no build, release, installer, or binary here — only text and machine-readable API descriptions, so
> there is nothing here that can be "corrupt" or need "repairing". Any issue, comment, or email
> claiming otherwise and offering a download link is not from us and is hostile. Do not follow the
> link; it is a lure. Report it to GitHub and, if you like, tell us at
> [info@apievangelist.com](mailto:info@apievangelist.com) so we can take it down.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

OANDA is a forex and CFD trading broker offering REST APIs for live and practice trading. The v20 REST API provides access to real-time forex rates, order management, trade lifecycle, position tracking, and historical OHLC candle data dating back to 2005. A separate Exchange Rates Data API delivers institutional-grade FX rates across 200+ currencies for data services use cases.

**Areas:** Foreign Exchange · FX Trading · CFD Trading · Financial Services · Trading APIs

## OANDA on APIs.io

Everything profiled for OANDA is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/oanda/](https://apis.io/providers/oanda/)** — or go straight to one of the APIs or properties below.

### APIs (10)

- [OANDA Account API](https://apis.io/apis/oanda/oanda-account-api/) — Manage and retrieve OANDA trading account details, summaries, tradeable instruments, and configuration settings. Supports polling for account state changes…
- [OANDA Order API](https://apis.io/apis/oanda/oanda-order-api/) — Create, list, modify, and cancel orders in an OANDA trading account. Supports market, limit, stop, take profit, stop loss, and trailing stop order types…
- [OANDA Trade API](https://apis.io/apis/oanda/oanda-trade-api/) — List, retrieve, partially or fully close open trades, and manage dependent orders (take profit, stop loss, trailing stop loss) for trades in an OANDA account.
- [OANDA Position API](https://apis.io/apis/oanda/oanda-position-api/) — List all positions (historical and open) and close out open positions for a specific instrument in an OANDA trading account.
- [OANDA Transaction API](https://apis.io/apis/oanda/oanda-transaction-api/) — Access full transaction history for an OANDA trading account with time-based and ID-range queries. Includes a streaming endpoint for real-time transaction…
- [OANDA Exchange Rates API](https://apis.io/apis/oanda/oanda-exchange-rates-api/) — Institutional-grade foreign exchange data service covering 200+ currencies and 38,000+ currency pairs. Provides daily average rates, period averages, ECB…
- [OANDA Accounts API](https://apis.io/apis/oanda/oanda-accounts-api/) — The Accounts API from OANDA — 29 operation(s) for accounts.
- [OANDA Instruments API](https://apis.io/apis/oanda/oanda-instruments-api/) — The Instruments API from OANDA — 5 operation(s) for instruments.
- [OANDA Pricing API](https://apis.io/apis/oanda/oanda-pricing-api/) — Retrieve real-time bid/ask pricing, stream live price updates at up to 4 per second, and access historical OHLC candlestick data for any tradeable…
- [OANDA Users API](https://apis.io/apis/oanda/oanda-users-api/) — The Users API from OANDA — 2 operation(s) for users.

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### Agentic access (1)

Which operations an agent can call, which act, and which need a human in the loop.

- [Oanda Agentic Access](https://apis.io/agentic-access/oanda/oanda-agentic-access/)

#### JSON Schema (156)

The data models the API reads and writes.

- [AcceptDatetimeFormat](https://apis.io/schemas/oanda/AcceptDatetimeFormat/)
- [Account](https://apis.io/schemas/oanda/Account/)
- [AccountChanges](https://apis.io/schemas/oanda/AccountChanges/)
- [AccountChangesState](https://apis.io/schemas/oanda/AccountChangesState/)
- [AccountFinancingMode](https://apis.io/schemas/oanda/AccountFinancingMode/)
- [AccountID](https://apis.io/schemas/oanda/AccountID/)
- [AccountProperties](https://apis.io/schemas/oanda/AccountProperties/)
- [AccountSummary](https://apis.io/schemas/oanda/AccountSummary/)
- [AccountUnits](https://apis.io/schemas/oanda/AccountUnits/)
- [CalculatedAccountState](https://apis.io/schemas/oanda/CalculatedAccountState/)
- [CalculatedPositionState](https://apis.io/schemas/oanda/CalculatedPositionState/)
- [CalculatedTradeState](https://apis.io/schemas/oanda/CalculatedTradeState/)
- [CancellableOrderType](https://apis.io/schemas/oanda/CancellableOrderType/)
- [Candlestick](https://apis.io/schemas/oanda/Candlestick/)
- [CandlestickData](https://apis.io/schemas/oanda/CandlestickData/)
- [CandlestickGranularity](https://apis.io/schemas/oanda/CandlestickGranularity/)
- [ClientComment](https://apis.io/schemas/oanda/ClientComment/)
- [ClientConfigureRejectTransaction](https://apis.io/schemas/oanda/ClientConfigureRejectTransaction/)
- [ClientConfigureTransaction](https://apis.io/schemas/oanda/ClientConfigureTransaction/)
- [ClientExtensions](https://apis.io/schemas/oanda/ClientExtensions/)
- [ClientID](https://apis.io/schemas/oanda/ClientID/)
- [ClientPrice](https://apis.io/schemas/oanda/ClientPrice/)
- [ClientRequestID](https://apis.io/schemas/oanda/ClientRequestID/)
- [ClientTag](https://apis.io/schemas/oanda/ClientTag/)
- [CloseTransaction](https://apis.io/schemas/oanda/CloseTransaction/)
- …and 131 more published on APIs.io

#### JSON-LD (1)

Linked-data contexts for the provider's vocabulary.

- [Oanda Context](https://apis.io/jsonld/oanda/oanda/)

#### Examples (39)

Example requests and responses.

- [Cancelorder](https://apis.io/examples/oanda/cancelOrder/)
- [Closeposition](https://apis.io/examples/oanda/closePosition/)
- [Closetrade](https://apis.io/examples/oanda/closeTrade/)
- [Configureaccount](https://apis.io/examples/oanda/configureAccount/)
- [Createorder](https://apis.io/examples/oanda/createOrder/)
- [Getaccount](https://apis.io/examples/oanda/getAccount/)
- [Getaccountchanges](https://apis.io/examples/oanda/getAccountChanges/)
- [Getaccountinstruments](https://apis.io/examples/oanda/getAccountInstruments/)
- [Getaccountsummary](https://apis.io/examples/oanda/getAccountSummary/)
- [Getbaseprices](https://apis.io/examples/oanda/getBasePrices/)
- [Getexternaluserinfo](https://apis.io/examples/oanda/getExternalUserInfo/)
- [Getinstrumentcandles](https://apis.io/examples/oanda/getInstrumentCandles/)
- [Getinstrumentprice](https://apis.io/examples/oanda/getInstrumentPrice/)
- [Getinstrumentpricerange](https://apis.io/examples/oanda/getInstrumentPriceRange/)
- [Getorder](https://apis.io/examples/oanda/getOrder/)
- [Getposition](https://apis.io/examples/oanda/getPosition/)
- [Getpricerange](https://apis.io/examples/oanda/getPriceRange/)
- [Getprices](https://apis.io/examples/oanda/getPrices/)
- [Gettrade](https://apis.io/examples/oanda/getTrade/)
- [Gettransaction](https://apis.io/examples/oanda/getTransaction/)
- [Gettransactionrange](https://apis.io/examples/oanda/getTransactionRange/)
- [Gettransactionssinceid](https://apis.io/examples/oanda/getTransactionsSinceId/)
- [Getuserinfo](https://apis.io/examples/oanda/getUserInfo/)
- [Get_Instruments_{Instrument}_Orderbook](https://apis.io/examples/oanda/get_instruments_{instrument}_orderBook/)
- [Get_Instruments_{Instrument}_Positionbook](https://apis.io/examples/oanda/get_instruments_{instrument}_positionBook/)
- …and 14 more published on APIs.io

#### Collections (4)

Postman and Open Collection request collections.

- [OANDA v20 REST Accounts API](https://apis.io/collections/oanda/open-oanda-accounts-api/)
- [OANDA v20 REST Accounts Instruments API](https://apis.io/collections/oanda/open-oanda-instruments-api/)
- [OANDA v20 REST Accounts Pricing API](https://apis.io/collections/oanda/open-oanda-pricing-api/)
- [OANDA v20 REST Accounts Users API](https://apis.io/collections/oanda/open-oanda-users-api/)

#### Governance rules (1)

Spectral rulesets for the provider's contracts.

- [OANDA — jsonschema rules](https://apis.io/rules/oanda/oanda-jsonschema-spectral-rules/)

#### Security (1)

Authentication, trust centre, and vulnerability disclosure.

- [Oanda Domain Security](https://apis.io/security/oanda/oanda-domain-security/)

#### Plans and pricing (1)

Published plans, tiers and prices.

- [Oanda Plans Pricing](https://apis.io/plans/oanda/oanda-plans-pricing/)

#### Rate limits (1)

Published request limits.

- [Oanda Rate Limits](https://apis.io/rate-limits/oanda/oanda-rate-limits/)

#### FinOps (1)

What the API costs to run, by operation.

- [Oanda Finops](https://apis.io/finops/oanda/oanda-finops/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://www.oanda.com/)
- [Documentation](https://developer.oanda.com/rest-live-v20/introduction/)
- [Getting started](https://developer.oanda.com/rest-live-v20/introduction/)
- [API reference](https://developer.oanda.com/rest-live-v20/account-ep/)
- [Pricing](https://www.oanda.com/foreign-exchange-data-services/en/exchange-rates-api/api-plans/)
- [GitHub](https://github.com/oanda)

## API Evangelist rating

**Kin Score 36.6** — thin · rubric 0.24.0 · scored 2026-10-17

| Facet | Score |
|---|---|
| Discoverability | 53.6 |
| Contract quality | 50.7 |
| Contract governance | 9.8 |
| Operational transparency | 13.2 |
| Developer ergonomics | 50.0 |
| Access clarity | 31.6 |

**Agent readiness 20.9** — agent-aware

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | yes |
| Agentic Access | derived (partial credit) |
| Reversibility Documented | documented (partial credit) |
| MCP Server | — |
| Auth Clarity | bearer (partial credit) |
| Idempotency | — |
| Error Semantics | — |
| OpenAPI Examples | documented (partial credit) |
| Rate Limit Signal | derived (partial credit) |
| Event Surface Described | — |
| Agent Skills | — |
| Well Known Catalog | — |
| Consent Identity | — |
| Agent Card | — |
| Dry Run Mode | — |
| Delegated Identity | — |
| Protected Resource Metadata | — |
| Dynamic Client Registration | — |
| Agentic Commerce | — |

**Regulatory alignment 21.3** — Securities & Market Data

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/oanda/](https://apis.io/providers/oanda/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for OANDA: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/oanda/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
