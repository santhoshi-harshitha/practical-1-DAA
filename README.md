# Design and Analysis of Algorithms Practicals

This repository contains Python implementations of fundamental algorithms and problem-solving techniques covered in the Design and Analysis of Algorithms (DAA) practicals.

## Practicals Summary

### Practical 1: Sorting Algorithms
Implements and compares common sorting techniques:

- Bubble Sort — repeatedly swaps adjacent elements that are out of order.
- Selection Sort — repeatedly selects the smallest element from the unsorted portion.
- Insertion Sort — builds the sorted array one element at a time.
- Merge Sort — divides the array into smaller parts and merges them in sorted order.
- Quick Sort — partitions the array around a pivot and recursively sorts the partitions.

The practical also discusses the time complexities of each sorting algorithm.

### Practical 2: Linear Search and Binary Search
Demonstrates two methods for finding an element in an array:

- Linear Search — checks each element sequentially and works with unsorted data.
- Binary Search — repeatedly divides a sorted array in half to locate the target efficiently.

### Practical 3: Heap Sort
Implements Heap Sort using a max heap. The algorithm builds a heap and repeatedly extracts the largest element to produce a sorted array. Its theoretical time complexity is **O(n log n)**.

### Practical 4: Factorial Using Iteration and Recursion
Calculates the factorial of a number using two approaches:

- Iteration — uses a loop to multiply the numbers from 1 to `n`.
- Recursion — repeatedly calls the function with a smaller value until reaching the base case.

### Practical 5: 0/1 Knapsack Using Dynamic Programming
Solves the 0/1 Knapsack problem using dynamic programming. It calculates the maximum value that can fit within a given capacity and identifies the items selected for the optimal solution.

### Practical 6: Matrix Chain Multiplication
Determines the most efficient order for multiplying a sequence of matrices. Dynamic programming is used to minimize the total number of scalar multiplications and display the optimal parenthesization.

### Practical 7: Coin Change Using Dynamic Programming
Finds the minimum number of coins required to make a specified amount from a given set of denominations. The dynamic programming solution returns `-1` when the amount cannot be formed.

### Practical 8: Graph Traversal
Implements two fundamental graph traversal algorithms:

- Breadth-First Search (BFS) — explores vertices level by level using a queue.
- Depth-First Search (DFS) — explores as far as possible along each branch using recursion.

## Files

- `DAA_practical01.ipynb` — Sorting algorithms
- `DAA_practical_02.ipynb` — Linear and binary search
- `DAA_practical03.ipynb` — Heap Sort
- `DAA_practical04.ipynb` — Iterative and recursive factorial
- `DAA_practical05.ipynb` — 0/1 Knapsack
- `DAA_practical06.ipynb` — Matrix Chain Multiplication
- `DAA_practical07.ipynb` — Coin Change
- `DAA_practical08.ipynb` — BFS and DFS graph traversal
