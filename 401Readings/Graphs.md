# Graphs

A graph is a non-linear data structure that can be looked at as a collection of vertices (or nodes) potentially connected by line segments named edges.

Here is some common terminology used when working with Graphs:

1. *Vertex* - A vertex, also called a "node", is a data object that can have zero or more adjacent vertices.
2. *Edge* - An edge is a connection between two nodes.
3. *Neighbor* - The neighbors of a node are its adjacent nodes, i.e., are connected via an edge.
4. *Degree* - The degree of a vertex is the number of edges connected to that vertex.

Graphs can be _directed_ and _undirected_, directed is like a doubly linked list. Undirected is like a singly linked list.
Graphs can be _complete_, _connected_, and _disconnected_, complete means all nodes are connected to all others, connected means every node has at least one connection (like a tree) and disconnected means not every node is connected to another

traversing a graph with breadth first traversal uses a Queue to visit all children at a given level, the depth first traversal uses a Stack to visit all children of a given subtree.

the breadth first traversal of a graph is like that of a tree, with the exception that graphs can have cycles. Traversing a graph that has cycles will result in an infinite loop….this is bad. To prevent such behavior, we need to have some way to keep track of whether a vertex has been “visited” before. Upon each visit, we’ll add the previously-unvisited vertex to a visited set, so we know not to visit it again as traversal continues.
