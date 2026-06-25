# Day 20: Insertion Sort in Python 🚀

## 📖 Introduction
Today, I practiced **Insertion Sort**, a simple comparison-based sorting algorithm that builds the final sorted array one element at a time.

The algorithm works similarly to how we arrange playing cards in our hands by inserting each card into its correct position.

---

## 🛠️ Algorithm

1. Start from the second element of the array.
2. Store the current element as `key`.
3. Compare `key` with elements before it.
4. Shift larger elements one position to the right.
5. Insert `key` into its correct position.
6. Repeat until the array is sorted.

---

## 🔍 Example Dry Run

Initial Array:

```text
[34, 45, 20, 56, 24, 38]
```

After inserting 20:

```text
[20, 34, 45, 56, 24, 38]
```

After inserting 24:

```text
[20, 24, 34, 45, 56, 38]
```

After inserting 38:

```text
[20, 24, 34, 38, 45, 56]
```

---

## 📊 Complexity Analysis

| Case | Time Complexity |
|------|----------------|
| Best Case | O(n) |
| Average Case | O(n²) |
| Worst Case | O(n²) |

### Space Complexity

```text
O(1)
```

---

## ✅ Advantages

- Easy to implement.
- In-place sorting algorithm.
- Stable sorting algorithm.
- Efficient for small datasets.
- Performs well on nearly sorted arrays.

---

## ❌ Disadvantages

- Not suitable for large datasets.
- Slower than advanced sorting algorithms for large inputs.

---

## 🎯 Conclusion

Insertion Sort is a simple and intuitive sorting algorithm that is useful for small or nearly sorted datasets. Understanding it helps build a strong foundation for learning more advanced sorting algorithms.

