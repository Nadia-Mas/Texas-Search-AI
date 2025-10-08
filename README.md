
AI-Informed Search
========================================
Author: Nadia - Fatemeh Sadat Masoumi  
University of Texas at San Antonio  
Course: CS 3793 – Artificial Intelligence  
Assignment 1 Project
----------------------------------------

📘 About This Repository
This repository contains a Python notebook developed for the Artificial Intelligence course at the University of Texas at San Antonio.  
It demonstrates how classical AI search algorithms can be applied to a real-world–inspired scenario: modeling the spread of a virus and optimizing vaccine distribution among Texas cities.

----------------------------------------
🎯 What You’ll Learn
- How to read data from CSV files and build a weighted graph.  
- How Uninformed Search (BFS) explores a graph to simulate virus spread.  
- How Informed Search (A*) finds the most efficient vaccine transport route.  
- How to visualize search results and compare strategies.

----------------------------------------
🧩 Project Description
1. **Data Loading** – Reads city coordinates and intercity distances from `cities.csv` and `distances.csv`.  
2. **Graph Construction** – Creates a 2D weighted graph linking all Texas cities.  
3. **Uninformed Search (BFS)** – Simulates the virus spreading from *Three Rivers* to all other cities.  
4. **Informed Search (A*)** – Finds an optimal path for vaccine transportation from *San Antonio* to *College Station* using straight-line distance as a heuristic.  
5. **Visualization (Optional)** – Overlays search paths on the Texas state map image (`texas-map-2.png`).

----------------------------------------
📂 Repository Contents
- `Copy of C5233_assignment1_trf553.ipynb` – main Python notebook.  
- `cities.csv` – list of cities with coordinates.  
- `distances.csv` – distances between connected cities.  
- `texas-map-2.png` – map overlay used for visualization.  
- `README.txt` – project overview (this file).

----------------------------------------
⚙️ Technologies Used
Python 3, CSV module, math, matplotlib, heapq, collections.deque  
(No prebuilt AI libraries used.)

----------------------------------------
📊 Example Outputs
- **BFS:** Sequence of infected cities and total travel distance.  
- **A\*:** Optimal vaccine route and total distance cost.  
- Optional plotted graph overlayed on the Texas map.

----------------------------------------
📜 License
This project is shared under the **MIT License** for educational and research purposes.  
You are welcome to explore, reference, or extend the code with proper attribution.

----------------------------------------
💡 Author’s Note
This project was created as part of my AI coursework to explore practical applications of graph-based search algorithms.  
If you find this useful for learning or demonstration —  

⭐ Give it a star (it helps me fight the algorithm!)  
🤖 May your BFS never get stuck in loops,  
🚀 and may your A* always find the shortest path!  
💾 If you break the code, don’t worry — that’s just “feature exploration.” 😉  
☕ Built with caffeine, curiosity, and a touch of chaos!

Stay awesome and keep coding! 💻✨

