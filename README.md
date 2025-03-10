# 8-Puzzle-Solver
Overview
This Python program solves the 8-puzzle problem using the A* search algorithm with the Manhattan Distance heuristic. 
The 8-puzzle is a sliding puzzle consisting of a 3x3 grid with numbered tiles and a blank space, where the goal is to arrange the tiles into a specific order.

Features
-> Implements the A* search algorithm
-> Uses the Manhattan Distance heuristic for efficient searching
-> Tracks and outputs the sequence of moves to reach the goal state
-> Allows user input for both the initial and goal states

How It Works
-> The program takes a user-defined 3x3 start state and goal state.
-> It uses the A* algorithm to explore possible moves.
-> The Manhattan Distance heuristic helps prioritize the best moves.
-> The solution path (sequence of moves) is printed if a solution exists.

How to Run
-> Save the script as 8_puzzle_solver.py.
-> Open a terminal or command prompt and navigate to the script location.
-> Run the script using:
-> python 8_puzzle_solver.pyEnter the start state and goal state as prompted.
