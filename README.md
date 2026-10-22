# Maze-Generation-Using-DFS
Implementation of a Maze Generation Algorithm using Depth-First Search (DFS) in Python. The program generates a random maze by exploring unvisited cells and removing walls between them using a stack-based DFS approach. DS Case Study – SPPU Second Year Computer Engineering.

# Maze Generation using DFS

## Aim
To generate a random maze using Depth-First Search (DFS).

## Description
This project generates a maze using a stack-based DFS
algorithm. Each cell is treated as a node, and walls
between adjacent cells are removed to create paths.
Backtracking is used when no unvisited neighbor exists.

## Data Structures Used
- Stack
- Set
- 2D List

## Algorithm
1. Create a grid in which all walls are present.
2. Start from the first cell and mark it visited.
3. Select a random unvisited neighboring cell.
4. Remove the wall between the current and next cell.
5. Push the next cell onto the stack.
6. If no unvisited neighbor exists, backtrack.
7. Continue until all cells are visited.
8. Display the generated maze.

## Time Complexity
O(R × C), where R is the number of rows
and C is the number of columns.

## Space Complexity
O(R × C), for the maze grid, visited set,
and DFS stack.

## Conclusion
The project demonstrates how DFS and backtracking
can be used to generate a random maze efficiently.

