# Portfolio-A weekly report — 2026-10-10 (deployed 2026-07-02, 14.1 weeks / 3.25 months)

| sleeve | this wk | exp/wk | total | cum R | fwd R/mo | exp R/mo | verdict |
|---|--:|--:|--:|--:|--:|--:|---|
| SPX500_Fri_M15 | 1 | 0.6 | 12 | -6.93 | -2.13 | +1.22 | watch |
| GER40_Wed_M5 | 1 | 0.7 | 10 | -1.93 | -0.59 | +1.69 | watch |
| NAS100_Thu_M5 | 1 | 0.6 | 12 | +1.96 | +0.60 | +0.47 | in-band |
| JPN225_Wed_M5 | 0 | 0.7 | 8 | -0.87 | -0.27 | +1.19 | in-band |
| JPN225_Thu_M5 | 0 | 0.7 | 7 | -5.17 | -1.59 | +0.22 | watch |
| NQ_Friday_M15 | 0 | 1.0 | 13 | -5.93 | -1.82 | +1.20 | watch |
| EURUSD_v116 | 4 | 4.8 | 39 | -3.93 | -1.21 | +2.36 | watch |

**Portfolio:** cum -22.79 R ($-319.07) · equity $9613.41 · DD from peak **$387** vs limit $600 (worst backtest month −$130)

## Correlated portfolio p99 (backtest+live, deploy-real JPN 0.1-lot, vs $600)
- **p99 $591** (98% of $600, margin 2%) · p99.5 $638 (106%) → **FLAG: p99 pushing toward limit (>540)**
- recomputed each week on the growing live ledger — rising p99 = forward tail heavier than backtest

## Cost check (realized median entry spread vs 1.25× model)
- SPX500_Fri_M15: median 40 pts vs model 40 → OK (n=3)
- GER40_Wed_M5: median 150 pts vs model 80 → **OVER GATE** (150 > 100) (n=1)
- NAS100_Thu_M5: median 100 pts vs model 80 → OK (n=2)
- NQ/EURUSD: own ledger formats — cost watch via realized R vs expectation (above).

## EURUSD watch (largest contributor, fattest tail)
- rolling PF over last 30: **0.65** — **FLAG: below 1.2**

## Promotion-gate counter (pre-registered)
- trades: **102 / 40** · months: **3.25 / 3.0**
- R in-band: see verdicts above · costs ≤1.25×: see cost check · correlation blow-up: compute per-sleeve weekly-R corr matrix
- **GATE COUNTABLY REACHED** — if R/costs/correlation are green, the re-sizing decision (toward p99 ~$5,200–5,500) and the 100k step become available (CEO decision).
