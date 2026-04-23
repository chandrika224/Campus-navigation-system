This project is a grid-based campus navigation system that helps users find the shortest path between a source and destination within a college campus. The campus is modeled as a matrix (2D grid) where each cell represents a walkable path or an obstacle.

The system applies pathfinding algorithms such as Breadth-First Search and Dijkstra's Algorithm to compute the optimal route efficiently.

Features:
Find shortest path between two points
Supports obstacles (blocked paths)
Grid-based (matrix) representation
Efficient pathfinding using BFS and Dijkstra
Clean layered architecture design
Easy to extend for real-world navigation systems

How It Works:
User provides start and destination
System validates the input
Grid (matrix) is processed
Pathfinding algorithm is executed
Shortest path is reconstructed and displayed

Architecture:

The system follows a Layered Architecture:

Presentation Layer (UI)
Controller Layer
Service Layer (Pathfinding Logic)
Data Layer (Matrix/Grid)

Tech Stack:
Java / Spring Boot (optional)
Data Structures & Algorithms
Matrix (2D Array)
BFS & Dijkstra

Use Cases:
Campus navigation
Indoor navigation systems
Game pathfinding
Robot movement simulation

Future Enhancements:
Add weighted paths (traffic/crowd simulation)
Interactive UI visualization
Real campus map integration
Advanced algorithms like A*

Key Learning Outcomes:
Matrix traversal
Graph-based pathfinding
System design using layered architecture
Real-world problem modeling
