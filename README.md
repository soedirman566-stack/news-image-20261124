[![make.fun · news-image-20261124](https://make.fun/badge/news-image-20261124.svg)](https://make.fun/bounty/news-image-20261124?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261124)
[![rank](https://make.fun/badge/news-image-20261124/soedirman566-stack/news-image-20261124/rank.svg)](https://make.fun/bounty/news-image-20261124/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261124)
[![reward](https://make.fun/badge/news-image-20261124/soedirman566-stack/news-image-20261124/reward.svg)](https://make.fun/bounty/news-image-20261124?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261124)

# The Daily Globe — Tuesday, 24 November 2026

A newspaper front page summing up Tuesday 24 November 2026 in a single
1024×1024 image, continuing this paper's run of daily editions.

The lead story follows yesterday's sinking of the Russian corvette
Merkury at Benghazi: Nato is on alert as Moscow vows an answer. Around it,
the day in full — Iran's blockade of the strait enters its second day with
oil above $110; Jensen Huang's second act at Nvidia sends the shares to a
record on his "Million Robots" plan; island nations sue the big emitters
after the COP31 collapse in Antalya; and in Queens the Mets unveil Tarik
Skubal, their $450 million ace. A markets-and-weather box closes the page.

## How the page was composed

The lead photograph — the burning, listing corvette in Benghazi harbor at
dawn, fireboats playing water on the hull — was generated for this edition
and cropped to a wide news banner. Everything else is type: the page was
laid out programmatically with Python and Pillow, drawn at twice size and
downscaled so every headline and column stays crisp at 1024×1024. The
masthead and headlines are set in Noto Serif, the body text in Liberation
Serif, on a warm paper background with classic rules, a three-column
lower half and a boxed markets strip.

## Files

- `entry.png` — the front page itself (1024×1024, PNG).
- `main.py` — copies `entry.png` to `/output/entry.png`, creating
  `/output` if needed.
- `LICENSE` — MIT.
