# Portfolio-A weekly report — 2026-08-15 (deployed 2026-07-02, 6.1 weeks / 1.41 months)

| sleeve | this wk | exp/wk | total | cum R | fwd R/mo | exp R/mo | verdict |
|---|--:|--:|--:|--:|--:|--:|---|
| SPX500_Fri_M15 | 1 | 0.6 | 7 | -3.43 | -2.43 | +1.22 | watch |
| GER40_Wed_M5 | 1 | 0.7 | 4 | +4.66 | +3.30 | +1.69 | in-band |
| NAS100_Thu_M5 | 1 | 0.6 | 5 | +1.91 | +1.35 | +0.47 | in-band |
| JPN225_Wed_M5 | 1 | 0.7 | 3 | -0.88 | -0.62 | +1.19 | warming up |
| JPN225_Thu_M5 | 0 | 0.7 | 4 | -6.71 | -4.75 | +0.22 | watch |
| NQ_Friday_M15 | 1 | 1.0 | 6 | -1.25 | -0.88 | +1.20 | watch |
| EURUSD_v116 | 3 | 4.8 | 17 | +0.61 | +0.43 | +2.36 | watch |

**Portfolio:** cum -5.09 R ($-71.25) · equity $9923.91 · DD from peak **$76** vs limit $600 (worst backtest month −$130)

## Correlated portfolio p99 (backtest+live, deploy-real JPN 0.1-lot, vs $600)
- **p99 $553** (92% of $600, margin 8%) · p99.5 $603 (100%) → **FLAG: p99 pushing toward limit (>540)**
- recomputed each week on the growing live ledger — rising p99 = forward tail heavier than backtest

## Cost check (realized median entry spread vs 1.25× model)
- SPX500_Fri_M15: median 40 pts vs model 40 → OK (n=3)
- GER40_Wed_M5: no live cost rows yet
- NAS100_Thu_M5: no live cost rows yet
- NQ/EURUSD: own ledger formats — cost watch via realized R vs expectation (above).

## EURUSD watch (largest contributor, fattest tail)
- n=17 < 30 — rolling-PF watch starts at 30 closed trades (no week-noise verdicts)

## Promotion-gate counter (pre-registered)
- trades: **47 / 40** · months: **1.41 / 3.0**
- R in-band: see verdicts above · costs ≤1.25×: see cost check · correlation blow-up: n/a until ≥8 weeks of per-sleeve weekly R
