# 🟢 Python DSA Journey – Greedy Algorithm

## 📌 Topic
**Greedy Algorithm**

## 🎯 Problem
Find the **maximum** and **minimum** possible sum of absolute differences by pairing elements in an array.

---

## 🧠 What is a Greedy Algorithm?

A **Greedy Algorithm** is an algorithmic approach that makes the **best possible choice at each step** with the hope of finding the overall optimal solution.

Instead of considering all possible combinations, it chooses the option that seems best at the current moment.

### Characteristics of Greedy Algorithms
- Makes a locally optimal choice at every step.
- Does not reconsider previous decisions.
- Works efficiently for problems with the **Greedy Choice Property** and **Optimal Substructure**.
- Usually provides faster solutions than exhaustive approaches.

---

## 💡 Problem Overview

Given an array of integers:

- Calculate the **maximum possible sum** of absolute differences by pairing the smallest elements with the largest elements.
- Calculate the **minimum possible sum** of absolute differences by pairing adjacent elements after sorting.

The key idea is that **sorting the array** makes it easier to create the most effective pairs.

---

## 🚀 Greedy Strategy

### Maximum Difference

To maximize the total difference:

- Sort the array in ascending order.
- Pair the smallest element with the largest element.
- Pair the second smallest with the second largest.
- Continue until all elements are paired.

This creates the largest possible difference for each pair.

---

### Minimum Difference

To minimize the total difference:

- Sort the array.
- Pair adjacent elements.
- Since adjacent elements are closest in value, their absolute difference is minimum.

This produces the smallest overall sum of differences.

---

## 📈 Algorithm Steps

1. Sort the array.
2. Create pairs for the maximum difference using the smallest and largest elements.
3. Create pairs for the minimum difference using adjacent elements.
4. Calculate the absolute difference for every pair.
5. Find the total sum for both cases.

---

## ⏱️ Time Complexity

| Operation | Complexity |
|-----------|------------|
| Sorting | **O(n log n)** |
| Pair Traversal | **O(n)** |
| **Overall** | **O(n log n)** |

---

## 💾 Space Complexity

**O(1)** (excluding the space used internally by the sorting algorithm)



---

## 🔑 Key Takeaways

- Greedy algorithms make the best decision available at each step.
- Sorting often simplifies greedy-based solutions.
- Pairing the smallest with the largest maximizes differences.
- Pairing adjacent elements minimizes differences.
- Greedy algorithms are efficient but work only when the problem satisfies the greedy-choice property.
