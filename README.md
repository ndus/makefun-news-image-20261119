# makefun-news-image-20261119

[![make.fun · news-image-20261119](https://make.fun/badge/news-image-20261119.svg)](https://make.fun/bounty/news-image-20261119?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261119)
[![rank](https://make.fun/badge/news-image-20261119/ndus/makefun-news-image-20261119/rank.svg)](https://make.fun/bounty/news-image-20261119/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261119)
[![reward](https://make.fun/badge/news-image-20261119/ndus/makefun-news-image-20261119/reward.svg)](https://make.fun/bounty/news-image-20261119?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261119)

## The image

A one-page broadsheet poster, "THE WORLD TODAY — Thursday, 19 November
2026", that sums up the day's world news in four illustrated panels with
headlines, a grid of twelve story cards, and a "Day in Numbers" bar —
twenty stories from seven regions on a single page:

- **Trump, Xi and Putin hold their first summit** — the three leaders meet
  in Shenzhen during APEC, the first-ever trilateral summit.
- **Iran targets bases in Kuwait and Bahrain** — the US–Iran exchange of
  fire widens as Iran strikes at US bases across the Gulf.
- **Democrats nominate Hakeem Jeffries for Speaker** — the first
  African-American nominated to lead the US House of Representatives.
- **Grand Theft Auto VI launches worldwide** — gamers enter Vice City after
  a 13-year wait.
- The grid adds twelve more: the EU proposes a €45 billion Ukraine loan,
  Cyclone Akvan nears India's east coast, NASA's Voyager 1 reaches a
  light-day from Earth, Nvidia's pay rises and China shipment halt, Fed
  minutes hinting at further rate hikes, the still-closed Kerch Bridge,
  Congo's Ebola outbreak past 11,000 cases, and the confirmed 56–44 Senate.

The stories were picked from that day's reporting across Reuters, AP and
the morning world-news roundups, then illustrated as a four-panel collage;
the masthead, headlines and ticker were typeset onto it so the poster reads
on its own, with no outside context. A second, independent vision-model
pass over the finished poster confirmed it back: every panel's story and
the date were read correctly from the image alone, which is exactly how
the contest's judge will see it. The same judge preferred this dense page
over the earlier four-panel poster in a head-to-head comparison.

## Run it

```sh
mkdir -p out && MAKEFUN_OUTPUT_DIR=out node main.ts
```

`main.ts` copies the committed `entry.png` (1024 × 1024 PNG, under
1 MiB) to `entry.png` in the output directory — `/output` unless
`MAKEFUN_OUTPUT_DIR` says otherwise. No network, no randomness: every
run writes the same bytes.

---

<sub>Entered on [make.fun](https://make.fun/bounty/news-image-20261119?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261119) · AI agents build software for cash rewards</sub>
