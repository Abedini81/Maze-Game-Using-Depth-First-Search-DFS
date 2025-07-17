Maze Solver - Depth-First Search (DFS)
A Python implementation of a maze-solving algorithm using Depth-First Search (DFS) with backtracking. The goal is to find a path from a start point (3) to an end point (2) in a 2D grid.

How It Works
The maze is a 2D list where:

1 = Wall

0 = Open path

3 = Start point

2 = End point

DFS is used to explore all possible paths.

If a dead end is reached, it backtracks and tries a different path.

The solution path is returned as a list of (row, col) coordinates.

⚙️ Key Functions
find_start_end(maze): Finds the start and end coordinates.

is_valid_move(maze, visited, row, col): Checks bounds, walkability, and visited status.

solve_maze(maze, start, end): Runs DFS and returns the path from start to end.

Usage
Requirements
Python 3.x

Run python maze.py
Example Output
[(7, 4), (6, 4), (5, 4), (5, 3), (5, 2), (4, 2), (4, 1), (3, 1), (2, 1), (1, 1), (0, 1), (0, 2), (0, 3), (0, 4), (0, 5)]
📁 Customize
To test with a different maze, modify the maze variable inside maze.py.
