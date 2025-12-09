# Project: Snake Game 
Subject: Chuyên đề 2

Final Project - Group: 21.44

Instructor: Dr. Nguyễn Văn Hiếu

## Member

| Name              | Student ID    |
| ----------------- | ------------- |
| Nguyễn Văn An   | **10620045**  |
| Phạm Thị Phương | **106210050** |
| Dương Thị Thảo Vi     | **10621259**  |

## Project Description 

### Snake Game – Pathfinding & AI Solvers

This project implements an intelligent version of the classic Snake Game where the snake automatically finds the safest and most optimal path to reach food on an 8×8 grid. The game integrates multiple algorithms—including Hamiltonian cycles, Greedy pathfinding, and DQN (Deep Q-Network)—to compare different solving strategies.

The main goal is to evaluate how deterministic algorithms (Hamilton, BFS-based shortest/longest paths, Greedy logic) and learning-based approaches (DQN) perform in navigating a confined grid without collisions while maximizing the amount of food consumed.

### The project includes:

- Hamilton Solver: Builds and follows a Hamiltonian cycle to guarantee safe traversal of the entire map. Supports shortcut optimization to reduce unnecessary movement.

- Greedy Solver: Uses shortest-path BFS and safety checks to move toward food if safe, otherwise follows a longest path to avoid self-collisions.

- Path Solver: Provides shortest (BFS) and heuristic longest path generation within the grid.

- DQN Solver: Trains a reinforcement learning agent to control the snake using DQN with Double DQN, Prioritized Replay, and Dueling Network extensions.

Comparative Analysis: Measures efficiency, survival length, and number of steps among different solvers.

This project demonstrates both algorithmic pathfinding techniques and deep reinforcement learning, providing a comprehensive study of AI behavior in constrained environments.
