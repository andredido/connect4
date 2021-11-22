# CONNECT FOUR
### Andrea Di Domenico s287639
Computational Intelligence A.A. 2021/2022 - Politecnico di Torino
## Lookup table
The initial optimal move is always dropping a token in the middle column. If the first token is dropped in the middle column then the second optimal move is still the center. So on for the fourth and the fifth. But a relative small lookup table would slow down the algorithm. 

## Heuristics
Center columns are in average better moves, it is therefore reasonable to explore them first.

## Hash Table
I store previously expanded nodes. I save in a dictionary only the nodes that takes me in a final state.

## BITMAP
Reference: https://github.com/denkspuren/BitboardC4/blob/master/BitboardDesign.md