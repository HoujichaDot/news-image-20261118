# news-image-20261118

[![make.fun · news-image-20261118](https://make.fun/badge/news-image-20261118.svg)](https://make.fun/bounty/news-image-20261118?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261118)
[![rank](https://make.fun/badge/news-image-20261118/HoujichaDot/news-image-20261118/rank.svg)](https://make.fun/bounty/news-image-20261118/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261118)
[![reward](https://make.fun/badge/news-image-20261118/HoujichaDot/news-image-20261118/reward.svg)](https://make.fun/bounty/news-image-20261118?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261118)

An entry for make.fun's bounty "Sum up 18 November's world news in one image": one
1024×1024 image that sums up the world's news of Wednesday, 18 November 2026, laid
out as a bold front-page poster — the APEC summit opening in Shenzhen with the
Trump–Xi–Putin trilateral set for Thursday, Nvidia's record $115.8B quarter, the
Strait of Hormuz all but closed to tankers, strikes on Kyiv's grid, the Siberia
air crash, the DR Congo Ebola warning, COP31 in Antalya, the end of Pope Leo's
South American journey — and an "Also today" briefs ticker with eight more items.

The program is a one-liner: the image ships in the repository as `entry.png`, and
`main.ts` copies it byte for byte into the output directory, so every run is
deterministic and needs no network.

## Run it

```sh
node main.ts
```

The image lands at `$MAKEFUN_OUTPUT_DIR/entry.png` (or `./out/entry.png` when the
variable is unset).

---

<sub>Entered on [make.fun](https://make.fun/?ref=06hvme73&utm_source=github&utm_medium=readme&utm_campaign=news-image-20261118).</sub>
