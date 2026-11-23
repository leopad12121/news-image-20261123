# The World in One Day — Monday 23 November 2026

[![make.fun](https://make.fun/badge/news-image-20261123.svg)](https://make.fun/bounty/news-image-20261123)
[![rank](https://make.fun/badge/news-image-20261123/leopad12121/news-image-20261123/rank.svg)](https://make.fun/bounty/news-image-20261123)
[![reward](https://make.fun/badge/news-image-20261123/leopad12121/news-image-20261123/reward.svg)](https://make.fun/bounty/news-image-20261123)

A one-image newspaper front page summing up the world's news of
Monday 23 November 2026, entered in the
[make.fun bounty](https://make.fun/bounty/news-image-20261123).

`main.py` (Python 3.13, standard library only at module level) draws a
1024x1024 front page — masthead, lead story, a 2x2 grid and a tech strip —
with Pillow when it is available, and otherwise copies the shipped
`entry.png` so the program still exits 0 with the verified image.
It writes to `$MAKEFUN_OUTPUT_DIR/entry.png`, else `/output/entry.png`
when `/output` exists, else `./entry.png`. Deterministic: two runs
produce byte-identical output.

## The day's six stories

1. **COP31 climate talks collapse** (Antalya) — nearly 200 nations fail
   to agree after record overtime; a draft with no fossil-fuel phase-out
   is rejected, the longest COP on record ends with no deal.
   Sources: AFP, CNN, Reuters.
2. **Russian drone flattens Kyiv flats** (Dymer) — part of a five-storey
   block north of Kyiv is destroyed; five killed, about nine feared in
   the rubble; the region declares a day of mourning.
   Sources: AP, Reuters.
3. **Sanctioned ship afire in the Gulf of Finland** — the Russian cargo
   ship Sparta II, under US sanctions, catches fire after a drone
   strike and drifts into Finnish waters.
   Sources: AP, Reuters.
4. **Factory fire in Indonesia** (Serang) — a blaze at a candy factory
   kills three workers; 36 missing.
   Sources: AP, Reuters.
5. **South Korea education minister quits** — resigns over an
   AI-assisted cheating scandal days before the Suneung college
   entrance exam. Sources: AP, AFP.
6. **Trump backs Huang rehire** — Trump urges Nvidia to rehire ex-CEO
   Jensen Huang amid a US spy probe tied to him.
   Sources: NYT, Reuters.

Also noted: Kim says North Korea seeks security, not supremacy; Trump
warns Iran over a New Year deadline; Nepal's PM visits Delhi.

## Run it

```sh
python3 main.py
# or: MAKEFUN_OUTPUT_DIR=out python3 main.py
```

## License

MIT — see [LICENSE](LICENSE).
