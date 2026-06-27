# Quick Sort in Python 🚀

## 📌 Topic
Quick Sort is a **Divide and Conquer** sorting algorithm that selects a **pivot** element, partitions the array around the pivot, and recursively sorts the left and right subarrays.

---

# 🧠 Algorithm

1. Choose a pivot element.
2. Rearrange the array so that:
   - Elements smaller than the pivot are placed on the left.
   - Elements greater than the pivot are placed on the right.
3. Place the pivot in its correct sorted position.
4. Recursively apply Quick Sort to the left subarray.
5. Recursively apply Quick Sort to the right subarray.
6. Stop when the subarray has one or zero elements.

---

# 🔍 Example

### Input

```python
[24, 20, 45, 32, 10, 3]
```

### First Partition

Pivot = **24**

```
[24, 20, 45, 32, 10, 3]
```

After partition:

```
[10, 20, 3, 24, 32, 45]
```

Pivot **24** is now in its correct position.

Recursively sort:

```
Left : [10, 20, 3]
Right: [32, 45]
```

Final Sorted Array:

```
[3, 10, 20, 24, 32, 45]
```

---

# 🌳 Recursion Tree

```
                [24,20,45,32,10,3]
                     pivot=24
                  /               \
          [10,20,3]            [32,45]
          pivot=10             pivot=32
          /      \               /   \
       [3]      [20]          []    [45]
```

---

# ⏱ Time Complexity

| Case | Complexity |
|------|------------|
| Best Case | O(n log n) |
| Average Case | O(n log n) |
| Worst Case | O(n²) |

---

# 💾 Space Complexity

- Average Case: **O(log n)**
- Worst Case: **O(n)** (due to recursion stack)

---

# ✅ Advantages

- Very fast in practice.
- In-place sorting (no extra array needed).
- Average time complexity is **O(n log n)**.
- Widely used in real-world applications.
- Efficient for large datasets.

---

# ❌ Disadvantages

- Worst-case time complexity is **O(n²)**.
- Recursive implementation may lead to stack overflow for very large inputs.
- Not a stable sorting algorithm.

---

# 📚 Real-World Applications

- Database sorting operations.
- Search engine indexing.
- Large-scale data processing.
- E-commerce product sorting.
- File system organization.
- Data analytics.
- Competitive programming.

---

# 🎯 Key Takeaways

- Quick Sort follows the **Divide and Conquer** strategy.
- A pivot divides the array into smaller subarrays.
- The pivot reaches its final sorted position after partitioning.
- Recursive calls sort the left and right partitions.
- Average performance is **O(n log n)**.
- Poor pivot selection can degrade performance to **O(n²)**.
- Random or median pivot selection helps improve performance.



