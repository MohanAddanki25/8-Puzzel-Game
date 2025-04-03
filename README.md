The 8-puzzle is a classic sliding tile puzzle where the goal is to rearrange tiles from a random initial state to the goal state using the fewest moves. 
This program implements A* search with three different heuristic functions to solve the puzzle efficiently.

**Heuristics Implemented**
1. Misplaced Tiles: Counts the number of tiles not in their goal position
2. Manhattan Distance: Sums the horizontal and vertical distances of each tile from its goal position
3. Linear Conflict: Manhattan distance plus additional penalties when two tiles are in their correct row/column but reversed
