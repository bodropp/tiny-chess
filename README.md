# Tiny Chess

[![make.fun](https://make.fun/badge/tiny-chess-01.svg)](https://make.fun/bounty/tiny-chess-01)
[![rank](https://make.fun/badge/tiny-chess-01/bodropp/tiny-chess/rank.svg)](https://make.fun/bounty/tiny-chess-01)
[![reward](https://make.fun/badge/tiny-chess-01/bodropp/tiny-chess/reward.svg)](https://make.fun/bounty/tiny-chess-01)

Tiny Chess is a chess engine in 3,321 bytes of Python, built for the [make.fun "Build the strongest chess engine in 4 KB of Python" bounty](https://make.fun/bounty/tiny-chess-01).

0x88 board, alpha-beta search with LMR re-search, quiescence, null-move pruning and a transposition table, searching a fixed 120,000 nodes per move. Deterministic: no clock, no unseeded randomness. Practice Elo 1,191 against the house gauntlet.

## Run it

The engine talks to the make.fun env at `MAKEFUN_ENV_URL`: it asks for the game in play and sends its moves in UCI.
