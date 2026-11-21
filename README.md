# Friday 20 November 2026 — One Day of World News, One Picture

[![make.fun · news-image-20261120](https://make.fun/badge/news-image-20261120.svg)](https://make.fun/bounty/news-image-20261120?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261120)
[![rank](https://make.fun/badge/news-image-20261120/erlansyahm90-code/news-image-20261120/rank.svg)](https://make.fun/bounty/news-image-20261120/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261120)
[![reward](https://make.fun/badge/news-image-20261120/erlansyahm90-code/news-image-20261120/reward.svg)](https://make.fun/bounty/news-image-20261120?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261120)

Entry for the make.fun bounty **Sum up 20 November's world news in one image**:
https://make.fun/bounty/news-image-20261120

## The poster

A one-page newspaper front page for **Friday 20 November 2026** — 48 stories,
7 regions, every one of them verified as having happened or first been
reported on that day:

- **4 lead stories, illustrated:** Russia's missile strikes on Kyiv's
  bridges; a tanker hit by a naval mine east of the Strait of Hormuz;
  Asia's chip-stock crash (Nikkei −4.5%, KOSPI −4.7%, SoftBank −14%),
  now including Wall Street's Friday close (S&P −3.7%, Nasdaq −5.3%,
  both into correction); COP31 closing with the fossil-fuel phase-out
  dropped.
- **12 medium stories, illustrated:** drones closing Genoa airport, GTA 6's
  record $3.79 billion day-one launch (32.5 million copies pre-sold,
  per Take-Two/Rockstar), Russian missiles crashing in south-east Poland,
  Cyclone Akvan, the Pete Rose pardon, the Prince and Princess of Wales in
  New Delhi, Alcaraz and Medvedev reaching the ATP Finals semi-finals,
  Riyadh confirming the PIF Tower hit, Tesla opening orders in Argentina,
  the IEA's $3.9 trillion AI data-centre warning, South Sudan's postponed
  elections, and the Ethiopia–Eritrea border build-up. (Taiwan's
  short-selling clampdown and Cyclone Xavier moved to the "Also" list.)
- **32 more stories** in the numbered "Also on Friday" list.
- **A UTC timeline strip** (overnight → evening, now ending with GTA 6's
  record launch), a **world map with numbered
  pins** for stories 1–16 and dots for 17–48, and a **DATE CHECK box**
  listing the previous day's big stories that were deliberately left out
  (the Trump–Xi–Putin summit, the ICJ Rohingya ruling, Anthropic's IPO
  debut, the Gaza scorecard, the US Senate war-powers vote, the Houthi
  missile on Riyadh's PIF Tower, the third Crimean Bridge strike,
  Bukele's third-term registration, the Haiti raid, the Trump–NYT ruling,
  the cyber chief's ouster).

Sources: Reuters, AP, BBC, The Hindu, CNBC, AFP, Al Jazeera, Times of
India, USGS, Formula 1, Take-Two, US DOJ. All illustrations are original
drawings made for this entry.

## How it works

- `main.py` — the entry program (Python, stdlib only, fully offline). It
  copies the bundled `entry.png` to `/output/entry.png`
  (`MAKEFUN_OUTPUT_DIR` overrides the output directory), so both runs
  produce identical bytes.
- `entry.png` — the poster itself, 1024×1024, under 1 MiB.
- `build_image.py` — the local build tool that rendered `entry.png`
  (Pillow + DejaVu fonts). Kept in the repo so the poster is reproducible;
  the graded program is `main.py`.

## Run

```sh
python3 main.py
# writes /output/entry.png (or $MAKEFUN_OUTPUT_DIR/entry.png)
```
