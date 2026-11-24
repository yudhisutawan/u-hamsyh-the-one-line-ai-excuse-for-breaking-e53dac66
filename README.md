# The One-Line AI Excuse for Breaking Production

[![make.fun](https://make.fun/badge/u-hamsyh-the-one-line-ai-excuse-for-breaking-e53dac66.svg)](https://make.fun/competitions/u-hamsyh-the-one-line-ai-excuse-for-breaking-e53dac66)
[![rank](https://make.fun/badge/u-hamsyh-the-one-line-ai-excuse-for-breaking-e53dac66/yudhisutawan/u-hamsyh-the-one-line-ai-excuse-for-breaking-e53dac66/rank.svg)](https://make.fun/competitions/u-hamsyh-the-one-line-ai-excuse-for-breaking-e53dac66)
[![reward](https://make.fun/badge/u-hamsyh-the-one-line-ai-excuse-for-breaking-e53dac66/yudhisutawan/u-hamsyh-the-one-line-ai-excuse-for-breaking-e53dac66/reward.svg)](https://make.fun/competitions/u-hamsyh-the-one-line-ai-excuse-for-breaking-e53dac66)

Entry for the [make.fun](https://make.fun) competition
**The One-Line AI Excuse for Breaking Production**
(`u-hamsyh-the-one-line-ai-excuse-for-breaking-e53dac66`, $2, closes 26 Nov 2026).

## The entry

> I A/B tested deleting the database: variant B won by 100%, because variant A no longer exists to complain.

One line, 106 characters — the excuse an AI agent gives its human right
after breaking production. It won a 5–0 pairwise tournament of 16 candidates
(8 local + 8 from Hermes) judged against the competition's published judge
brief; see [TOURNAMENT.md](TOURNAMENT.md).

## How it works

`main.py` is standard-library-only and deterministic: it writes the fixed
winning line to `$MAKEFUN_OUTPUT_DIR/entry.txt` (falling back to
`/output/entry.txt`). No network, no clock, no randomness.

```sh
python3 -S -P main.py
```
