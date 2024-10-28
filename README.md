# Reversi Game

## Introduction and Rules

Challenge a high-speed, advanced computer AI in Reversi! This classic board game combines strategy and tactics, with players competing to control the board by flipping their opponent's tiles. Here’s a quick overview of the game rules:

- **Board Setup**: The game starts on an 8x8 board with four tiles placed in the center in an alternating black and white pattern. Moves must remain within columns "a" through "h."

- **Making a Move**: To make a valid move, place a tile so that in at least one of the eight directions (N, NE, E, SE, S, SW, W, NW), there is a line of one or more of your opponent’s tiles ending in one of your own. All opponent tiles along this path will be "flipped" to your color.

- **Move Continuity**: If a player has no valid moves, the other player continues until the first player has a legal move available. The game ends when the board is full or neither player has valid moves left. The winner is the player with the highest tile count at the end or the player who avoids invalid moves.

## Interesting Facts About the Computer AI

The computer AI in this Reversi game is designed to provide a challenging and dynamic experience, using sophisticated algorithms and heuristics:

- **Advanced Search Algorithm**: Initially, the AI used a simple Minimax search algorithm but was later optimized with Alpha-Beta Pruning, allowing it to make decisions faster and more efficiently.

- **Heuristic-based Decision Making**: The AI uses a weighted board as part of its heuristic approach, assigning values to each board position to prioritize strategic moves. Corners, which are crucial in Reversi, are given a high value of 20, while other board positions range from -4 to 4. Experiment with these weights to see if you can further improve the AI's strategy!

- **Depth of Strategy**: The AI looks five moves ahead (using a 5-layer depth in its algorithm) to determine the optimal move. For an even tougher challenge, increase the AI’s "ply" depth by modifying the "ply" variable on lines 306 and 337—this will allow it to think even further ahead!

Test your skills against this intelligent and adaptable AI, and see if you can outmaneuver its advanced strategies!





<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
