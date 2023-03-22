# Breadth-First-Search
Breadth-first search (BFS) is an algorithm for searching a tree data structure for a node that satisfies a given property. 

It starts at the tree root and explores all nodes at the present depth prior to moving on to the nodes at the next depth level. Extra memory, usually a queue, is needed to keep track of the child nodes that were encountered but not yet explored.

Follow the below method to implement BFS traversal.

1. Declare a queue and insert the starting vertex.
2. Initialize a visited array and mark the starting vertex as visited.
3. Follow the below process till the queue becomes empty:
4. Remove the first vertex of the queue.
5. Mark that vertex as visited.
6. Insert all the unvisited neighbors of the vertex into the queue.
