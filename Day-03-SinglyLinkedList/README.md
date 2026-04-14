# 📌 Day 4: Singly Linked List (DSA)

## 🔍 Introduction
A **Singly Linked List** is a linear data structure where each element (node) contains:
- Data
- A reference (pointer) to the next node

Unlike arrays, elements are not stored in contiguous memory locations.

---

## 🧱 Structure of Node

- **Data** → Stores the value  
- **Next Pointer** → Points to the next node in the list  

---

## ⚙️ Operations Implemented

### 1️⃣ Traversal
- Visiting each node from head to end  
- Time Complexity: **O(n)**  

---

### 2️⃣ Insertion

#### ➤ At Beginning
- New node points to current head  
- Head updated to new node  
- Time Complexity: **O(1)**  

#### ➤ At End
- Traverse till last node  
- Last node points to new node  
- Time Complexity: **O(n)**  

#### ➤ At Middle (Position-Based Insertion)
- Traverse to the node just before the desired position  
- Adjust pointers:
  - New node → points to next node  
  - Previous node → points to new node  
- Time Complexity: **O(n)**  

---

### 3️⃣ Deletion

#### ➤ Delete from Beginning
- Move head to next node  
- Time Complexity: **O(1)**  

#### ➤ Delete from End
- Traverse to second last node  
- Remove last node  
- Time Complexity: **O(n)**  

#### ➤ Delete from Middle (Position-Based Deletion)
- Traverse to the node just before the target position  
- Change pointer to skip the node:
  - Previous node → points to next of target node  
- Effectively removes the node from the list  
- Time Complexity: **O(n)**  

---

## 📊 Time Complexity Summary

| Operation                   | Time Complexity |
|----------------------------|----------------|
| Traversal                  | O(n)           |
| Insertion (Beginning)      | O(1)           |
| Insertion (End)            | O(n)           |
| Insertion (Middle)         | O(n)           |
| Deletion (Beginning)       | O(1)           |
| Deletion (End)             | O(n)           |
| Deletion (Middle)          | O(n)           |

---

## 🧠 Key Learnings
- Linked Lists use **dynamic memory allocation**
- Efficient insertions and deletions compared to arrays
- Pointer manipulation is the core concept
- No direct access like arrays (no indexing)

---

## 💻 Implementation Details
- Language: **Python**
- Concepts Used:
  - Classes & Objects
  - References (Pointers)
  - DSA fundamentals

---

