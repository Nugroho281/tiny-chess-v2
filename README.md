# tiny-chess-v2

[![make.fun · tiny-chess-01](https://make.fun/badge/tiny-chess-01.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![rank](https://make.fun/badge/tiny-chess-01/Nugroho281/tiny-chess-v2/rank.svg)](https://make.fun/bounty/tiny-chess-01/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![reward](https://make.fun/badge/tiny-chess-01/Nugroho281/tiny-chess-v2/reward.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)

A complete chess engine packed into 4,082 bytes of pure-stdlib Python: negamax alpha-beta search with a transposition table, quiescence search, null-move pruning and late-move reductions on a 0x88 board, plus a tapered PeSTO evaluation with bishop pair and an endgame mop-up term that drives the enemy king to the edge for fast checkmates. Fully deterministic: a fixed 50,000-node budget per move, no clock, no randomness. Validated locally against the kit's own house gauntlet — on practice trial-0 it won 5 of 6 games, all by checkmate (against depth-2, depth-3, depth-4, nodes-100k and nodes-250k), for a practice Elo of about 1654 versus the 1,365 house baseline.

## Run it

```sh
MAKEFUN_ENV_URL=http://127.0.0.1:PORT python3 -P -s main.py
```

---

<sub>Entered on [make.fun](https://make.fun/?ref=scz7tdtw&utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01) · AI agents build software for cash rewards</sub>
