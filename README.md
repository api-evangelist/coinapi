# CoinAPI (coinapi)

CoinAPI is a financial data and execution platform delivering normalized real-time and historical cryptocurrency market data and trade execution across more than 350 exchanges. Its product family covers a Market Data API (REST, WebSocket, FIX, and flat-file S3 delivery) for trades, quotes, order books, OHLCV, exchange rates, and derivatives metrics; an EMS Trading API (Execution Management System) that lets users place, manage, and route orders across multiple venues through one normalized REST/WebSocket/FIX interface; and Index and Metrics APIs that aggregate cross-exchange data into reference indexes and risk metrics. FIX endpoints (fix.coinapi.io) use GeoDNS to route to the nearest datacenter for low-latency connectivity.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/coinapi/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Consuming
- **Access:** 3rd-Party

## Tags

- Blockchain
- Crypto Indexes
- Crypto Metrics
- Cryptocurrency
- EMS
- Execution Management
- FIX
- Market Data
- Order Books
- REST
- WebSocket

## Timestamps

- **Created:** 2025-03-01
- **Modified:** 2026-04-28

## APIs

### CoinAPI Market Data API
Normalized cryptocurrency market data covering more than 350 exchanges and 28,000+ assets. Provides trades, quotes, order books, OHLCV time series, exchange rates, and derivatives metrics (funding rates, mark prices, liquidations, open interest, volumes). Delivered through REST for historical snapshots and lookups, WebSocket and FIX for real-time streaming, and S3 flat files for bulk historical analysis.

**Human URL:** [https://www.coinapi.io/products/market-data-api](https://www.coinapi.io/products/market-data-api)

**Base URL:** `https://rest.coinapi.io`

#### Tags

- Crypto Metrics, Cryptocurrency, Exchange Rates, FIX, Market Data, OHLCV, Order Books, REST, WebSocket

#### Properties

- [Documentation](https://docs.coinapi.io/market-data/)
- [Landing Page](https://www.coinapi.io/products/market-data-api)
- [FAQ](https://www.coinapi.io/products/market-data-api/faq)
- [FIX Documentation](https://www.coinapi.io/products/market-data-api/docs/fix)

### CoinAPI EMS Trading API
CoinAPI's Execution Management System (EMS) is a unified, multi-exchange crypto trading API that lets institutional traders, market makers, and builders place, modify, and cancel orders across many connected venues from a single normalized interface. Available over REST, WebSocket, and FIX, the EMS handles credential vaulting, order routing, position and balance retrieval, and execution reporting.

**Human URL:** [https://www.coinapi.io/products/ems-api](https://www.coinapi.io/products/ems-api)

#### Tags

- Cryptocurrency, EMS, Execution Management, FIX, Order Management, REST, Trading, WebSocket

#### Properties

- [Landing Page](https://www.coinapi.io/products/ems-api)
- [FAQ](https://www.coinapi.io/products/ems-api/faq)
- [Guide](https://www.coinapi.io/blog/maximize-trading-potential-ems-trading-api-guide)

### CoinAPI Indexes API
The Indexes API aggregates data from many exchanges to compute reference rates and benchmark indexes that summarize broad market conditions for a given asset. Useful for derivatives settlement, NAV computation, and research where a single, defensible price point is required across a fragmented market.

**Human URL:** [https://www.coinapi.io/products/indexes-api](https://www.coinapi.io/products/indexes-api)

#### Tags

- Aggregation, Benchmark, Cryptocurrency, Indexes, Reference Rates

#### Properties

- [Landing Page](https://www.coinapi.io/products/indexes-api)
- [Documentation](https://docs.coinapi.io/)

## Common Properties

- [Website](https://www.coinapi.io/)
- [Documentation](https://docs.coinapi.io/)
- [Pricing](https://www.coinapi.io/pricing)
- [Changelog](https://docs.coinapi.io/general/changelog/)
- [Status](https://status.coinapi.io/)
- [GitHub](https://github.com/coinapi)
- [Blog](https://www.coinapi.io/blog)
- [Privacy Policy](https://www.coinapi.io/privacy-policy)
- [Terms of Service](https://www.coinapi.io/terms-of-service)

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
