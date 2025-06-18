# Route Optimizer - TSP Visualizer using Leaflet

An interactive web-based application that allows users to add locations on a live map and find the shortest possible route that visits each point once and returns to the starting point. This project visualizes the **Travelling Salesman Problem (TSP)** using two algorithms:

- **Nearest Neighbor (Fast Approximation)**
- **Exhaustive Search (Brute-force for small sets)**

Built using **HTML, CSS, JavaScript**, and **Leaflet.js** for real-time map interaction.

---

## Features

- 🗺️ Click to add locations directly on the map
- ⚡ Solve TSP using **Nearest Neighbor algorithm**
- 🧠 Optional exhaustive algorithm for exact results (recommended for ≤ 8 locations)
- 📏 View total optimized route distance
- 🔄 Reset map and start fresh
- 🌐 Works with **OpenStreetMap** tiles using **Leaflet.js**

---

## Algorithms Used

### 1. Nearest Neighbor (Greedy Approach)
- Starts from a point and repeatedly visits the nearest unvisited location.
- Fast but may not always produce the best path.

### 2. Exhaustive Search
- Tries all permutations and returns the best.
- Accurate but computationally heavy. Ideal for fewer cities (≤8).

---

## Technologies

- `Leaflet.js` – map rendering and interaction
- `HTML/CSS` – structure and styling
- `JavaScript` – logic and interactivity

---

## How to Use

1. **Open the app in browser** (or host via local server)
2. **Click on the map** to add waypoints
3. Select the algorithm:  
   - `Nearest` (Fast)  
   - `Exhaustive` (Exact, for small inputs)
4. Click **🧮 Optimize Route**
5. View the optimized path and total distance
6. Use **🔄 Reset** to start over

---

## Credits

- [Leaflet.js](https://leafletjs.com/) for interactive map integration
- [OpenStreetMap](https://www.openstreetmap.org/) for free and open tile data

---

## Author

Developed with ❤️ by [Abhishek A](https://github.com/Abhigowda02)

---

> If you like this project, consider giving it a ⭐️ on GitHub!

