# Graph Coloring Simulator

A web-based Graph Coloring Simulator implemented using HTML, CSS, and JavaScript. It demonstrates graph coloring using Greedy and Backtracking algorithms.

## Features

- Add, move, and delete vertices and edges.
- Create custom graphs or load predefined examples.
- Implement Greedy and Backtracking algorithms.
- Visualize graph coloring step by step.
- Display the number of vertices, edges, and colors used.

## Algorithms

### Greedy Algorithm
Assigns the smallest available color to each vertex such that no two adjacent vertices have the same color. It does not always produce the minimum number of colors.

### Backtracking Algorithm
Uses recursion to find a valid coloring by trying different color assignments. It determines the minimum number of colors required.

## Technologies Used

- HTML
- CSS
- JavaScript
- HTML5 Canvas API

## How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/bhavjsh/graph-color-stimulator.git
   ```
2. Open `graph-coloring-simulator.html` in a web browser.

## Usage

1. Add vertices and connect them using edges, or select a predefined graph.
2. Select Greedy or Backtracking from the algorithm dropdown.
3. Click **Color Graph** to apply the selected algorithm.
4. Use **Next Step** to view the coloring process.
5. Click **Clear Graph** to reset the graph.
