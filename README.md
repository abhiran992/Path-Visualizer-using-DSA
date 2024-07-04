# Path Visualizer using DSA

## Overview

Path Visualizer is an interactive web application designed to visualize various pathfinding algorithms in action. The application provides a visual representation of how these algorithms navigate through a grid to find the shortest path between two points. This project is an educational tool to help users understand the underlying mechanics of pathfinding algorithms and their efficiency.

## Features

- **Interactive Grid**: Create and modify grids with walls and weights to see how algorithms handle obstacles.
- **Multiple Algorithms**: Visualize popular pathfinding algorithms such as Dijkstra's Algorithm, A* Search, and Breadth-First Search (BFS).
- **Speed Control**: Adjust the speed of the visualization to see the algorithm in action step-by-step or at a faster pace.
- **Responsive Design**: Accessible on various devices, ensuring a consistent experience across different screen sizes.

## Algorithms Implemented

- **Dijkstra's Algorithm**: A classic algorithm for finding the shortest path in a graph with non-negative weights.
- **A* Search**: An extension of Dijkstra's Algorithm that uses heuristics to improve performance.
- **Breadth-First Search (BFS)**: A simple algorithm suitable for unweighted grids.
- **Depth-First Search (DFS)**: A less efficient algorithm for pathfinding but useful for educational purposes.

## Getting Started

### Prerequisites

- Node.js and npm installed on your machine.

### Installation

1. Clone the repository:
   ```sh
   git clone https://github.com/abhiran992/Path-Visualizer-using-DSA.git
   ```
2. Navigate to the project directory:
   ```sh
   cd Path-Visualizer-using-DSA
   ```
3. Install dependencies:
   ```sh
   npm install
   ```
4. Start the application:
   ```sh
   npm start
   ```

The application should now be running on `http://localhost:3000`.

## Usage

1. Open the application in your web browser.
2. Select the algorithm you want to visualize from the options.
3. Create walls by clicking on the grid cells.
4. (Optional) Add weights by right-clicking on the grid cells.
5. Set the start and end points by clicking on the respective buttons and then on the grid cells.
6. Click on the "Start Visualization" button to see the algorithm in action.
7. Adjust the speed using the slider to control the pace of the visualization.

## Contributing

Contributions are welcome! If you have suggestions for improvements or new features, feel free to open an issue or submit a pull request. Please ensure that your contributions align with the project's coding standards and practices.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Acknowledgements

- Inspired by various online pathfinding visualizer projects and educational tools.
- Thanks to all contributors and the open-source community for their valuable resources and support.

---

Feel free to modify this description according to any additional details or changes you might have for the project.
