# Quant Finance Lab

Focused studies from my MSc in Quantitative Finance (Honours, VU Amsterdam), reworked as standalone research pieces. Each maps to a stage of the systematic pipeline I'm [building end-to-end](../../systematic-trading-system).

| Study | Pipeline stage | One line |
|---|---|---|
| [`price-discovery-vecm/`](price-discovery-vecm) | Signals · microstructure | Which exchange leads price discovery for a cross-listed S&P 500 ETF? (VECM, FEVD: London leads, 65–76%) |
| [`equity-premium-forecasting/`](equity-premium-forecasting) | Signals · forecast combination | Welch-Goyal predictors out of sample: individual predictors are fragile, **combinations survive** (mean/median/DMSPE) |
| [`credit-risk-models/`](credit-risk-models) | Risk · credit | CDS curve stripping (simple vs exact iterative) + CreditMetrics transition-matrix portfolio credit risk |
| [`var-es-backtesting/`](var-es-backtesting) | Risk · market | 5 VaR/ES methods × 3 allocations, 2118-day rolling backtest, exact binomial coverage tests, √T-rule rejection |

Notebooks have outputs stripped for readability; each folder's README documents data sources (licensed data is never committed).
