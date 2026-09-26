# Portfolio-A weekly report — 2026-09-26 (deployed 2026-07-02, 12.1 weeks / 2.79 months)

| sleeve | this wk | exp/wk | total | cum R | fwd R/mo | exp R/mo | verdict |
|---|--:|--:|--:|--:|--:|--:|---|
| SPX500_Fri_M15 | 1 | 0.6 | 10 | -6.57 | -2.35 | +1.22 | watch |
| GER40_Wed_M5 | 0 | 0.7 | 9 | -0.63 | -0.22 | +1.69 | watch |
| NAS100_Thu_M5 | 1 | 0.6 | 11 | +2.93 | +1.05 | +0.47 | in-band |
| JPN225_Wed_M5 | 0 | 0.7 | 7 | -2.06 | -0.74 | +1.19 | watch |
| JPN225_Thu_M5 | 0 | 0.7 | 6 | -7.88 | -2.82 | +0.22 | watch |
| NQ_Friday_M15 | 1 | 1.0 | 12 | -4.94 | -1.77 | +1.20 | watch |
| EURUSD_v116 | 2 | 4.8 | 34 | +1.52 | +0.54 | +2.36 | watch |

**Portfolio:** cum -17.62 R ($-246.69) · equity $9737.11 · DD from peak **$263** vs limit $600 (worst backtest month −$130)

## Correlated portfolio p99 (backtest+live, deploy-real JPN 0.1-lot, vs $600)
- **p99 $593** (99% of $600, margin 1%) · p99.5 $641 (107%) → **FLAG: p99 pushing toward limit (>540)**
- recomputed each week on the growing live ledger — rising p99 = forward tail heavier than backtest

## Cost check (realized median entry spread vs 1.25× model)
- SPX500_Fri_M15: median 40 pts vs model 40 → OK (n=1)
- GER40_Wed_M5: no live cost rows yet
- NAS100_Thu_M5: median 100 pts vs model 80 → OK (n=1)
- NQ/EURUSD: own ledger formats — cost watch via realized R vs expectation (above).

## EURUSD watch (largest contributor, fattest tail)
- rolling PF over last 30: **1.22** (≥1.2 OK)

## Promotion-gate counter (pre-registered)
- trades: **90 / 40** · months: **2.79 / 3.0**
- R in-band: see verdicts above · costs ≤1.25×: see cost check · correlation blow-up: compute per-sleeve weekly-R corr matrix
