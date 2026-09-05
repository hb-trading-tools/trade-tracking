# Portfolio-A weekly report — 2026-09-05 (deployed 2026-07-02, 9.1 weeks / 2.10 months)

| sleeve | this wk | exp/wk | total | cum R | fwd R/mo | exp R/mo | verdict |
|---|--:|--:|--:|--:|--:|--:|---|
| SPX500_Fri_M15 | 0 | 0.6 | 8 | -4.47 | -2.13 | +1.22 | watch |
| GER40_Wed_M5 | 1 | 0.7 | 7 | +1.66 | +0.79 | +1.69 | in-band |
| NAS100_Thu_M5 | 1 | 0.6 | 8 | +1.79 | +0.85 | +0.47 | in-band |
| JPN225_Wed_M5 | 0 | 0.7 | 5 | +0.24 | +0.11 | +1.19 | in-band |
| JPN225_Thu_M5 | 0 | 0.7 | 5 | -8.37 | -3.98 | +0.22 | watch |
| NQ_Friday_M15 | 1 | 1.0 | 9 | -4.04 | -1.92 | +1.20 | watch |
| EURUSD_v116 | 3 | 4.8 | 24 | -0.73 | -0.35 | +2.36 | watch |

**Portfolio:** cum -13.92 R ($-194.87) · equity $9754.04 · DD from peak **$246** vs limit $600 (worst backtest month −$130)

## Correlated portfolio p99 (backtest+live, deploy-real JPN 0.1-lot, vs $600)
- **p99 $566** (94% of $600, margin 6%) · p99.5 $618 (103%) → **FLAG: p99 pushing toward limit (>540)**
- recomputed each week on the growing live ledger — rising p99 = forward tail heavier than backtest

## Cost check (realized median entry spread vs 1.25× model)
- SPX500_Fri_M15: median 40 pts vs model 40 → OK (n=3)
- GER40_Wed_M5: median 150 pts vs model 80 → **OVER GATE** (150 > 100) (n=3)
- NAS100_Thu_M5: median 100 pts vs model 80 → OK (n=2)
- NQ/EURUSD: own ledger formats — cost watch via realized R vs expectation (above).

## EURUSD watch (largest contributor, fattest tail)
- n=24 < 30 — rolling-PF watch starts at 30 closed trades (no week-noise verdicts)

## Promotion-gate counter (pre-registered)
- trades: **67 / 40** · months: **2.10 / 3.0**
- R in-band: see verdicts above · costs ≤1.25×: see cost check · correlation blow-up: compute per-sleeve weekly-R corr matrix
