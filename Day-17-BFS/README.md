# Day 17 - Python DSA Journey 🚀

## Topic: Breadth First Search (BFS) using Adjacency Matrix

### What I Learned
- Implemented Graph using an Adjacency Matrix.
- Added edges between vertices in an undirected graph.
- Learned how Breadth First Search (BFS) works.
- Used a Queue (`deque`) to traverse the graph level by level.
- Maintained a `visited` array to avoid visiting nodes multiple times.
- Understood the time and space complexity of BFS.



### Time Complexity
- BFS using Adjacency Matrix: **O(V²)**

### Space Complexity
- **O(V)**

  ## Graph Representation

```text
        0
       / \
      1---3
         / \
        4---5
        |
        6
       / \
      2   7
```
## BFS Traversal from Vertex 0

```text
Start: 0

Level 0:       0
              / \
Level 1:     1   3
                 /|\
Level 2:       4  5
               |
Level 3:       6
              / \
Level 4:     2   7

```
### Key Takeaway
BFS explores the graph level by level, visiting all neighboring nodes before moving to the next level. It is widely used for shortest path problems in unweighted graphs and graph traversal.

