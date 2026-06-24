# Day 19 - DSA with Python 🚀

## Topic: Selection Sort

Today, I practiced the **Selection Sort** algorithm in Python.

### 📌 What is Selection Sort?

Selection Sort is a simple sorting algorithm that repeatedly finds the smallest element from the unsorted part of the array and places it at the beginning.

---

## 🔹 Algorithm

1. Start from the first element.
2. Find the minimum element in the remaining unsorted array.
3. Swap it with the current element.
4. Move to the next position.
5. Repeat until the array is sorted.

---

## 🔹 Example

### Input

```python
[24, 56, 10, 38, 40, 7, 90]
```

### Output

```python
[7, 10, 24, 38, 40, 56, 90]
```

---

## 🔹 Dry Run

### Pass 1
```
[24, 56, 10, 38, 40, 7, 90]
Minimum = 7
After swap:
[7, 56, 10, 38, 40, 24, 90]
```

### Pass 2
```
Minimum = 10
[7, 10, 56, 38, 40, 24, 90]
```

### Pass 3
```
Minimum = 24
[7, 10, 24, 38, 40, 56, 90]
```

Remaining elements are already in correct order.

---

## 🔹 Time Complexity

| Case | Complexity |
|------|------------|
| Best Case | O(n²) |
| Average Case | O(n²) |
| Worst Case | O(n²) |

---

## 🔹 Space Complexity

```text
O(1)
```

Selection Sort is an **in-place sorting algorithm** because it does not require extra memory.

---

## 🔹 Key Points

- Comparison-based sorting algorithm.
- In-place sorting algorithm.
- Easy to understand and implement.
- Performs minimum number of swaps.
- Not suitable for large datasets due to O(n²) time complexity.

