# algorithm-lab
Interactive Pathfinding Algorithm Visualizer and Game
[README_algorithm_lab.md](https://github.com/user-attachments/files/35211396/README_algorithm_lab.md)
# Algorithm Lab — Interactive Pathfinding Game

**Live demo:** https://rashadnabiyev009.github.io/algorithm-lab/

## Overview
Algorithm Lab is a browser-based educational game and visualization tool for exploring pathfinding algorithms. Players navigate a maze and compare their route with algorithm-generated paths.

## Features
- Three maze sizes: 9×9, 13×13, and 17×17
- Keyboard (arrow keys/WASD) and on-screen movement controls
- Animated search visualization
- Side-by-side numerical comparison of BFS, DFS, and A*
- Metrics for player steps, shortest-path length, visited cells, and algorithm path length
- Responsive layout for different screen sizes

## Algorithms
| Algorithm | Core idea | Shortest path in this game's unweighted grid? |
| --- | --- | --- |
| Breadth-First Search (BFS) | Explore neighbors level by level | Yes |
| Depth-First Search (DFS) | Explore one branch deeply before backtracking | Not guaranteed |
| A* Search | Prioritize estimated total cost `f(n) = g(n) + h(n)` | Yes, using Manhattan distance here |

The grid uses four-directional movement. A* uses Manhattan distance as its heuristic.

## How to use
1. Open the [live game](https://rashadnabiyev009.github.io/algorithm-lab/).
2. Choose a difficulty and navigate the maze toward the star.
3. Select BFS, DFS, or A* and click **Alqoritmi göstər** to visualize a search.
4. Click **Müqayisə et** to compare the three algorithms on the current maze.
5. Generate a new maze and repeat to see how the results change.

## Tech stack
- HTML
- CSS
- Vanilla JavaScript
- GitHub Pages

## Research questions
- How do BFS, DFS, and A* differ in the number of visited cells?
- Why does DFS not always produce a shortest path?
- How does the Manhattan-distance heuristic guide A* on a grid?

## Next steps
- Add an English/Azerbaijani language switch
- Add charts and downloadable experiment results
- Add reproducible maze seeds and structured tests
- Document experiments and limitations

## Project note
This project was developed with AI assistance. The code, algorithms, and experimental observations should be reviewed and understood before being presented as independent academic work.
