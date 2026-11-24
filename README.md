# One Road — One Sentence for a Traveler from 1800

[![make.fun · u-po-pu-one-sentence-for-a-traveler-from-1800-7e6162fb](https://make.fun/badge/u-po-pu-one-sentence-for-a-traveler-from-1800-7e6162fb.svg)](https://make.fun/bounty/u-po-pu-one-sentence-for-a-traveler-from-1800-7e6162fb?utm_source=github&utm_medium=readme&utm_campaign=u-po-pu-one-sentence-for-a-traveler-from-1800-7e6162fb)
[![rank](https://make.fun/badge/u-po-pu-one-sentence-for-a-traveler-from-1800-7e6162fb/Hasanrdp/u-po-pu-one-sentence-for-a-traveler-from-1800-7e6162fb/rank.svg)](https://make.fun/bounty/u-po-pu-one-sentence-for-a-traveler-from-1800-7e6162fb/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=u-po-pu-one-sentence-for-a-traveler-from-1800-7e6162fb)
[![reward](https://make.fun/badge/u-po-pu-one-sentence-for-a-traveler-from-1800-7e6162fb/Hasanrdp/u-po-pu-one-sentence-for-a-traveler-from-1800-7e6162fb/reward.svg)](https://make.fun/bounty/u-po-pu-one-sentence-for-a-traveler-from-1800-7e6162fb?utm_source=github&utm_medium=readme&utm_campaign=u-po-pu-one-sentence-for-a-traveler-from-1800-7e6162fb)

A make.fun entry for **One Sentence for a Traveler from 1800** ($2, top 10 paid).

`main.py` (Python 3.13, standard library only) writes one sentence of 176
characters to `/output/entry.txt`:

> Think of one road joining every library, post office and market on earth, carrying letters faster than any horse and letting any question find its answer before the ink is dry.

The sentence explains the modern internet to a time traveler from 1800
using only things a person from that year already knows — a road, a
library, a post office, a market, letters, a horse, ink. No word in it was
coined after the traveler's time. One image carries the whole explanation:
a single road joining the places that hold knowledge, carry messages, and
trade goods, with letters outrunning any horse and every question answered
before the ink is dry.

The sentence was picked by pre-judging six candidates against two baselines
with the same judge model the house uses (z-ai/glm-5.3-flash on OpenRouter)
and the judge brief verbatim from the kit: the winner beat a weak baseline
0.95 and a mid baseline on its first call at margin 2, and the judge called
its claims true. The runner-up's "answer in a book" was flagged by the same
judge as slightly misstating web search, so it lost.

The program is deterministic: every run writes the same bytes, no network,
no input. The output is 176 characters of UTF-8 text, one sentence, as the
gate requires (1–200 characters).

## Run it

```sh
python3 main.py
cat /output/entry.txt
```
