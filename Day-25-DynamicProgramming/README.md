# 📚 Day 25 – Dynamic Programming (DP)


Today, I explored **Dynamic Programming (DP)**—a powerful algorithmic technique used to solve optimization problems efficiently by avoiding repeated computations.

---

# 🧠 What is Dynamic Programming?

Dynamic Programming is a problem-solving technique used to solve complex problems by breaking them down into smaller, simpler subproblems.

Instead of solving the same subproblem multiple times, Dynamic Programming stores the result of each solved subproblem and reuses it whenever needed. This significantly improves efficiency.

Dynamic Programming is applicable when a problem satisfies two important properties:

- ✅ **Optimal Substructure**
- ✅ **Overlapping Subproblems**

---

# 🔑 Optimal Substructure

A problem has **Optimal Substructure** if its optimal solution can be constructed from the optimal solutions of its smaller subproblems.

### Example

Suppose you want to find the maximum profit in the 0/1 Knapsack problem.

To decide whether to include an item, you compare:

- Profit obtained by including the item
- Profit obtained by excluding the item

The best answer depends on the best solutions of these smaller problems.

---

# 🔁 Overlapping Subproblems

A problem has **Overlapping Subproblems** when the same subproblems are solved repeatedly during computation.

Without Dynamic Programming, the algorithm performs duplicate calculations, making it inefficient.

Dynamic Programming eliminates this repetition by storing previously computed results.

---

# 📝 Memoization (Top-Down Approach)

**Memoization** is a Dynamic Programming technique where the problem is solved using **recursion**.

Instead of solving every recursive call repeatedly, the solution of each subproblem is stored in a memory structure (such as an array or dictionary).

Whenever the same subproblem is encountered again, the stored answer is returned immediately instead of recomputing it.

### Characteristics

- Uses recursion
- Stores previously computed results
- Avoids repeated calculations
- Solves only the subproblems that are actually needed

### Advantages

- Easy to convert from recursive solutions
- Efficient for problems where not all subproblems are required

### Disadvantages

- Uses recursive function calls
- Extra memory is required for recursion (call stack)
- May cause stack overflow for very deep recursion

---

# 📊 Tabulation (Bottom-Up Approach)

**Tabulation** is another Dynamic Programming technique where the solution is built iteratively from the smallest subproblems to the final answer.

Instead of recursion, a table (usually an array or matrix) is filled step by step.

Each entry depends on values that have already been computed.

### Characteristics

- Uses iteration
- No recursion
- Starts from base cases
- Builds toward the final solution

### Advantages

- Faster than recursion due to no function call overhead
- No risk of stack overflow
- Often preferred in coding interviews

### Disadvantages

- May compute subproblems that are never actually needed
- Sometimes uses more memory than memoization

---

# 🔄 Memoization vs Tabulation

| Feature | Memoization | Tabulation |
|---------|-------------|------------|
| Approach | Top-Down | Bottom-Up |
| Uses Recursion | ✅ Yes | ❌ No |
| Uses Iteration | ❌ No | ✅ Yes |
| Stores Results | ✅ Yes | ✅ Yes |
| Solves Only Needed Subproblems | ✅ Yes | ❌ Not Always |
| Risk of Stack Overflow | ✅ Yes | ❌ No |
| Generally Faster | Slightly slower due to recursion | Usually faster |



