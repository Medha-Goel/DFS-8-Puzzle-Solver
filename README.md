
# Artificial Intelligence — Case Study
## 8-Puzzle Problem using Depth First Search (DFS)
Name:  Medha Goel

A responsive 8-puzzle visualizer implemented using HTML5, custom CSS3, and JavaScript ES6.

## Included components
- Home / case-study cover page with student name
- Initial and goal state inputs, with input validation
- Random solvable puzzle and example puzzle options
- DFS solver with visited-state checking
- Initial, goal, and current board visualization
- Run / pause / resume, next, previous, reset, and speed controls
- Solution path and search statistics
- Search-process view with generated successors, frontier (open list), explored (closed list), parent, depth, and event log
- Algorithm comparison reference page
- DFS information page with working principle, advantages, limitations, complexity, and pseudocode

## Run locally
1. Extract the project folder.
2. Open `index.html` in a modern browser.
3. Select **Puzzle Lab**, enter the initial and goal states, or generate a random solvable board.
4. Select **Find solution**, then use the playback controls to explore the path.

Use digits `0` through `8` exactly once in each state. `0` represents the blank space.

## Publish with GitHub Pages
1. Create a GitHub repository and upload `index.html`, `css/style.css`, `js/app.js`, and this README.
2. Open **Settings → Pages**.
3. Choose the main branch and root folder, then save.
4. Open the published URL after GitHub Pages finishes deploying.

## Notes
- DFS is the only search algorithm implemented in this individual project.
- Other algorithms on the comparison page are qualitative references, not executed benchmarks.
- The DFS implementation has a 40,000-expanded-node safety limit to avoid freezing the browser on difficult searches.

# DFS-8-Puzzle-Solver
An 8-puzzle solver using Depth-First Search (DFS) to find a path from an initial state to the goal state.

