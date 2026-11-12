# Graph Algorithms: BFS and Dijkstra's

![C++](https://img.shields.io/badge/C%2B%2B-blue) ![Course](https://img.shields.io/badge/CS315-Algorithm%20Design-lightgrey)

## Overview
A C++ project that models a map of Middle-earth as a graph and finds paths between locations using Breadth-First Search (BFS) and Dijkstra's algorithm. Built for my CS315 Algorithm Design class.

## Algorithms Implemented
### Breadth-First Search (BFS)
- Traverses the graph level by level using a queue.
- Computes the number of edges from a starting vertex to every reachable vertex.
- Tracks parent vertices to reconstruct shortest paths in unweighted graphs.
- Time complexity: O(V + E)

### Dijkstra's Algorithm
- Finds shortest paths from a starting vertex in a weighted graph.
- Uses edge weights to compute the minimum distance to every other vertex.
- Tracks parent vertices to reconstruct the shortest path.
- Time complexity: O((V + E) log V) with a priority queue

## Project Structure
- `Graph.cpp`: graph (adjacency list), BFS, and Dijkstra implementations
- `MiddleEarthVertices.txt`: the locations (vertices)
- `MiddleEarthEdges.txt`: the connections and weights (edges)

## How to Run
```bash
git clone https://github.com/lilBiggy101/graph-algorithms-class-project.git
cd graph-algorithms-class-project
g++ -g Graph.cpp -o Graph
./Graph
```
When prompted, enter a starting location, for example `Hobbiton`.

## Technologies
- C++
- Standard Template Library (STL)

## What I Learned
- How graphs are represented with adjacency lists.
- How BFS and Dijkstra's algorithm find the shortest path between a start and end node, and when to use each.
