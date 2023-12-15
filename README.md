
# Dijkstra's Algorithm Visualization

This repository contains a Python implementation of Dijkstra's algorithm for pathfinding, visualized using the Pygame library. Dijkstra's algorithm is a popular algorithm for finding the shortest path between nodes in a graph.

## Dijkstra's Algorithm Overview
Dijkstra's algorithm is a graph search algorithm that finds the shortest path between two nodes in a weighted graph. It operates by iteratively expanding the frontier of explored nodes from the initial node, choosing the node with the lowest tentative distance from the start at each step. The algorithm maintains a priority queue to efficiently select the next node to explore.

## Implementation Details
The implementation uses a 2D grid of "boxes," each representing a node in the graph. The grid is initially set up with a specified number of columns and rows. Users can interact with the visualization by adding walls and setting a target destination using mouse controls.

### Box Class: 
Represents a node in the graph. Each box has attributes such as its position, whether it is a start node, a wall, the target destination, and its state in the algorithm (visited, queued). Boxes also store information about their neighbors.

### Grid Initialization: 
A grid is created with boxes, and each box is linked to its neighboring boxes.

### User Interaction: 
Users can draw walls on the grid and set a target destination using mouse controls.

### Algorithm Execution: 
The main loop of the program allows the user to start the algorithm by pressing a key. The algorithm then explores the graph using Dijkstra's algorithm until it reaches the target destination or determines that no solution exists.

### Visualization: 
The Pygame library is used to visualize the algorithm's execution. Boxes change color to represent different states (queued, visited, path), and the visualization updates in real-time as the algorithm progresses.

## How to Use
Run the program.
Draw walls on the grid by clicking and dragging the left mouse button.
Set the target destination by right-clicking on a box.
Press any key to start Dijkstra's algorithm.
Observe the visualization of the algorithm's execution.

## Dependencies
Python 3.x
Pygame library
Install Pygame using the following terminal command:

*pip install pygame*

## Notes

The program uses a simple Tkinter messagebox to notify the user if there is no solution.
Close the Pygame window to exit the program.

# *Feel free to explore, modify, and use this code for educational purposes or as a starting point for more complex pathfinding algorithms. If you have any questions or suggestions, please feel free to contact me. *

*Made by Dan Dragos*
