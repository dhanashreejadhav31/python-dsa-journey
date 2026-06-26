# 📘 Day 20 – Merge Sort in Python | DSA Journey 🚀

Today I learned and implemented **Merge Sort**, one of the most efficient sorting algorithms that follows the **Divide and Conquer** approach.

---

# 📌 What is Merge Sort?

Merge Sort is a sorting algorithm that:

- Divides the array into smaller halves.
- Recursively sorts each half.
- Merges the sorted halves into one sorted array.

Instead of sorting the array directly, it repeatedly breaks the array into smaller pieces until each piece contains only one element.

Since a single element is already sorted, it then starts merging them in sorted order.

---

# 🧠 Divide and Conquer Strategy

Merge Sort works in three steps:

### 1️⃣ Divide
Split the array into two halves.

```
[38, 27, 43, 3, 9, 82, 10]

            |
      ----------------
      |              |
 [38,27,43,3]    [9,82,10]
```

---

### 2️⃣ Conquer

Recursively divide until every subarray contains only one element.

```
[38,27,43,3]

↓

[38,27] [43,3]

↓

[38] [27] [43] [3]
```

Single elements are considered sorted.

---

### 3️⃣ Merge

Merge the smaller sorted arrays into larger sorted arrays.

```
[38] [27]
↓

[27,38]

[43] [3]
↓

[3,43]

↓

[3,27,38,43]
```

Repeat until the entire array becomes sorted.

---

# 📊 Visual Representation

Original Array

```
[2, 34, 45, 57, 9, 15, 25]
```

## Step 1: Divide

```
                [2 34 45 57 9 15 25]

              /                     \
      [2 34 45 57]               [9 15 25]

      /          \              /        \
 [2 34]      [45 57]         [9 15]     [25]

 /    \       /    \         /    \
[2] [34]   [45] [57]      [9] [15]
```

---

## Step 2: Merge

```
[2] + [34]
↓

[2 34]

[45] + [57]
↓

[45 57]

[9] + [15]
↓

[9 15]
```

---

## Step 3: Merge Larger Arrays

```
[2 34] + [45 57]
↓

[2 34 45 57]

[9 15] + [25]
↓

[9 15 25]
```

---

## Final Merge

```
[2 34 45 57]
+
[9 15 25]

↓

[2 9 15 25 34 45 57]
```

---

# 💻 Algorithm

```
MergeSort(array)

If array has more than one element

    Find middle

    Divide into left half

    Divide into right half

    MergeSort(left)

    MergeSort(right)

    Merge(left,right)
```

---


# ⏱ Time Complexity

| Case | Complexity |
|------|------------|
| Best | O(n log n) |
| Average | O(n log n) |
| Worst | O(n log n) |

Unlike Bubble Sort or Selection Sort, Merge Sort performs consistently in all cases.

---

# 💾 Space Complexity

```
O(n)
```

Extra memory is required for temporary arrays.

---

# ✅ Advantages

- Very efficient for large datasets.
- Stable sorting algorithm.
- Predictable performance.
- Uses Divide and Conquer.
- Performs well even in the worst case.

---

# ❌ Disadvantages

- Requires extra memory.
- Not an in-place sorting algorithm.
- Recursive calls increase stack usage.
- Slightly slower for very small arrays compared to simpler algorithms.

---

# 📌 Applications

- Sorting large datasets
- External sorting (files on disk)
- Linked list sorting
- Database systems
- Parallel processing
- Big data applications



