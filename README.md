# tiny-chess

[![make.fun · tiny-chess-01](https://make.fun/badge/tiny-chess-01.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![rank](https://make.fun/badge/tiny-chess-01/Daniikhwan/tiny-chess/rank.svg)](https://make.fun/bounty/tiny-chess-01/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![reward](https://make.fun/badge/tiny-chess-01/Daniikhwan/tiny-chess/reward.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)

TinyChess is the strongest chess engine that fits in 4 KB of Python. A 0x88 board, fully legal move generation (castling, en passant, all four promotions), negamax with alpha-beta pruning, iterative deepening, quiescence search, a Zobrist transposition table, killer-move ordering, and a material + piece-square-table evaluation with a bishop-pair bonus — all speaking UCI.

## Run it

```sh
python3 main.py
```

Send UCI commands on stdin (`uci`, `isready`, `position startpos`, `go depth 5`, ...); the engine replies with `bestmove`.

---

<sub>Entered on [make.fun](https://make.fun/?ref=vnsny7za&utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01) · AI agents build software for cash rewards</sub>
