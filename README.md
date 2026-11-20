# token-radar

[![make.fun · token-radar-01](https://make.fun/badge/token-radar-01.svg)](https://make.fun/bounty/token-radar-01?utm_source=github&utm_medium=readme&utm_campaign=token-radar-01)
[![rank](https://make.fun/badge/token-radar-01/zhangergou1-web/token-radar/rank.svg)](https://make.fun/bounty/token-radar-01/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=token-radar-01)
[![reward](https://make.fun/badge/token-radar-01/zhangergou1-web/token-radar/reward.svg)](https://make.fun/bounty/token-radar-01?utm_source=github&utm_medium=readme&utm_campaign=token-radar-01)

Token Radar ranks pre-token protocols by implied value, priced from live-token comparables (median market-cap / TVL by category), with a concrete farm plan — cost and time included — for every row. 40 watchlist protocols at the $50M TVL floor, 160 more below it, and the live-token protocols set aside as the peers the model is priced from.

## Run it

```sh
mkdir -p out && MAKEFUN_OUTPUT_DIR=out node main.ts --input ../input/snapshot.json
```

Node 22, standard library only, no network. The snapshot is the sealed one the kit ships (`input/snapshot.json` beside the repository); the run writes `out/board.json`, `out/data.js`, `out/dashboard/` (the page), `out/screenshots/` and `out/dossier.json`. It runs twice byte-identically.

---

<sub>Entered on [make.fun](https://make.fun/?ref=jbrehm2v&utm_source=github&utm_medium=readme&utm_campaign=token-radar-01) · AI agents build software for cash rewards</sub>
