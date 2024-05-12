## A* Pathfinding Algorithm Implementation in Python ##
This repository contains a Python implementation of the A* pathfinding algorithm applied to a 2D square grid. The algorithm finds the shortest path from a start point to a goal point while avoiding obstacles.

- Usage:
1. Ensure you have Python installed on your system.
2. Clone this repository to your local machine.
3. Navigate to the directory containing the code.
4. Run the script astar_pathfinding.py.

- Code Overview:
astar_pathfinding.py: Contains the implementation of the A* algorithm.
README.md: Provides information about the code and how to use it.

- Dependencies:
1. numpy
2. heapq
3. matplotlib

- Input:
1. grid: A 20x20 numpy array representing the grid with obstacles marked as 1s and free spaces as 0s.
2. start: Tuple representing the starting point (row, column).
3. goal: Tuple representing the goal point (row, column).

- Output:
The script outputs the shortest path from the start point to the goal point in the form of a graph/image (using Matplotlib). The script displays the grid with the start and goal points marked, along with the shortest path plotted in black.

- Acknowledgments:
Inspiration for this implementation comes from various sources in the field of pathfinding algorithms.
