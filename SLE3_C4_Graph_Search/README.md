
# SLE-3: Architectural Design of a Graph Search System

## Project Background
This project continues the SLE-2 empirical performance analysis of
Breadth-First Search (BFS) and Depth-First Search (DFS).

## Problem Setup
- Graph: 15 nodes (0 to 14)
- Start node: 0
- Goal node: 6
- Algorithms: BFS and DFS

## Python Program
- `graph_search.py` contains the graph, BFS, DFS, and timing functions.

## Architecture Diagrams
- `diagrams/01_context.puml` - C4 Level 1: Context
- `diagrams/02_container.puml` - C4 Level 2: Containers / logical modules
- `diagrams/03_component.puml` - C4 Level 3: BFS components
- `diagrams/04_code_overview.puml` - C4 Level 4: Code overview

## How to Run
Run the Python program from the project folder:

```bash
python graph_search.py
```

## Main Observation
For this graph and traversal order, both algorithms find the path
[0, 2, 6]. BFS expands 7 nodes and DFS expands 13 nodes.

Execution time varies between runs and computers.
