# Metro Route Finder

A C++ application that simulates a metro navigation system. The project allows users to manage metro stations and routes, visualize the network, and find the shortest path between stations using graph traversal algorithms. The graphical interface is built with **Raylib**, while **STL** is used for efficient data management.

---

## Features

- Add, edit, and manage metro stations
- Create and manage connections between stations
- Visualize the metro network
- Find the shortest path between two stations using **Breadth-First Search (BFS)**
- Explore routes using **Depth-First Search (DFS)**
- Save and load metro data from files
- Interactive graphical interface using Raylib

---

## Technologies Used

- C++
- STL (Vector, Map, Queue, Set)
- Raylib

---

## How It Works

1. Load the metro network from the provided data files.
2. View the metro map through the graphical interface.
3. Select source and destination stations.
4. The application calculates the shortest route using **Breadth-First Search (BFS)**.
5. Users can also explore the network using **Depth-First Search (DFS)**.
6. Station and route information can be updated and saved.

---

## Algorithms Used

### Breadth-First Search (BFS)
- Finds the shortest path in an unweighted graph.
- Uses a queue to visit stations level by level.
- Time Complexity: **O(V + E)**

### Depth-First Search (DFS)
- Explores one path completely before backtracking.
- Uses recursion (or a stack).
- Time Complexity: **O(V + E)**

---

## Learning Outcomes

This project helped us gain practical experience with:

- Graph data structures
- Graph traversal algorithms
- File handling in C++
- STL containers
- GUI development with Raylib
- Problem-solving and teamwork

---


## Future Improvements

- Weighted routes with travel distance/time
- Dijkstra's Algorithm for shortest path
- Search and filter stations
- Interactive zoom and pan
- Better UI and animations
- Real-time route updates

---

## Screenshots

Add screenshots of the application here.

<img width="1919" height="978" alt="image" src="https://github.com/user-attachments/assets/70fd1666-a4c7-4295-aeae-8813853e4991" />

<img width="1911" height="988" alt="image" src="https://github.com/user-attachments/assets/d865b1c4-e668-465e-91fc-b2eaf8f19d94" />


---

## License

This project was developed for educational purposes as part of a Computer Engineering course.
