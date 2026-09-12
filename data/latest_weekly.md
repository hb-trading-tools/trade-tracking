# Portfolio-A weekly report — 2026-09-12 (deployed 2026-07-02, 10.1 weeks / 2.33 months)

| sleeve | this wk | exp/wk | total | cum R | fwd R/mo | exp R/mo | verdict |
|---|--:|--:|--:|--:|--:|--:|---|
| SPX500_Fri_M15 | 0 | 0.6 | 8 | -4.47 | -1.92 | +1.22 | watch |
| GER40_Wed_M5 | 1 | 0.7 | 8 | +0.58 | +0.25 | +1.69 | in-band |
| NAS100_Thu_M5 | 1 | 0.6 | 9 | +2.44 | +1.04 | +0.47 | in-band |
| JPN225_Wed_M5 | 1 | 0.7 | 6 | -1.73 | -0.74 | +1.19 | watch |
| JPN225_Thu_M5 | 1 | 0.7 | 6 | -7.88 | -3.38 | +0.22 | watch |
| NQ_Friday_M15 | 1 | 1.0 | 10 | -4.20 | -1.80 | +1.20 | watch |
| EURUSD_v116 | 4 | 4.8 | 28 | +0.26 | +0.11 | +2.36 | watch |

**Portfolio:** cum -15.00 R ($-210.03) · equity $9780.37 · DD from peak **$220** vs limit $600 (worst backtest month −$130)

## Correlated portfolio p99 (backtest+live, deploy-real JPN 0.1-lot, vs $600)
- **p99 $585** (97% of $600, margin 3%) · p99.5 $636 (106%) → **FLAG: p99 pushing toward limit (>540)**
- recomputed each week on the growing live ledger — rising p99 = forward tail heavier than backtest

## Cost check (realized median entry spread vs 1.25× model)
- SPX500_Fri_M15: median 40 pts vs model 40 → OK (n=3)
- GER40_Wed_M5: median 150 pts vs model 80 → **OVER GATE** (150 > 100) (n=6)
- NAS100_Thu_M5: median 100 pts vs model 80 → OK (n=3)
- NQ/EURUSD: own ledger formats — cost watch via realized R vs expectation (above).

## EURUSD watch (largest contributor, fattest tail)
- n=28 < 30 — rolling-PF watch starts at 30 closed trades (no week-noise verdicts)

## Promotion-gate counter (pre-registered)
- trades: **76 / 40** · months: **2.33 / 3.0**
- R in-band: see verdicts above · costs ≤1.25×: see cost check · correlation blow-up: compute per-sleeve weekly-R corr matrix
