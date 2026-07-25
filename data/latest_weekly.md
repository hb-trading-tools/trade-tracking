# Portfolio-A weekly report — 2026-07-25 (deployed 2026-07-02, 3.1 weeks / 0.72 months)

| sleeve | this wk | exp/wk | total | cum R | fwd R/mo | exp R/mo | verdict |
|---|--:|--:|--:|--:|--:|--:|---|
| SPX500_Fri_M15 | 1 | 0.6 | 4 | -2.75 | -3.81 | +1.22 | warming up |
| GER40_Wed_M5 | 1 | 0.7 | 1 | +0.33 | +0.46 | +1.69 | warming up |
| NAS100_Thu_M5 | 1 | 0.6 | 2 | -1.88 | -2.60 | +0.47 | warming up |
| JPN225_Wed_M5 | 0 | 0.7 | 1 | -2.22 | -3.07 | +1.19 | warming up |
| JPN225_Thu_M5 | 1 | 0.7 | 2 | -3.72 | -5.15 | +0.22 | warming up |
| NQ_Friday_M15 | 1 | 1.0 | 3 | -1.25 | -1.72 | +1.20 | warming up |
| EURUSD_v116 | 2 | 4.8 | 9 | +4.01 | +5.54 | +2.36 | warming up |

**Portfolio:** cum -7.48 R ($-104.69) · equity $9912.45 · DD from peak **$88** vs limit $600 (worst backtest month −$130)

## Correlated portfolio p99 (backtest+live, deploy-real JPN 0.1-lot, vs $600)
- **p99 $509** (85% of $600, margin 15%) · p99.5 $550 (92%) → OK (within budget)
- recomputed each week on the growing live ledger — rising p99 = forward tail heavier than backtest

## Cost check (realized median entry spread vs 1.25× model)
- SPX500_Fri_M15: no live cost rows yet
- GER40_Wed_M5: no live cost rows yet
- NAS100_Thu_M5: no live cost rows yet
- NQ/EURUSD: own ledger formats — cost watch via realized R vs expectation (above).

## EURUSD watch (largest contributor, fattest tail)
- n=9 < 30 — rolling-PF watch starts at 30 closed trades (no week-noise verdicts)

## Promotion-gate counter (pre-registered)
- trades: **23 / 40** · months: **0.72 / 3.0**
- R in-band: see verdicts above · costs ≤1.25×: see cost check · correlation blow-up: n/a until ≥8 weeks of per-sleeve weekly R
