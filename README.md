# Othello-Pygame

This is an Othello Game with heuristic search MiniMax Algorithm with Alpha-beta pruning.

# Othello 

Othello is a board game derived from the original game Reversi. The game board itself is an 8x8 square grid. Each player has 32 disk-like black and white pieces- each playing choosing a color to start the game. The initial starting position includes 4 pieces in the middle 4 squares of the board- 2 black and 2 white pieces

# Minimax Algorithm

This algorithm is considered the heart for many algorithms which have been used for a SumZero game. In 1928, the theorem of this algorithm was published by John von Neumann[TL59]. Neumann is cited as saying ”There could be no theory of games .. without that theorem .. I thought there was nothing worth publishing until the Minimax Theorem was proved[Cas96].” Minimax algorithm is for fully observable and deterministic games. These games include classic board games such as chess, checkers, tic tac toe, and go.

# Alpha-beta Pruning 

Minimax algorithm searches entire nodes, even if it is obvious that some nodes of the tree can be pruned ignored. There is an optimization which improves MiniMax algorithm is called AlphaBeta-Pruning algorithm. Instead of searching entire tree, Alpha-Beta-Pruning is a technique for pruning nodes that are not needed to evaluate the possible moves. This will save a lot of searching time which allow increasing search depth. In 1961, McCarthy proposed Alpha-Beta during the Dartmouth Conference[Kot04].

# References

//http://www.cs.columbia.edu/~sedwards/classes/2020/4995-fall/reports/Othello.pdf
//http://cs.indstate.edu/~aaljubran/paper.pdf
//https://github.com/IcePear-Jzx/Othello-AI
