# 🌳 Day 12 – Binary Search Tree (BST) Creation and Searching in Python

## 📚 Introduction

Today I learned about the **Binary Search Tree (BST)**, a special type of binary tree that allows efficient searching and insertion of data.

I implemented:

* BST Node Creation
* BST Insertion
* BST Searching
* Inorder Traversal

---

## 🔹 What is a Binary Search Tree (BST)?

A Binary Search Tree (BST) is a binary tree in which:

* All nodes in the left subtree have values smaller than the root node.
* All nodes in the right subtree have values greater than the root node.
* Both left and right subtrees are also BSTs.

### Example

```text
         20
       /    \
     15      30
    /  \    /  \
   12  18 25   40
                  \
                  50
```

---

## 🔹 BST Properties

1. Left Subtree < Root Node
2. Right Subtree > Root Node
3. No duplicate values (in this implementation)
4. Inorder traversal of a BST produces sorted output

---

## 🔹 Node Structure

Each node contains:

* Data (Value)
* Left Child Pointer
* Right Child Pointer

---

## 🔹 BST Insertion

### Algorithm

1. If the tree is empty, create a new node.
2. Compare the value with the current node.
3. If smaller, move to the left subtree.
4. If greater, move to the right subtree.
5. Repeat until the correct position is found.

### Example

Inserted values:

```text
20, 15, 30, 40, 12, 18, 25, 50
```

Resulting BST:

```text
         20
       /    \
     15      30
    /  \    /  \
   12  18 25   40
                  \
                  50
```

---

## 🔹 Searching in BST

Searching uses the BST property to reduce the number of comparisons.

### Algorithm

1. Start from the root node.
2. If the value matches, element is found.
3. If the value is smaller, move left.
4. If the value is greater, move right.
5. Continue until the value is found or the tree becomes empty.

### Example 1

Searching for:

```text
18
```

Path followed:

```text
20 → 15 → 18
```

Result:

```text
Element Found
```

### Example 2

Searching for:

```text
100
```

Path followed:

```text
20 → 30 → 40 → 50 → None
```

Result:

```text
Element Not Found
```


---

## 🔹 Time Complexity

| Operation | Average Case | Worst Case |
| --------- | ------------ | ---------- |
| Search    | O(log n)     | O(n)       |
| Insert    | O(log n)     | O(n)       |
| Traversal | O(n)         | O(n)       |

---

## 🔹 Advantages of BST

✅ Fast Searching

✅ Fast Insertion

✅ Maintains Sorted Data

✅ Easy to Perform Range Queries

✅ Dynamic Data Structure

---

## 🔹 Applications of BST

* Database Searching
* Dictionary Implementation
* Contact Management Systems
* File Organization
* Autocomplete Systems
* Symbol Tables in Compilers


