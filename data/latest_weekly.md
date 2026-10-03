# Portfolio-A weekly report — 2026-10-03 (deployed 2026-07-02, 13.1 weeks / 3.02 months)

| sleeve | this wk | exp/wk | total | cum R | fwd R/mo | exp R/mo | verdict |
|---|--:|--:|--:|--:|--:|--:|---|
| SPX500_Fri_M15 | 1 | 0.6 | 11 | -7.49 | -2.48 | +1.22 | watch |
| GER40_Wed_M5 | 0 | 0.7 | 9 | -0.63 | -0.21 | +1.69 | watch |
| NAS100_Thu_M5 | 0 | 0.6 | 11 | +2.93 | +0.97 | +0.47 | in-band |
| JPN225_Wed_M5 | 1 | 0.7 | 8 | -0.87 | -0.29 | +1.19 | in-band |
| JPN225_Thu_M5 | 1 | 0.7 | 7 | -5.17 | -1.71 | +0.22 | watch |
| NQ_Friday_M15 | 1 | 1.0 | 13 | -5.93 | -1.96 | +1.20 | watch |
| EURUSD_v116 | 1 | 4.8 | 35 | +0.48 | +0.16 | +2.36 | watch |

**Portfolio:** cum -16.68 R ($-233.47) · equity $9765.19 · DD from peak **$235** vs limit $600 (worst backtest month −$130)

## Correlated portfolio p99 (backtest+live, deploy-real JPN 0.1-lot, vs $600)
- **p99 $591** (99% of $600, margin 1%) · p99.5 $641 (107%) → **FLAG: p99 pushing toward limit (>540)**
- recomputed each week on the growing live ledger — rising p99 = forward tail heavier than backtest

## Cost check (realized median entry spread vs 1.25× model)
- SPX500_Fri_M15: median 40 pts vs model 40 → OK (n=2)
- GER40_Wed_M5: no live cost rows yet
- NAS100_Thu_M5: median 100 pts vs model 80 → OK (n=1)
- NQ/EURUSD: own ledger formats — cost watch via realized R vs expectation (above).

## EURUSD watch (largest contributor, fattest tail)
- rolling PF over last 30: **1.05** — **FLAG: below 1.2**

## Promotion-gate counter (pre-registered)
- trades: **95 / 40** · months: **3.02 / 3.0**
- R in-band: see verdicts above · costs ≤1.25×: see cost check · correlation blow-up: compute per-sleeve weekly-R corr matrix
- **GATE COUNTABLY REACHED** — if R/costs/correlation are green, the re-sizing decision (toward p99 ~$5,200–5,500) and the 100k step become available (CEO decision).
