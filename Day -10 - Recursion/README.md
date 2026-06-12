# Day 10: Recursion in Python

## 📖 What is Recursion?

Recursion is a programming technique where a function calls itself to solve a smaller version of the same problem.

A recursive function must have:

1. **Base Case** – Stops the recursion.
2. **Recursive Case** – Function calls itself with a smaller input.

---

## 🔹 Structure of a Recursive Function

```python
def recursive_function():
    if base_case:
        return result
    return recursive_function(smaller_problem)
```


## 🔹 Advantages of Recursion

- Makes code shorter and cleaner.
- Useful for problems that can be divided into smaller subproblems.
- Commonly used in Trees and Graphs.
- Helps solve divide-and-conquer problems.

---

## 🔹 Disadvantages of Recursion

- Uses extra memory due to the call stack.
- Can be slower than iteration.
- Too many recursive calls may cause a stack overflow.

---

## 🔹 Difference Between Recursion and Iteration

| Recursion | Iteration |
|------------|------------|
| Function calls itself | Uses loops |
| Easier to write for some problems | Usually faster |
| Uses call stack memory | Uses less memory |
| May cause stack overflow | No stack overflow issue |

---

## 🔹 Key Takeaways

✅ A recursive function must have a base case.  
✅ Recursion solves a problem by breaking it into smaller subproblems.  
✅ Every recursive call should move toward the base case.  
✅ Recursion is widely used in DSA, especially Trees and Graphs.  
✅ Factorial, Fibonacci, and Palindrome are common beginner recursion problems.
