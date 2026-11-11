# Graph Algorithms: BFS and Dijkstra's

## Overview
This was a project for my CS315 Algorithm Design class and had me implement graph traversal and shortest-path algorithms in C++. It explores how graphs can represent connections between locations and the implementation of BFS and Dijkstra's algorithm to construct shortest paths from any 2 nodes.

## Algorithms Implemented

### Breadth-First Search (BFS)
- Traverses a graph level by level using a queue.
- Calculates the number of edges from a starting vertex to reachable vertices.
- Tracks parent vertices to reconstruct shortest paths in unweighted graphs.

### Dijkstra's Algorithm
- Finds shortest paths from a starting vertex in a weighted graph.
- Uses edge weights to calculate the minimum distance to other vertices.
- Tracks parent vertices to reconstruct shortest paths.

## How To Run
1. Copy Repo
2. Compile with g++ -g Graph.cpp -o Graph
3. Run with ./Graph and type Hobbiton when prompted

## Technologies
- C++
- Standard Template Library (STL)

## Purpose
This project taught me about how graphs are represented through Adjacency lists and how graphing algorithms can be used to find the shortest path from a starting node to an ending node. 
