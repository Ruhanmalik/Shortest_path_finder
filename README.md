# Shortest_path_finder

# Visual Maze Pathfinder

A Python-based maze solving application that uses breadth-first search (BFS) to find the shortest path from start to end, with a visual interface showing the path-finding process in real-time.

## Features

- Visual representation of maze solving using curses library
- Real-time pathfinding visualization with color coding
- Breadth-first search implementation for optimal path finding
- Customizable maze layout
- Color-coded display (Blue for maze, Red for path)

## Prerequisites

- Python 3.x
- curses library (built into Python for Unix/Linux/macOS; for Windows, use `windows-curses`)

## Installation

1. Clone the repository:
```bash
git clone https://github.com/yourusername/visual-maze-pathfinder.git
cd visual-maze-pathfinder
```

2. If you're on Windows, install the curses library:
```bash
pip install windows-curses
```

The maze will be displayed with:
- 'O' representing the start point
- 'X' representing the end point
- '#' representing walls
- ' ' (space) representing traversable paths

The program will visualize the pathfinding process in real-time, showing:
- Blue characters for the maze structure
- Red 'X' markers for the discovered path

## How It Works

1. The program uses a breadth-first search algorithm to find the shortest path
2. It explores neighboring cells in four directions (up, down, left, right)
3. Visited cells are tracked to avoid cycles
4. The path is visualized in real-time as the algorithm explores
5. Once the end point is reached, the complete path is displayed
