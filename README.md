# A*_Path_Planning_Algorithm
Implementation of the A* path planning algorithm for finding the shortest path in a grid with obstacles. Supports configurable start/goal points, visualizations, and cost +heuristics. Ideal for robotics, games, and AI applications.
# A* Path Planning Algorithm 🚀

This project implements the **A\*** (A-Star) pathfinding algorithm on a **9x10 grid**. It finds the shortest path between a start and goal cell while avoiding obstacles. The algorithm uses a combination of actual cost (`g`) and heuristic cost (`h`) to determine the best path.

---

## 📌 Features

- 9x10 grid-based environment
- Customizable start, goal, and obstacle positions
- Efficient pathfinding with A* algorithm
- Clear path visualization using `matplotlib`
- Modular, easy-to-read Python code

---

## 📂 Project Structure

- `A__Path_Planning_Algorithm.ipynb`: Main implementation in a Jupyter Notebook
- `Cell` class for each node in the grid
- Heuristic function (Euclidean or Manhattan)
- Visualization of open/closed lists and final path

---

## 🧠 How A* Works

A* uses:
- `g(n)`: Actual cost from start to node `n`
- `h(n)`: Estimated cost from node `n` to goal
- `f(n) = g(n) + h(n)`: Total estimated cost

It explores the most promising paths first and guarantees the shortest path if the heuristic is admissible.

---

## 🖼️ Example Visualization

Path planning example on a 9x10 grid:

- `S` = Start
- `G` = Goal
- `#` = Obstacle
- `.` = Path

```plaintext
S . . # . . . . . .
. # . # . . . . . .
. # . . . # . . . .
. . # # . # . . . .
. . . . . # . . . G

Requirements
Python 3.x
matplotlib

pip install matplotlib

How to Run
1. Open the notebook in Jupyter:

jupyter notebook A__Path_Planning_Algorithm.ipynb

2. Run all cells to see the A* pathfinding in action.
Applications

Mobile robot navigation
AI pathfinding in games
Maze-solving bots
Autonomous vehicle route planning

Author - Atharva Pathak
