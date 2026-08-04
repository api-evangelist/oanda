# OANDA (oanda)

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

OANDA is a forex and CFD trading broker offering REST APIs for live and practice trading. The v20 REST API provides access to real-time forex rates, order management, trade lifecycle, position tracking, and historical OHLC candle data dating back to 2005. A separate Exchange Rates Data API delivers institutional-grade FX rates across 200+ currencies for data services use cases.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/oanda/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/oanda/main/apis.yml)

## Scope

- **Position:** Consuming
- **Access:** 3rd-Party

## Tags

- Forex
- FX Trading
- CFD Trading
- Financial Services
- Trading APIs

## Timestamps

- **Created:** 2026-06-13
- **Modified:** 2026-06-13

## APIs

### OANDA Account API

Manage and retrieve OANDA trading account details, summaries, tradeable instruments, and configuration settings. Supports polling for account state changes since a specified transaction ID.

#### Tags

- Accounts
- Forex
- Trading

#### Properties

- [Documentation](https://developer.oanda.com/rest-live-v20/account-ep/)
- [API Reference](https://developer.oanda.com/rest-live-v20/account-ep/)

---

### OANDA Order API

Create, list, modify, and cancel orders in an OANDA trading account. Supports market, limit, stop, take profit, stop loss, and trailing stop order types with FOK, IOC, DAY, GTD, and GTC durations.

#### Tags

- Orders
- Forex
- Trading

#### Properties

- [Documentation](https://developer.oanda.com/rest-live-v20/order-ep/)
- [API Reference](https://developer.oanda.com/rest-live-v20/order-ep/)

---

### OANDA Trade API

List, retrieve, partially or fully close open trades, and manage dependent orders (take profit, stop loss, trailing stop loss) for trades in an OANDA account.

#### Tags

- Trades
- Forex
- Trading

#### Properties

- [Documentation](https://developer.oanda.com/rest-live-v20/trade-ep/)
- [API Reference](https://developer.oanda.com/rest-live-v20/trade-ep/)

---

### OANDA Position API

List all positions (historical and open) and close out open positions for a specific instrument in an OANDA trading account.

#### Tags

- Positions
- Forex
- Trading

#### Properties

- [Documentation](https://developer.oanda.com/rest-live-v20/position-ep/)
- [API Reference](https://developer.oanda.com/rest-live-v20/position-ep/)

---

### OANDA Transaction API

Access full transaction history for an OANDA trading account with time-based and ID-range queries. Includes a streaming endpoint for real-time transaction notifications from the moment the request is made.

#### Tags

- Transactions
- Forex
- Trading

#### Properties

- [Documentation](https://developer.oanda.com/rest-live-v20/transaction-ep/)
- [API Reference](https://developer.oanda.com/rest-live-v20/transaction-ep/)

---

### OANDA Pricing API

Retrieve real-time bid/ask pricing, stream live price updates at up to 4 per second, and access historical OHLC candlestick data for any tradeable instrument. Historical data is available from 2005 onward with up to 5,000 records per page.

#### Tags

- Pricing
- Forex
- Real-Time Rates
- Historical Data
- Candles

#### Properties

- [Documentation](https://developer.oanda.com/rest-live-v20/pricing-ep/)
- [API Reference](https://developer.oanda.com/rest-live-v20/pricing-ep/)

---

### OANDA Exchange Rates API

Institutional-grade foreign exchange data service covering 200+ currencies and 38,000+ currency pairs. Provides daily average rates, period averages, ECB and national bank rates, forward rates, streaming spot rates updated every five seconds, and cryptocurrency rates. Available via annual subscription plans starting at $4,850/year.

#### Tags

- Exchange Rates
- Forex
- FX Data
- Currencies

#### Properties

- [Documentation](https://www.oanda.com/foreign-exchange-data-services/en/exchange-rates-api/)
- [Pricing](https://www.oanda.com/foreign-exchange-data-services/en/exchange-rates-api/api-plans/)

---

## Common Resources

- [Developer Portal](https://developer.oanda.com/)
- [Documentation](https://developer.oanda.com/rest-live-v20/introduction/)
- [Authentication](https://developer.oanda.com/rest-live-v20/authentication/)
- [Best Practices](https://developer.oanda.com/rest-live-v20/best-practices/)
- [API Comparison](https://developer.oanda.com/rest-live-v20/api-comparison/)
- [OpenAPI Source](https://github.com/oanda/v20-openapi)
- [Python SDK](https://github.com/oanda/v20-python)
- [Python Samples](https://github.com/oanda/v20-python-samples)
- [JavaScript SDK](https://github.com/oanda/v20-javascript)
- [Java SDK](https://github.com/oanda/v20-java)
- [GitHub Organization](https://github.com/oanda)
- [Pricing](https://www.oanda.com/foreign-exchange-data-services/en/exchange-rates-api/api-plans/)
- [Website](https://www.oanda.com)
- [Sign Up / Demo Account](https://www.oanda.com/us-en/trading/demo-account/)
