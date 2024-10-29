# Graph-Traversing-Visualizer
This project is a GUI-based visualizer for Graph Traversal Algorithms, built with Python and Tkinter. It offers an interactive demonstration of Breadth-First Search (BFS) and Depth-First Search (DFS) algorithms by animating the traversal of nodes in a simple graph.

# Features
1. Graph Structure: Pre-defined set of nodes and edges with connections.
2. BFS Traversal: Shows nodes turning red as they are visited in a breadth-first manner.
3. DFS Traversal: Shows nodes turning blue as they are visited in a depth-first manner.
4. Interactive Controls: Buttons to start BFS or DFS traversal.
5. Status Indicator: Displays the current traversal status ("Not Visited", "Visited").

# Project Structure
1. GraphTraversal Class: Manages the canvas, graph structure, and traversal algorithms.
2. basic_set_up(): Initializes buttons, labels, and sets up the canvas.
3. make_vertex(): Creates vertices (nodes) and connections (edges) on the canvas.
4. make_connector_up(), make_connector_down(): Creates lines representing edges between nodes.
5. collector_connector(): Collects node data to be used during traversal.
6. binary_search(): Efficiently finds nodes in the graph.
7. bfs_traversing(): Implements BFS traversal animation.
8. dfs_traversing(): Implements DFS traversal animation.
