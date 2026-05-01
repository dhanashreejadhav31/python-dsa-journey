# 🔁 Circular Doubly Linked List (Python)

## 📌 Overview

 Implemented a **Circular Doubly Linked List (CDLL)** in Python with all major operations including insertion, deletion, and traversal.

A Circular Doubly Linked List is a type of linked list where:

* Each node contains `data`, `next`, and `prev` pointers
* The last node points back to the head (circular structure)
* Traversal can happen in both directions

---

## 🧠 Key Concept

In CDLL, we must always maintain:

```
last.next = head  
head.prev = last
```

This ensures the list remains **circular and doubly linked**.

---

## ⚙️ Operations Implemented

### ✅ Insertion

* Insert at beginning
* Insert at end
* Insert after a given node

### ❌ Deletion

* Delete head node
* Delete middle node
* Delete last node
* Handle single node case
* Handle value not found

### 🔍 Traversal

* Print all elements in circular order

---

## 🧩 Code Structure

* `Node` → Represents each element
* `CircularDLL` → Main class containing all operations

---

## 🚀 Sample Execution

```python
obj = CircularDLL()

obj.insertAtEnd(10)
obj.insertAtEnd(20)
obj.insertAtEnd(30)
obj.insertAtEnd(40)

obj.insertAtBeg(5)
obj.insertAfter(25, 20)

obj.deleteNode(40)

obj.printLL()
```

### 📤 Output

```
5 <--> 10 <--> 20 <--> 25 <--> 30 <--> (head)
```

---

## ⚠️ Edge Cases Handled

* Empty list
* Single node list
* Deleting head node
* Deleting last node
* Value not found

---

## 📈 What I Learned

* Importance of maintaining circular links
* Handling edge cases in linked lists
* Difference between linear and circular traversal
* Why updating both `prev` and `next` pointers is critical

---

## 💡 Key Takeaway

Unlike linear linked lists, Circular Linked Lists do not have `NULL`.
So traversal must stop manually using:

```
temp == head
```

