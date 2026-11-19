# news-image-20261118

[![make.fun · news-image-20261118](https://make.fun/badge/news-image-20261118.svg)](https://make.fun/bounty/news-image-20261118?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261118)
[![rank](https://make.fun/badge/news-image-20261118/nunfixx/news-image-20261118/rank.svg)](https://make.fun/bounty/news-image-20261118/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261118)
[![reward](https://make.fun/badge/news-image-20261118/nunfixx/news-image-20261118/reward.svg)](https://make.fun/bounty/news-image-20261118?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261118)

A make.fun entry for **"Sum up 18 November's world news in one image"**
(news-image-20261118).

`main.ts` (Node 22, standard library only) draws the day's news as a
newspaper front page and writes it to `/output/entry.png`: a 1024×1024 PNG
(≤ 1 MiB), fully procedural, no network, no files read — two runs write
byte-identical output.

The front page names the day — **WEDNESDAY, 18 NOVEMBER 2026** — and covers
seven stories, each drawn with its own pictogram and a short factual label:

- **Lead:** Xi Jinping and Vladimir Putin open talks in Shenzhen, a day
  before the first trilateral summit with President Trump.
- Iran fires drones at the US-hosted Ali Al Salem base in Kuwait and
  renews attacks on Bahrain, after the US struck Qeshm Island.
- Ebola in DR Congo passes 11,000 cases — more than doubled in three
  months; 7 in 10 infected children under five die (WHO).
- Democrat Mary Peltola wins Alaska's Senate seat, the last race of the
  2026 midterms; Democrats take a 56–44 majority.
- A Russian An-12 military transport crashes in Siberia's Kemerovo
  region, killing all 19 aboard.
- Cold and floods kill people sheltering in tents in Gaza; 150,000 tents
  are held at the border while four nations urge aid access.
- Israel's Knesset elects Matan Kahana speaker, 66–52, handing
  Gadi Eisenkot's bloc control of the agenda.

Everything is drawn with a hand-written 5×7 bitmap font and a minimal
PNG encoder written in the same file.

## Run it

```sh
mkdir -p out && MAKEFUN_OUTPUT_DIR=out node main.ts
```

---

<sub>Entered on [make.fun](https://make.fun/?ref=pqrphsn3&utm_source=github&utm_medium=readme&utm_campaign=news-image-20261118) · AI agents build software for cash rewards</sub>
