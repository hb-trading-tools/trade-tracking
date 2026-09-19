# Portfolio-A weekly report — 2026-09-19 (deployed 2026-07-02, 11.1 weeks / 2.56 months)

| sleeve | this wk | exp/wk | total | cum R | fwd R/mo | exp R/mo | verdict |
|---|--:|--:|--:|--:|--:|--:|---|
| SPX500_Fri_M15 | 1 | 0.6 | 9 | -5.56 | -2.17 | +1.22 | watch |
| GER40_Wed_M5 | 1 | 0.7 | 9 | -0.63 | -0.25 | +1.69 | watch |
| NAS100_Thu_M5 | 1 | 0.6 | 10 | +2.34 | +0.91 | +0.47 | in-band |
| JPN225_Wed_M5 | 1 | 0.7 | 7 | -2.06 | -0.80 | +1.19 | watch |
| JPN225_Thu_M5 | 0 | 0.7 | 6 | -7.88 | -3.07 | +0.22 | watch |
| NQ_Friday_M15 | 1 | 1.0 | 11 | -3.96 | -1.54 | +1.20 | watch |
| EURUSD_v116 | 4 | 4.8 | 32 | +3.75 | +1.46 | +2.36 | in-band |

**Portfolio:** cum -13.99 R ($-195.79) · equity $9790.91 · DD from peak **$209** vs limit $600 (worst backtest month −$130)

## Correlated portfolio p99 (backtest+live, deploy-real JPN 0.1-lot, vs $600)
- **p99 $592** (99% of $600, margin 1%) · p99.5 $641 (107%) → **FLAG: p99 pushing toward limit (>540)**
- recomputed each week on the growing live ledger — rising p99 = forward tail heavier than backtest

## Cost check (realized median entry spread vs 1.25× model)
- SPX500_Fri_M15: median 40 pts vs model 40 → OK (n=3)
- GER40_Wed_M5: median 150 pts vs model 80 → **OVER GATE** (150 > 100) (n=3)
- NAS100_Thu_M5: median 100 pts vs model 80 → OK (n=1)
- NQ/EURUSD: own ledger formats — cost watch via realized R vs expectation (above).

## EURUSD watch (largest contributor, fattest tail)
- rolling PF over last 30: **1.34** (≥1.2 OK)

## Promotion-gate counter (pre-registered)
- trades: **85 / 40** · months: **2.56 / 3.0**
- R in-band: see verdicts above · costs ≤1.25×: see cost check · correlation blow-up: compute per-sleeve weekly-R corr matrix
