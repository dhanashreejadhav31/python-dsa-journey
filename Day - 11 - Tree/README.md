# Day 11 - Trees and Tree Traversal in Python 🌳

## What is a Tree?

A Tree is a hierarchical, non-linear data structure made up of nodes connected by edges.

### Tree Terminology

- **Root Node** – The topmost node of a tree.
- **Parent Node** – A node that has children.
- **Child Node** – A node connected below a parent node.
- **Leaf Node** – A node with no children.
- **Edge** – Connection between two nodes.
- **Subtree** – A tree formed by a node and its descendants.

---

## Types of Trees 

### 1. Binary Tree

A tree in which each node can have at most two children.

Example:

        A
       / \
      B   C

### 2. Binary Search Tree (BST)

A binary tree where:

- Left subtree contains smaller values.
- Right subtree contains larger values.

Example:

        10
       /  \
      5    15

### 3. Strict Binary Tree

A tree where every non-leaf node has exactly two children.

Example:

        A
       / \
      B   C
     / \
    D   E

### 4. Complete Binary Tree

All levels are completely filled except possibly the last level, which is filled from left to right.

Example:

        1
       / \
      2   3
     / \  /
    4  5 6

### 5. Skew Binary Tree

A tree where every node has only one child.

#### Left Skewed

        1
       /
      2
     /
    3

#### Right Skewed

    1
     \
      2
       \
        3

### 6. Extended Binary Tree

A binary tree where NULL children are replaced with special external nodes.

Example:

        A
       / \
      B   C
     / \ / \
    N  N N  N

(N represents external nodes/Dummy Nodes)

---

## Tree Traversal

Traversal means visiting every node of a tree exactly once.

### Preorder Traversal (Root → Left → Right)

Algorithm:
1. Visit Root
2. Traverse Left Subtree
3. Traverse Right Subtree

### Inorder Traversal (Left → Root → Right)

Algorithm:
1. Traverse Left Subtree
2. Visit Root
3. Traverse Right Subtree

### Postorder Traversal (Left → Right → Root)

Algorithm:
1. Traverse Left Subtree
2. Traverse Right Subtree
3. Visit Root

DSA Journey 🚀
**Day 11 Completed**
