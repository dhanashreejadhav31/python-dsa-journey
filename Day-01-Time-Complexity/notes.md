# Day 01 – Time Complexity

Today I learned the concept of Time Complexity in Data Structures and Algorithms.

## What is Time Complexity?

Time Complexity measures the time taken by an algorithm as the input size increases.

It helps us compare algorithms and choose the most efficient one.

Types of Asymptotic Notation

1. Big O (O)
Represents the worst-case complexity of an algorithm.

2. Omega (Ω)
Represents the best-case complexity.

3. Theta (Θ)
Represents the average-case or tight bound complexity.

## Big-O Notation

Big-O notation represents the worst-case performance of an algorithm.

Common complexities:

O(1) – Constant Time  
Ex- arr = [10, 20, 30, 40]
    print(arr[0])   # accessing first element
    
O(log n) – Logarithmic Time  
Ex- n = 16
    while n > 1:
      print(n)
      n = n // 2
      
O(n) – Linear Time  
Ex- print("Hello")

O(n log n) – Linearithmic Time  

O(n²) – Quadratic Time 
Ex-arr = [1, 2, 3]
    for i in arr:
      for j in arr:
          print(i, j)
          
O(2ⁿ) – Exponential Time

## Examples

## Examples of Time Complexities

O(1) – Accessing array element  
O(n) – Traversing array  
O(n²) – Nested loops  
O(log n) – Binary search  
O(n log n) – Efficient sorting algorithms

## Key Takeaways

- Time complexity helps analyze algorithm efficiency.
- Big-O notation represents worst-case performance.
- Efficient algorithms have lower time complexity.

## Next Goal

Start learning Arrays and solve basic problems.
