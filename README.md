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
Explores two fundamental searching techniques used to locate a target element in an array. The practical explains how each algorithm works, demonstrates their implementation in Python, and compares their efficiency, requirements, and use cases.

- Linear Search — checks each element sequentially from the beginning of the array until the target is found or all elements have been examined. It can be applied to both sorted and unsorted arrays.
- Binary Search — repeatedly compares the target with the middle element and eliminates half of the remaining search space after each comparison. It is more efficient than linear search but requires the array to be sorted.

The practical also covers successful and unsuccessful searches, explains the difference between iterative and recursive approaches, and compares their time complexities. Linear search has a worst-case time complexity of **O(n)**, while binary search has a worst-case time complexity of **O(log n)** and a space complexity of **O(1)** when implemented iteratively.

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
