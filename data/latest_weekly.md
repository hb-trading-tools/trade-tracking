# Portfolio-A weekly report — 2026-08-01 (deployed 2026-07-02, 4.1 weeks / 0.95 months)

| sleeve | this wk | exp/wk | total | cum R | fwd R/mo | exp R/mo | verdict |
|---|--:|--:|--:|--:|--:|--:|---|
| SPX500_Fri_M15 | 1 | 0.6 | 5 | -3.72 | -3.90 | +1.22 | watch |
| GER40_Wed_M5 | 1 | 0.7 | 2 | +3.31 | +3.47 | +1.69 | warming up |
| NAS100_Thu_M5 | 1 | 0.6 | 3 | -0.03 | -0.03 | +0.47 | warming up |
| JPN225_Wed_M5 | 0 | 0.7 | 1 | -2.22 | -2.33 | +1.19 | warming up |
| JPN225_Thu_M5 | 1 | 0.7 | 3 | -6.40 | -6.72 | +0.22 | warming up |
| NQ_Friday_M15 | 1 | 1.0 | 4 | -1.42 | -1.49 | +1.20 | watch |
| EURUSD_v116 | 2 | 4.8 | 11 | +8.00 | +8.40 | +2.36 | in-band |

**Portfolio:** cum -2.48 R ($-34.66) · equity $9981.13 · DD from peak **$19** vs limit $600 (worst backtest month −$130)

## Correlated portfolio p99 (backtest+live, deploy-real JPN 0.1-lot, vs $600)
- **p99 $507** (84% of $600, margin 16%) · p99.5 $548 (91%) → OK (within budget)
- recomputed each week on the growing live ledger — rising p99 = forward tail heavier than backtest

## Cost check (realized median entry spread vs 1.25× model)
- SPX500_Fri_M15: no live cost rows yet
- GER40_Wed_M5: no live cost rows yet
- NAS100_Thu_M5: no live cost rows yet
- NQ/EURUSD: own ledger formats — cost watch via realized R vs expectation (above).

## EURUSD watch (largest contributor, fattest tail)
- n=11 < 30 — rolling-PF watch starts at 30 closed trades (no week-noise verdicts)

## Promotion-gate counter (pre-registered)
- trades: **30 / 40** · months: **0.95 / 3.0**
- R in-band: see verdicts above · costs ≤1.25×: see cost check · correlation blow-up: n/a until ≥8 weeks of per-sleeve weekly R
