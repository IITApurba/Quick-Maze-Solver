# 🏆 Maze Solver (BFS)

## Overview
This is a **Maze Solver** written in **C++** that finds the **shortest path** from the **start ('S')** to the **finish ('F')**, avoiding obstacles ('#'). It uses **Breadth-First Search (BFS)** to ensure the shortest path is always found if it exists.

## Features
- **Finds the shortest path** in any given maze.
- **Prints the path length** and movement directions (L, R, U, D).
- **Handles any complex maze** and correctly identifies unreachable destinations.
- **Efficient BFS-based approach** with **O(n × m)** time complexity.

## How It Works
- Reads the maze from input.
- Uses **BFS** to explore all possible paths.
- Stores parent nodes to reconstruct the path.
- Outputs the **shortest path** and movement directions.

## Input Format
```
<n> <m>   # Dimensions of the maze
<maze grid>   # 'S' for start, 'F' for finish, '#' for walls, '.' for open paths
```
### Input:
```
6 6
S . # . . .
. . . . . .
# . # . # .
. . . # . .
# # # # . #
F . . . . .
```

## 📤 Output Format
- **Distance Matrix** showing the shortest distance to each cell.
- **Start and Finish positions.**
- **If the finish is reachable, the shortest path length and directions are displayed.**

### Output:
```
Path length: 15
Path direction: 

(0,0) -> (0,1) -> (1,1) -> (1,2) -> (1,3) -> (1,4) -> (1,5) -> (2,5) -> (3,5) -> (3,4) -> (4,4) -> (5,4) -> (5,3) -> (5,2) -> (5,1) -> (5,0)

RDRRRRDDLDDLLLL
```

## Running the Code
```bash
g++ maze_solver.cpp -o maze_solver
./maze_solver < input.txt
```

## Technologies Used
- **C++** for efficient execution.
- **Breadth-First Search (BFS)** for shortest path calculation.

## Why I Love This Code ❤️
This is one of the best pieces of code I have written because:
- It **always works**, no matter how complex the maze is
- It uses **pure logic, not random guessing**
- The **implementation is clean, structured, and easy to understand**
- It **feels like a real-world problem solver**, making it very satisfying to run

## Author
👨‍💻 **Apurba Kumar Show**

Feel free to **star** ⭐ this repository if you like it!

