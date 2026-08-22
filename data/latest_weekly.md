# Portfolio-A weekly report — 2026-08-22 (deployed 2026-07-02, 7.1 weeks / 1.64 months)

| sleeve | this wk | exp/wk | total | cum R | fwd R/mo | exp R/mo | verdict |
|---|--:|--:|--:|--:|--:|--:|---|
| SPX500_Fri_M15 | 0 | 0.6 | 7 | -3.43 | -2.09 | +1.22 | watch |
| GER40_Wed_M5 | 1 | 0.7 | 5 | +3.75 | +2.28 | +1.69 | in-band |
| NAS100_Thu_M5 | 1 | 0.6 | 6 | +0.90 | +0.55 | +0.47 | in-band |
| JPN225_Wed_M5 | 1 | 0.7 | 4 | -2.48 | -1.51 | +1.19 | watch |
| JPN225_Thu_M5 | 1 | 0.7 | 5 | -8.37 | -5.10 | +0.22 | watch |
| NQ_Friday_M15 | 1 | 1.0 | 7 | -2.18 | -1.32 | +1.20 | watch |
| EURUSD_v116 | 1 | 4.8 | 18 | -0.46 | -0.28 | +2.36 | watch |

**Portfolio:** cum -12.26 R ($-171.69) · equity $9819.64 · DD from peak **$180** vs limit $600 (worst backtest month −$130)

## Correlated portfolio p99 (backtest+live, deploy-real JPN 0.1-lot, vs $600)
- **p99 $552** (92% of $600, margin 8%) · p99.5 $605 (101%) → **FLAG: p99 pushing toward limit (>540)**
- recomputed each week on the growing live ledger — rising p99 = forward tail heavier than backtest

## Cost check (realized median entry spread vs 1.25× model)
- SPX500_Fri_M15: no live cost rows yet
- GER40_Wed_M5: no live cost rows yet
- NAS100_Thu_M5: median 100 pts vs model 80 → OK (n=1)
- NQ/EURUSD: own ledger formats — cost watch via realized R vs expectation (above).

## EURUSD watch (largest contributor, fattest tail)
- n=18 < 30 — rolling-PF watch starts at 30 closed trades (no week-noise verdicts)

## Promotion-gate counter (pre-registered)
- trades: **53 / 40** · months: **1.64 / 3.0**
- R in-band: see verdicts above · costs ≤1.25×: see cost check · correlation blow-up: n/a until ≥8 weeks of per-sleeve weekly R
