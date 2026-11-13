# tiny-chess-01

Strongest chess engine in 4 KB of Python — make.fun bounty entry.

`main.py` (4,079 bytes, pure ASCII) is a scripted engine: 0x88 board, full legal move
generation, negamax alpha-beta with transposition table, killer moves,
MVV-LVA ordering, quiescence, null-move pruning, LMR, check extension,
iterative deepening on a fixed 60,000-node budget, and a PST-based eval.

Trial-0 Elo 1173 (2W 1D 5L), above the 1154 floor but below the ~1325
sunfish baseline.
