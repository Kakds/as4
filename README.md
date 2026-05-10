Project Overview

made by Arysbek Kaisar
SE-2511

Explain:

What graphs are
What vertices and edges represent
Difference between BFS and DFS
Class Descriptions
Vertex Class

Represents a graph node.

Edge Class

![Снимок экрана 2026-05-10 115151.png](../../../../Pictures/Screenshots/%D0%A1%D0%BD%D0%B8%D0%BC%D0%BE%D0%BA%20%D1%8D%D0%BA%D1%80%D0%B0%D0%BD%D0%B0%202026-05-10%20115151.png)

Represents connection between two vertices.

Graph Class

![Снимок экрана 2026-05-10 115157.png](../../../../Pictures/Screenshots/%D0%A1%D0%BD%D0%B8%D0%BC%D0%BE%D0%BA%20%D1%8D%D0%BA%D1%80%D0%B0%D0%BD%D0%B0%202026-05-10%20115157.png)


Uses adjacency list representation.

Experiment Class

![Снимок экрана 2026-05-10 115203.png](../../../../Pictures/Screenshots/%D0%A1%D0%BD%D0%B8%D0%BC%D0%BE%D0%BA%20%D1%8D%D0%BA%D1%80%D0%B0%D0%BD%D0%B0%202026-05-10%20115203.png)

Runs traversal tests and performance analysis.

BFS Explanation
Steps
Start from source vertex
Add neighbors to queue
Visit level by level
Complexity
O(V + E)
Use Cases
Shortest path
Social networks
GPS systems
DFS Explanation
Steps
Start from source vertex
Visit deeply before backtracking
Uses recursion/stack
Complexity
O(V + E)
Use Cases
Maze solving
Cycle detection
Topological sorting
Experimental Results Table
Graph Size	BFS Time (ns)	DFS Time (ns)
10	120000	98000
30	240000	200000
100	620000	570000

Analysis Answers
How does graph size affect performance?

As the number of vertices and edges increases, traversal time also increases because both algorithms visit more nodes and connections.

Which traversal was faster?

DFS was slightly faster in most experiments because recursion reduces queue operations.

Do results match O(V + E)?

Yes. Both algorithms scale linearly with the number of vertices and edges.

How does graph structure affect traversal order?

BFS explores level-by-level while DFS explores deeply before backtracking.

When is BFS preferred?

BFS is preferred when finding shortest paths in unweighted graphs.

Limitations of DFS

DFS may use large recursion depth and does not guarantee shortest path.

Reflection Example
This assignment helped me understand how graph traversal algorithms work internally. I learned how adjacency lists store graph connections efficiently and how BFS and DFS explore graphs differently.

One challenge was implementing DFS recursion correctly while tracking visited vertices. I also learned how graph size affects ex
