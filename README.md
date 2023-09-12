# Zewail City Pathfinding AI

## Overview

This project utilizes various searching algorithms to find optimal paths within Zewail City. The goal is to help users navigate from their current location to a specified destination, utilizing interior paths within buildings. Additionally, a graphical user interface (GUI) is provided to enhance user interaction and visualization of the paths.

## Features

- **Multiple Searching Algorithms:** The project incorporates a range of searching algorithms such as Dijkstra's Algorithm, A* Algorithm, and Depth-First Search (DFS) to find paths within Zewail City.

- **Interior Pathfinding:** The algorithms are designed to consider interior paths within buildings, providing users with comprehensive navigation options.

- **Graphical User Interface (GUI):** The GUI offers an intuitive way for users to input their current location and desired destination, as well as visualize the generated paths.

- **User-Friendly Output:** The project outputs clear and easy-to-understand directions for users, making it straightforward to follow the recommended path.

## Usage

1. **Installation:**

   - Clone the repository to your local machine:
     ```
      https://github.com/Amir-Seif-Mohamed/AI_project_based-Uni_campus_map.git
     ```
   - Navigate to the project directory.

2. **Dependencies:**

   - Inserted within the notebook for easier installation. 

3. **Execution:**

   - Run the main script:
     ```
     project.ipynb
     ```

4. **GUI Interaction:**

   - The GUI will prompt you to input your current location and desired destination.

   - After providing the necessary information, click on the "Find Path" button.

   - The GUI will display the recommended path, and you can follow the directions provided.

## Algorithms

The project incorporates various search algorithms into three main categories:

### Uninformed Search

- **BFS (Breadth-First Search):**
  - Time needed to find solution: 0.195 sec
  - Complete: Yes
  - Optimal: No (it will be optimum if the step cost is one)
  - Number of expanded nodes: 95 Nodes

- **DFS (Depth-First Search):**
  - Time needed to find solution: 0.704 sec
  - Complete: Yes
  - Optimal: No
  - Number of expanded nodes: 78 Nodes

- **IDS (Iterative Deepening Search):**
  - Time needed to find solution: 0.841 sec
  - Complete: Yes
  - Optimal: No (it will be optimum if the step cost is one)
  - Number of expanded nodes: 196 Nodes

### Informed Search

- **A* (A Star):**
  - Time needed to find solution: 0.1 sec
  - Complete: Yes
  - Optimal: Yes
  - Number of expanded nodes: 38 Nodes

- **Greedy:**
  - Time needed to find solution: 0.06 sec
  - Complete: Yes
  - Optimal: No
  - Number of expanded nodes: 38 Nodes

### Local Search

- **Hill Climbing:**
  - Time needed to find solution: It stucks
  - Complete: No
  - Optimal: No
  - Number of expanded nodes: It stucks

- **Simulated Annealing:**
  - Time needed to find solution: It takes too many times to get the solution and it may get stuck
  - Complete: No
  - Optimal: No
  - Number of expanded nodes: It takes too many times to get the solution and it may get stuck

## Contribution

If you'd like to contribute to the project, please follow these steps:

1. Fork the repository.
2. Create a new branch for your feature or bug fix.
3. Make your changes and commit them with descriptive messages.
4. Push your changes to your forked repository.
5. Open a pull request with a clear title and detailed description.
