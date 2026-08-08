# Portfolio-A weekly report — 2026-08-08 (deployed 2026-07-02, 5.1 weeks / 1.18 months)

| sleeve | this wk | exp/wk | total | cum R | fwd R/mo | exp R/mo | verdict |
|---|--:|--:|--:|--:|--:|--:|---|
| SPX500_Fri_M15 | 1 | 0.6 | 6 | -4.71 | -3.98 | +1.22 | watch |
| GER40_Wed_M5 | 1 | 0.7 | 3 | +2.34 | +1.98 | +1.69 | warming up |
| NAS100_Thu_M5 | 1 | 0.6 | 4 | +1.48 | +1.25 | +0.47 | in-band |
| JPN225_Wed_M5 | 1 | 0.7 | 2 | -1.90 | -1.60 | +1.19 | warming up |
| JPN225_Thu_M5 | 1 | 0.7 | 4 | -6.71 | -5.68 | +0.22 | watch |
| NQ_Friday_M15 | 1 | 1.0 | 5 | -1.94 | -1.64 | +1.20 | watch |
| EURUSD_v116 | 3 | 4.8 | 14 | +3.81 | +3.22 | +2.36 | in-band |

**Portfolio:** cum -7.63 R ($-106.78) · equity $9874.27 · DD from peak **$126** vs limit $600 (worst backtest month −$130)

## Correlated portfolio p99 (backtest+live, deploy-real JPN 0.1-lot, vs $600)
- **p99 $553** (92% of $600, margin 8%) · p99.5 $618 (103%) → **FLAG: p99 pushing toward limit (>540)**
- recomputed each week on the growing live ledger — rising p99 = forward tail heavier than backtest

## Cost check (realized median entry spread vs 1.25× model)
- SPX500_Fri_M15: no live cost rows yet
- GER40_Wed_M5: no live cost rows yet
- NAS100_Thu_M5: no live cost rows yet
- NQ/EURUSD: own ledger formats — cost watch via realized R vs expectation (above).

## EURUSD watch (largest contributor, fattest tail)
- n=14 < 30 — rolling-PF watch starts at 30 closed trades (no week-noise verdicts)

## Promotion-gate counter (pre-registered)
- trades: **39 / 40** · months: **1.18 / 3.0**
- R in-band: see verdicts above · costs ≤1.25×: see cost check · correlation blow-up: n/a until ≥8 weeks of per-sleeve weekly R
