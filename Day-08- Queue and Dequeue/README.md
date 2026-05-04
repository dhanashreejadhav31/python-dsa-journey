# 📚 Queue and Deque 

## 🔹 1. Queue (FIFO)

### 📌 Definition

A **Queue** is a linear data structure that follows the **FIFO (First In First Out)** principle.
The element inserted first will be removed first.

---

### ⚙️ Basic Operations

| Operation | Description                   |
| --------- | ----------------------------- |
| Enqueue   | Insert element at the rear    |
| Dequeue   | Remove element from the front |
| Peek      | View front element            |
| isEmpty   | Check if queue is empty       |


---

### ⏱️ Time Complexity

| Operation | Time               |
| --------- | ------------------ |
| Enqueue   | O(1)               |
| Dequeue   | O(n) (using list)  |
| Dequeue   | O(1) (using deque) |

---

### 💡 Applications

* CPU Scheduling
* Printer Queue
* BFS (Breadth First Search)
* Handling requests in web servers

---

## 🔹 2. Deque (Double Ended Queue)

### 📌 Definition

A **Deque** is a linear data structure where insertion and deletion can be performed from **both ends** (front and rear).

---

### ⚙️ Basic Operations

| Operation     | Description       |
| ------------- | ----------------- |
| insertAtBeg   | Insert at front   |
| insertAtEnd   | Insert at rear    |
| deleteFromBeg | Delete from front |
| deleteAtEnd   | Delete from rear  |


---

### ⏱️ Time Complexity

| Operation    | Time                       |
| ------------ | -------------------------- |
| Insert Front | O(n) (list) / O(1) (deque) |
| Insert Rear  | O(1)                       |
| Delete Front | O(n) (list) / O(1) (deque) |
| Delete Rear  | O(1)                       |

---

### 💡 Applications

* Undo/Redo operations
* Palindrome checking
* Sliding window problems
* Task scheduling

---

## 🔥 Queue vs Deque

| Feature     | Queue           | Deque                    |
| ----------- | --------------- | ------------------------ |
| Access      | One end only    | Both ends                |
| Flexibility | Less            | More                     |
| Operations  | Enqueue/Dequeue | Insert/Delete both sides |

---

## 🚀 Key Takeaways

* Queue follows **FIFO**
* Deque is more flexible than Queue
* Python `list` is inefficient for front operations
* `collections.deque` provides **O(1)** operations


---
