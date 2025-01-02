# Priority-Queue# Priority Queue in MIPS Assembly with Dijkstra's Algorithm  

This repository contains an implementation of a **Priority Queue** using **MIPS Assembly Language**, with an application of **Dijkstra's Shortest Path Algorithm** to demonstrate its functionality.  

---

## Features  

### Priority Queue Implementation  
- Supports insertion and deletion of elements based on their priority.  
- Implements a min-heap structure for efficient operations.  

### Dijkstra's Algorithm  
- Calculates the shortest path from a source node to all other nodes in a graph.  
- Utilizes the priority queue for efficiently selecting the node with the smallest distance.  

---

## Requirements  

- **MIPS Simulator**:  
  The code is tested on the [MARS MIPS Simulator](http://courses.missouristate.edu/KenVollmar/mars/).  
- **Basic Knowledge**:  
  Understanding of assembly language and graph algorithms is recommended.  

---

## How It Works  
### Priority Queue  
The priority queue is implemented using a **min-heap** structure.  
It supports two main operations:  
-  **Insert**: Adds an element with a given priority.  
- **Extract Min**: Removes and returns the element with the smallest priority.  

### Dijkstra's Algorithm  
- **Input**: A weighted graph represented as an adjacency matrix and a source node.  
- **Process**:  
  - Uses the priority queue to keep track of nodes with the smallest tentative distances.  
  - Iteratively updates distances to calculate the shortest paths.  
