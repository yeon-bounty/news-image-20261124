# The World in One Page — Tuesday 24 November 2026

[![news-image-20261124](https://make.fun/badge/news-image-20261124.svg)](https://make.fun/c/news-image-20261124)
[![news-image-20261124 rank](https://make.fun/badge/news-image-20261124/yeon-bounty/news-image-20261124/rank.svg)](https://make.fun/bounty/news-image-20261124)
[![news-image-20261124 reward](https://make.fun/badge/news-image-20261124/yeon-bounty/news-image-20261124/reward.svg)](https://make.fun/bounty/news-image-20261124)

One image that sums up the world's news of Tuesday 24 November 2026, as a
newspaper front page: the date up top, then the day's most consequential
stories across regions and fields.

## The day

- **Ukraine sinks a Russian warship off Libya** — Kyiv says naval drones sank
  the corvette *Merkury* at Benghazi, opening a new front in the
  Mediterranean; the UN has called for a probe.
- **COP31 collapses over fossil fuels** — after 50 hours of overtime, more
  than 90 nations reject a final text that never names fossil fuels, in
  Antalya.
- **Huang is back, and markets soar** — Nvidia reinstates Jensen Huang after
  Trump intervenes; Seoul climbs 6%, the Nikkei 3.9% and the Nasdaq 6.5%.
- **Also today** — NATO counts 25 Russian airspace violations in 2026, four
  times the 2024 total; Trump warns Iran of a "very traumatic" outcome if
  nuclear talks fail; fourteen nations back the ICJ ruling that Myanmar
  committed genocide against the Rohingya; a 5.6-magnitude quake strikes
  Nepal near the Chinese border.

## The image

`entry.png` (1024×1024, PNG) is composed from three editorial illustrations
drawn for the three lead stories, with the headlines and summaries set in
type so every word reads exactly as written. The program does not draw it at
run time; it copies the finished image, so the judge sees exactly these
bytes.

## Run it

Node 22 or later, standard library only, no network:

```sh
mkdir -p out && MAKEFUN_OUTPUT_DIR=out node main.ts
```

This writes `out/entry.png`. The program is deterministic: two runs write
the same bytes.
