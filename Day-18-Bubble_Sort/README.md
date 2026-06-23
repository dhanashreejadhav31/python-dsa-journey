# 🚀 Python DSA Journey - Day 18
# Bubble Sort Algorithm

## 📌 Overview
Today, I practiced the Bubble Sort algorithm in Python.

Bubble Sort is a simple comparison-based sorting algorithm that repeatedly compares adjacent elements and swaps them if they are in the wrong order. After each pass, the largest unsorted element "bubbles up" to its correct position.

---

## 📝 Algorithm

1. Traverse the array from index 0 to n-1.
2. Compare adjacent elements.
3. Swap them if the left element is greater than the right element.
4. After each pass, the largest element is placed at the end.
5. Repeat until the array is completely sorted.

---

## 🔍 Working Example

Initial Array:

```text
[4, 67, 32, 21, 10, 2, 55]
```

Pass 1:

```text
[4, 32, 21, 10, 2, 55, 67]
```

Pass 2:

```text
[4, 21, 10, 2, 32, 55, 67]
```

Pass 3:

```text
[4, 10, 2, 21, 32, 55, 67]
```

Pass 4:

```text
[4, 2, 10, 21, 32, 55, 67]
```

Pass 5:

```text
[2, 4, 10, 21, 32, 55, 67]
```

Final Sorted Array:

```text
[2, 4, 10, 21, 32, 55, 67]
```

---

## ⏱️ Time Complexity

| Case | Complexity |
|------|------------|
| Best Case | O(n²) |
| Average Case | O(n²) |
| Worst Case | O(n²) |


---

## ✅ Characteristics of Bubble Sort

- Comparison-based sorting algorithm
- Stable sorting algorithm
- In-place sorting
- Easy to understand and implement
- Not efficient for large datasets



