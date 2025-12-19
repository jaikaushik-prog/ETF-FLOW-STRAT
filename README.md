This script implements the "ETF Flow Pressure" alpha strategy.
- Logic: Identifies stocks facing mechanical selling pressure from ETF outflows.
- Signal: Bottom 10% of Flow Pressure (Pressure < 0).
- Execution: Buy at Close (or Next Open), Hold 20 Days.
- Risk Control: Volatility Targeting (15% Annualized).
- Universe: NIFTY 50 Constituents.
- Benchmark: NIFTY 50 Buy & Hold.
