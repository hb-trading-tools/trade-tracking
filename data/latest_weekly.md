# Portfolio-A weekly report — 2026-07-11 (deployed 2026-07-02, 1.1 weeks / 0.26 months)

| sleeve | this wk | exp/wk | total | cum R | fwd R/mo | exp R/mo | verdict |
|---|--:|--:|--:|--:|--:|--:|---|
| SPX500_Fri_M15 | 1 | 0.6 | 2 | -2.04 | -7.77 | +1.22 | warming up |
| GER40_Wed_M5 | 0 | 0.7 | 0 | +0.00 | +0.00 | +1.69 | warming up |
| NAS100_Thu_M5 | 1 | 0.6 | 1 | -0.96 | -3.64 | +0.47 | warming up |
| JPN225_Wed_M5 | 1 | 0.7 | 1 | -2.22 | -8.44 | +1.19 | warming up |
| JPN225_Thu_M5 | 1 | 0.7 | 1 | -2.29 | -8.72 | +0.22 | warming up |
| NQ_Friday_M15 | 1 | 1.0 | 1 | -0.93 | -3.54 | +1.20 | warming up |
| EURUSD_v116 | 4 | 4.8 | 4 | -2.54 | -9.65 | +2.36 | warming up |

**Portfolio:** cum -10.97 R ($-153.63) · equity $9840.36 · DD from peak **$160** vs limit $600 (worst backtest month −$130)

## Correlated portfolio p99 (backtest+live, deploy-real JPN 0.1-lot, vs $600)
- **p99 $510** (85% of $600, margin 15%) · p99.5 $556 (93%) → OK (within budget)
- recomputed each week on the growing live ledger — rising p99 = forward tail heavier than backtest

## Cost check (realized median entry spread vs 1.25× model)
- SPX500_Fri_M15: median 40 pts vs model 40 → OK (n=1)
- GER40_Wed_M5: no live cost rows yet
- NAS100_Thu_M5: median 100 pts vs model 80 → OK (n=1)
- NQ/EURUSD: own ledger formats — cost watch via realized R vs expectation (above).

## EURUSD watch (largest contributor, fattest tail)
- n=4 < 30 — rolling-PF watch starts at 30 closed trades (no week-noise verdicts)

## Promotion-gate counter (pre-registered)
- trades: **11 / 40** · months: **0.26 / 3.0**
- R in-band: see verdicts above · costs ≤1.25×: see cost check · correlation blow-up: n/a until ≥8 weeks of per-sleeve weekly R
