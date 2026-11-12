# tiny-chess-01

Strongest chess engine in 4 KB of Python — make.fun bounty entry.

`main.py` (4,013 bytes) is a scripted engine: 0x88 board, full legal move
generation, negamax alpha-beta with transposition table, killer moves,
MVV-LVA ordering, quiescence, null-move pruning, LMR, check extension,
iterative deepening on a fixed 60,000-node budget, and a PST-based eval.

Practice mean Elo 1418 (trials 1464 / 1464 / 1326), above the 1154 floor
and the ~1325 sunfish baseline.

Note: `main.py` is latin-1 encoded (`# coding: latin-1`); commit it
byte-preservingly, do not re-save as UTF-8.
