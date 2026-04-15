# smart-route-optimization-system
Smart Route Optimization System using BFS, Dijkstra and Emergency Routing with Python GUI and Map Visualization
#  Smart Route Optimization System

A Python-based intelligent route optimization system that finds the best path between cities using graph algorithms like **BFS** and **Dijkstra**, with a special **Emergency Routing mechanism** considering traffic and priority.

---

##  Project Overview

This project demonstrates how different algorithms can be used to calculate and compare routes:

-  Normal Route (BFS)
-  Shortest Route (Dijkstra Algorithm)
-  Emergency Route (Modified Dijkstra with traffic & priority)

It also visualizes the routes on an interactive map using **Folium**.

---

## Features

- ✅ Multiple route comparison (Normal, Shortest, Emergency)
- ✅ Dynamic traffic simulation (realistic behavior)
- ✅ Priority-based emergency routing
- ✅ Interactive GUI using Tkinter
- ✅ Real-time map visualization using Folium
- ✅ Distance calculation for each route

---

##  Algorithms Used

### 1. Breadth-First Search (BFS)
- Finds a path with minimum number of nodes
- Used for Normal Route

### 2. Dijkstra Algorithm
- Finds shortest path based on distance
- Uses priority queue (heap)

### 3. Modified Dijkstra Algorithm
- Used for Emergency Route
- Considers:
  - Distance
  - Traffic
  - Priority

**Cost Function:**
