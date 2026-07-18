# Portfolio-A weekly report — 2026-07-18 (deployed 2026-07-02, 2.1 weeks / 0.49 months)

| sleeve | this wk | exp/wk | total | cum R | fwd R/mo | exp R/mo | verdict |
|---|--:|--:|--:|--:|--:|--:|---|
| SPX500_Fri_M15 | 1 | 0.6 | 3 | -1.74 | -3.52 | +1.22 | warming up |
| GER40_Wed_M5 | 0 | 0.7 | 0 | +0.00 | +0.00 | +1.69 | warming up |
| NAS100_Thu_M5 | 0 | 0.6 | 1 | -0.96 | -1.94 | +0.47 | warming up |
| JPN225_Wed_M5 | 0 | 0.7 | 1 | -2.22 | -4.50 | +1.19 | warming up |
| JPN225_Thu_M5 | 0 | 0.7 | 1 | -2.29 | -4.65 | +0.22 | warming up |
| NQ_Friday_M15 | 1 | 1.0 | 2 | -0.37 | -0.75 | +1.20 | warming up |
| EURUSD_v116 | 3 | 4.8 | 7 | +3.62 | +7.35 | +2.36 | warming up |

**Portfolio:** cum -3.95 R ($-55.27) · equity $9939.41 · DD from peak **$61** vs limit $600 (worst backtest month −$130)

## Correlated portfolio p99 (backtest+live, deploy-real JPN 0.1-lot, vs $600)
- **p99 $510** (85% of $600, margin 15%) · p99.5 $556 (93%) → OK (within budget)
- recomputed each week on the growing live ledger — rising p99 = forward tail heavier than backtest

## Cost check (realized median entry spread vs 1.25× model)
- SPX500_Fri_M15: median 160 pts vs model 40 → **OVER GATE** (160 > 50) (n=1)
- GER40_Wed_M5: no live cost rows yet
- NAS100_Thu_M5: median 100 pts vs model 80 → OK (n=1)
- NQ/EURUSD: own ledger formats — cost watch via realized R vs expectation (above).

## EURUSD watch (largest contributor, fattest tail)
- n=7 < 30 — rolling-PF watch starts at 30 closed trades (no week-noise verdicts)

## Promotion-gate counter (pre-registered)
- trades: **16 / 40** · months: **0.49 / 3.0**
- R in-band: see verdicts above · costs ≤1.25×: see cost check · correlation blow-up: n/a until ≥8 weeks of per-sleeve weekly R
