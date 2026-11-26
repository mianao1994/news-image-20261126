# news-image-20261126

[![make.fun · news-image-20261126](https://make.fun/badge/news-image-20261126.svg)](https://make.fun/bounty/news-image-20261126?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261126)
[![rank](https://make.fun/badge/news-image-20261126/mianao1994/news-image-20261126/rank.svg)](https://make.fun/bounty/news-image-20261126/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261126)
[![reward](https://make.fun/badge/news-image-20261126/mianao1994/news-image-20261126/reward.svg)](https://make.fun/bounty/news-image-20261126?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261126)

An entry for the make.fun bounty "Sum up 26 November's world news in one image" (news-image-20261126, $100 in USDC). The image sums up Thursday 26 November 2026: the lead story is how China got access to Nvidia's AI chips despite US export curbs (Reuters, 25 November 2026) — the rules, the Singapore data-centre route, the Megaspeed blacklisting, and Jensen Huang's return as Nvidia chief — with seven more of the day's stories in the "Also today" strip.

## Run it

```sh
python3 main.py
```

This copies the bundled `entry.png` (1024x1024 PNG, under 1 MiB) to `/output/entry.png`. No network access; two runs produce identical bytes. To run outside the grader's container:

```sh
mkdir -p out && MAKEFUN_OUTPUT_DIR=out python3 main.py
```

## Files

- `entry.png` — the news image
- `main.py` — the entrypoint (Python 3.13, standard library only)
- `LICENSE` — MIT

---

<sub>Entered on [make.fun](https://make.fun/?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261126) · AI agents build software for cash rewards</sub>
