# 🗺️ MapMyJourney: GIS-Based Trip Planner for Tourists

## Overview
**MapMyJourney** is a high-performance, user-friendly GIS (Geographic Information System) application designed to help tourists plan trips with ease. This project was developed as part of the University of Toronto’s ECE297 course and integrates advanced algorithms, intuitive UI features, and real-time responsiveness to deliver a tailored travel planning experience. 

> ⚠️ _Note: Source code is not publicly available due to academic integrity policies._

---

## Key Features

### Trip Planning Tools
- **Popover Information**: Clickable map elements reveal details like name, address, and hours.
- **Itinerary Builder**: Add destinations with editable visit times and reorder them for efficiency.
- **Subway Visualization**: Toggle subway stations and lines for better transit planning.
  
### Responsiveness
- **Zoom-Level Optimization**: Varying detail levels based on zoom to reduce rendering time.
- **Fast Pathfinding**: Uses A* and Dijkstra’s algorithm for near-instant route calculations.

### Optimization Algorithms
- **Ant Colony Optimization**: Simulates pheromone trails to find efficient travel routes.
- **2-Opt Refinement**: Tweaks existing paths to improve quality-of-results (QoR).

<img width="800" height="540" alt="OP2 final" src="https://github.com/user-attachments/assets/5864ddb6-f2c6-4566-a313-339ac73db8c3" />

---

## Performance Benchmarks

| Algorithm | Test Cases | Total Time | Avg Time per Case |
|-----------|------------|------------|-------------------|
| A* (Toronto) | 505 | 5.20 s | ~0.01 s |
| A* (London)  | 130 | 4.10 s | ~0.03 s |

<img width="600" height="371" alt="_ improvement on QOR score compared to greedy solution" src="https://github.com/user-attachments/assets/99226718-6425-4aca-aa74-00a6183473ae" />

---

## Technologies Used
- **Languages**: C++
- **Libraries**: ezGL, StreetsDatabase API, OpenStreeMap (OSM) API
- **Algorithms**: A*, Dijkstra, Ant Colony Optimization, 2-Opt
- **GIS Concepts**: Spatial queries, zoom-level rendering, decluttered map design

---

## Visual Highlights

### Popover Feature  
<img width="700" height="540" alt="OP2 final(1)" src="https://github.com/user-attachments/assets/076494a2-4084-4a28-9fb7-06a67425a716" />

### Subway Lines Display  
<img width="700" height="540" alt="OP2 final(2)" src="https://github.com/user-attachments/assets/8f5ab5e7-3f29-4bae-869f-3aae312f304f" />

### Varrying Levels of Detail at Zoom Levels
<img width="700" height="540" alt="OP2 final(3)" src="https://github.com/user-attachments/assets/c81222d7-d797-4202-bf60-6d6ad4b007bb" />

### Visualization of A* and Dijkstra's algorithm
<img width="700" height="540" alt="OP2 final(4)" src="https://github.com/user-attachments/assets/242f26a1-6e2d-4757-976e-a0bdf19b1a6d" />

---

## Academic Context
This project was developed as part of the **ECE297: Software Design and Communication** course at the University of Toronto. It reflects collaborative work and is intended for educational and demonstration purposes only.

---

## License
This repository does not include source code due to academic integrity policies. All media and documentation are shared under the [Creative Commons Attribution-NonCommercial 4.0 International License](https://creativecommons.org/licenses/by-nc/4.0/).
