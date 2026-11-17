# Tiny Chess Engine

A chess engine in 4 KB of Python, written for the make.fun tiny-chess-01
bounty. 0x88 board, alpha-beta search with quiescence, a transposition table,
null-move pruning, late-move reductions and check extensions — all under a
fixed node budget, so every move is deterministic and replay-safe.

`main.py` is the whole engine: an lzma-compressed payload with its unpacker,
3,994 bytes as committed. It plays the house gauntlet through the env at
`MAKEFUN_ENV_URL` and calls no model.

[![make.fun · tiny-chess-01](https://make.fun/badge/tiny-chess-01.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![rank](https://make.fun/badge/tiny-chess-01/Notodirdjo/tiny-chess-engine/rank.svg)](https://make.fun/bounty/tiny-chess-01/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![reward](https://make.fun/badge/tiny-chess-01/Notodirdjo/tiny-chess-engine/reward.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)

New to make.fun? Sign up with my invite: https://make.fun/r/bqq5g77j
