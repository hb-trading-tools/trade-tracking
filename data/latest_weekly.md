# Portfolio-A weekly report — 2026-08-29 (deployed 2026-07-02, 8.1 weeks / 1.87 months)

| sleeve | this wk | exp/wk | total | cum R | fwd R/mo | exp R/mo | verdict |
|---|--:|--:|--:|--:|--:|--:|---|
| SPX500_Fri_M15 | 1 | 0.6 | 8 | -4.47 | -2.39 | +1.22 | watch |
| GER40_Wed_M5 | 1 | 0.7 | 6 | +2.57 | +1.37 | +1.69 | in-band |
| NAS100_Thu_M5 | 1 | 0.6 | 7 | +1.13 | +0.60 | +0.47 | in-band |
| JPN225_Wed_M5 | 1 | 0.7 | 5 | +0.24 | +0.13 | +1.19 | in-band |
| JPN225_Thu_M5 | 0 | 0.7 | 5 | -8.37 | -4.47 | +0.22 | watch |
| NQ_Friday_M15 | 1 | 1.0 | 8 | -3.16 | -1.68 | +1.20 | watch |
| EURUSD_v116 | 3 | 4.8 | 21 | -0.63 | -0.33 | +2.36 | watch |

**Portfolio:** cum -12.68 R ($-177.55) · equity $9774.35 · DD from peak **$226** vs limit $600 (worst backtest month −$130)

## Correlated portfolio p99 (backtest+live, deploy-real JPN 0.1-lot, vs $600)
- **p99 $566** (94% of $600, margin 6%) · p99.5 $618 (103%) → **FLAG: p99 pushing toward limit (>540)**
- recomputed each week on the growing live ledger — rising p99 = forward tail heavier than backtest

## Cost check (realized median entry spread vs 1.25× model)
- SPX500_Fri_M15: median 40 pts vs model 40 → OK (n=3)
- GER40_Wed_M5: no live cost rows yet
- NAS100_Thu_M5: median 100 pts vs model 80 → OK (n=1)
- NQ/EURUSD: own ledger formats — cost watch via realized R vs expectation (above).

## EURUSD watch (largest contributor, fattest tail)
- n=21 < 30 — rolling-PF watch starts at 30 closed trades (no week-noise verdicts)

## Promotion-gate counter (pre-registered)
- trades: **61 / 40** · months: **1.87 / 3.0**
- R in-band: see verdicts above · costs ≤1.25×: see cost check · correlation blow-up: compute per-sleeve weekly-R corr matrix
