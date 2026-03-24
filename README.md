# Awesome Wealth

A curated list of awesome Model Context Protocol (MCP) servers, APIs, and tools for finance, wealth management, and market data.

*Maintained by [ByteCEO](https://www.linkedin.com/company/byteceo) as we map the landscape for AI-native wealth and compliance infrastructure.*

---

## 📂 The Directory

### 📈 Market Data & TradFi

*Tools for pulling stock prices, historical data, and macroeconomic indicators.*

* [Financial Datasets MCP](https://github.com/financial-datasets/mcp-server) - Pulls income statements, balance sheets, cash flows, and real-time stock prices.
* [OpenMarkets (Yahoo Finance)](https://github.com/danchev/openmarkets) - Agentic retrieval of financial market data, historical stock prices, and dividend history via YFinance.
* [Finance MCP (FMP Data)](https://github.com/16Coffee/finance-mcp) - Retrieves options data, analyst grades, and detailed financial statements using Financial Modeling Prep.
* [Alpha Vantage MCP](https://github.com/alphavantage/alpha_vantage_mcp) - The official Alpha Vantage server. Real-time and historical stocks, ETFs, options, forex, crypto, fundamentals, and technical indicators. Uses Progressive Tool Discovery to minimize token costs.
* [EODHD MCP](https://github.com/Enlavan/EODHD_MCP_server) - Exposes EOD Historical Data APIs to any MCP-compatible client. Covers 75+ tools including daily OHLCV, intraday, tick data, fundamentals, news, sentiment, and options.

### ⛓️ On-Chain & Crypto

*Tools for tracking token prices, wallet balances, and blockchain state.*

* [CoinGecko Official MCP](https://docs.coingecko.com/docs/mcp-server) - The official server for tracking crypto prices and market data across 200+ blockchains directly from CoinGecko.
* [Crypto Price MCP](https://github.com/truss44/mcp-crypto-price) - Hooks into the CoinCap API for real-time crypto trends and historical data.
* [Bankless Onchain MCP](https://github.com/Bankless/onchain-mcp) - Official Bankless integration for querying on-chain data including ERC20 tokens, transaction history, and smart contract state via the Bankless API.
* [Etherscan MCP](https://github.com/crazyrabbitLTC/mcp-etherscan-server) - Provides Ethereum blockchain data tools including ETH balance checking, transaction history, ERC20 token transfers, contract ABIs, gas price monitoring, and ENS name resolution.
* [Solana Agent Kit MCP](https://github.com/sendaifun/solana-mcp) - AI-driven interactions with the Solana blockchain, enabling 40+ protocol actions including transactions, wallet management, and NFT minting.
* [Wallet Inspector MCP](https://github.com/kukapay/wallet-inspector-mcp) - Inspects wallet balances and on-chain activity across major EVM chains (Ethereum, Polygon, BSC, Base, Arbitrum) and Solana. Returns formatted balance tables and transaction histories.

### 🏠 Property & Real Estate

*Tools for property search, MLS data, valuations, mortgage calculations, and real estate CRM management.*

* [Zillow MCP](https://github.com/sap156/zillow-mcp-server) - Real-time access to Zillow property data. Search listings by location and price range, retrieve property details, track market trends (median sale price, days on market), and calculate mortgage payments.
* [Repliers Real Estate API MCP](https://github.com/Repliers-io/mcp-server) - Accesses real-time MLS listings, property history, valuations, and advanced search filters. Supports natural language queries like "3-bed apartments in SF under $1M listed this week."
* [Real Estate Data Management MCP](https://github.com/agentic-ops/real-estate-mcp) - A comprehensive local data management tool with 30+ tools covering listings, agent operations, client management, market analysis, and area intelligence including nearby amenities and school data.
* [Follow Up Boss CRM MCP](https://github.com/benlaube/fub-mcp) - Connects AI agents to the Follow Up Boss real estate CRM. 34 tools for full CRUD on contacts, leads, deals, pipelines, tasks, and call logs — with duplicate detection and smart date filtering.
* [Australian Real Estate RAG MCP](https://github.com/danny-tdoan/realestate-rag-mcp) - Enables flexible, natural language property search and market analysis across Australian real estate listings using a vector database and RAG pipeline. Supports school-zone and suburb-boundary queries. *(Australia market)*

### 🛡️ KYC/KYB & Compliance

*Tools for identity verification, business onboarding, and AML checks.*

* [Open Legal Compliance MCP](https://github.com/TCoder920x/open-legal-compliance-mcp) - Enables AI assistants to search and analyze legal documents from multiple jurisdictions using open government APIs (US Code, CFR, CourtListener, SEC EDGAR, EU regulations, UK legislation).
* *(We are currently mapping the identity space. The official ByteCEO KYC/B MCP server will be listed here soon.)*

### 🧮 Calculators & Projections

*Native tools for compound interest, tax estimation, and portfolio forecasting.*

* [TypeScript Calculator MCP](https://github.com/mvavassori/calculator-mcp-server) - A comprehensive math server exposing functions for percentages, trigonometry, logarithms, and basic arithmetic.
* [Go Calculator Server](https://github.com/avisangle/calculator-server) - A high-precision, Go-based MCP server implementing 13+ advanced mathematical tools including NPV, IRR, loan comparison, and investment scenario modelling.

### 📰 News & Sentiment

*Scrapers and APIs for real-time financial news and market sentiment analysis.*

* [World News API MCP](https://github.com/ddsky/world-news-api-mcp) - Enables AI assistants to search for global news, extract article sentiment, filter by location, and analyze entities.
* [Realtime News MCP](https://github.com/devjiel/mcp-news-server) - A lightweight integration with NewsAPI to pull current top headlines and market news context.
* [CryptoPanic MCP](https://github.com/kukapay/cryptopanic-mcp-server) - Delivers the latest cryptocurrency news to AI agents, powered by CryptoPanic. Covers headlines, sentiment flags, and source metadata across coins.
* [Crypto Sentiment MCP](https://github.com/kukapay/crypto-sentiment-mcp) - Delivers real-time cryptocurrency sentiment analysis to AI agents using aggregated social media and news data via Santiment.
* [Crypto Fear & Greed MCP](https://github.com/kukapay/crypto-feargreed-mcp) - Provides real-time and historical Crypto Fear & Greed Index data. Lightweight signal server for market mood tracking.
* [Polymarket MCP](https://github.com/berlinbra/polymarket-mcp) - Access prediction market data via Polymarket — market prices, probabilities, resolution dates, and historical volume for event-driven sentiment signals.

---

## 🗺️ Roadmap

- [x] **Phase 1:** Aggregate the most useful wealth-related APIs and MCPs in one place.
- [ ] **Phase 2:** Launch the official ByteCEO Wealth MCP server for direct LLM integration into compliance and wealth workflows.

---

## 🤝 Contributing

Contributions are welcome! Please open a Pull Request to add new MCP servers or tools to the list.