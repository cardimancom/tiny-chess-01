# tiny-chess-01

Strongest chess engine in 4 KB of Python — make.fun bounty entry.

`main.py` (4,091 bytes, pure ASCII, multi-line bz2+base85 loader) is a scripted engine: 0x88 board, full legal move
generation, negamax alpha-beta with transposition table, killer moves,
MVV-LVA ordering, quiescence, null-move pruning, LMR, check extension,
iterative deepening on a fixed 80,000-node budget, and a PST-based eval.

Trial-0 Elo 1326 (3W 1D 4L) after the node-budget increase, at the ~1325
sunfish baseline.
