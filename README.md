# Kestrel Perch — Moderate

**Balanced.** A core of index funds and blue-chips, a small gold-and-silver hedge, a quarter in cash reserve. The default tier for long-term holders.

## Target allocation

| Asset | Target |
|---|---|
| SPY — S&P 500 ETF | 25 % |
| QQQ — Nasdaq-100 ETF | 15 % |
| AAPL — Apple | 10 % |
| MSFT — Microsoft | 10 % |
| BRK.B — Berkshire | 10 % |
| Gold & silver sleeve | 5 % |
| SGOV — 0–3 mo Treasuries | 25 % |

Invested 75 % · Cash & Treasuries 25 %.

## How it is run

Every Kestrel portfolio is held in a VANE vault the owner alone can open and is kept on target by the same agentic engine: live two-source marks, a published drift band, and a full re-true-up whenever the market pushes the mix out of band — sells before buys, every leg an atomic on-chain swap with a slippage floor the program enforces. Nothing is calendar-based and nothing is discretionary.

The complete methodology — band mathematics and parameters, cooldown, trade construction, screening thresholds and substitution rules — is maintained in a private repository (`KestrelInvest/kestrel-strategy`).

See it live: https://kestrelinvest.xyz/portfolios.html · Custody: `KestrelInvest/vane`

---
*Not investment advice. Kestrel is in development; nothing here is live for public deposits. Portfolio definitions are versioned; a change is a new version that a vault adopts only when its owner signs.*
