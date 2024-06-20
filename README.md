Bread first search
Difference between a graph DS and Tree DS is that graph has a cycle, where are tree is a hierarchical structure. So graphs could have cycle(neighbours are connected).
Now to know if a Vertex is already visited, we take a Help of an Visited Array.
Approach is simple a] we take a Starting point and go to an immediate neighbour b] before going further we store all the neighbours of the current vertex c] As informed we take help of Visted array to track
To get a immediate neighbour, we use a Queue, we get neighbours and push them to Queue, this way we perform and get the sequence of BFS
Also called Level Order traversal
We use- Queue, while loop ==>> BFS
There is something called0 Disconnected components(disconnected graph), to do BFS for such graphs we should be having a dynamic Starting points.
O(V+E)
