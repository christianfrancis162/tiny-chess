# tiny-chess

[![make.fun · tiny-chess-01](https://make.fun/badge/tiny-chess-01.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![rank](https://make.fun/badge/tiny-chess-01/christianfrancis162/tiny-chess/rank.svg)](https://make.fun/bounty/tiny-chess-01/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![reward](https://make.fun/badge/tiny-chess-01/christianfrancis162/tiny-chess/reward.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)

A tiny chess engine for make.fun's "Build the strongest chess engine in 4 KB of Python" ($500). `main.py` is a compressed 0x88 alpha-beta engine: transposition table, killer moves, null-move pruning, quiescence, iterative deepening on a fixed node budget (never a clock). Python 3.13 stdlib only, deterministic. It talks to the env at `$MAKEFUN_ENV_URL` and plays in UCI.

Practice Elo 1,581 mean over three trials (1,545 / 1,654 / 1,545; 12 wins, 4 draws, 2 losses).
