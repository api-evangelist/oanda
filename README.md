# OANDA (oanda)

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
