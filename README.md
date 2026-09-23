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
Explores two fundamental searching techniques used to locate a target element in an array. The practical explains how each algorithm works, demonstrates their implementation in Python, and compares their performance.

- Linear Search — checks each element sequentially from the beginning of the array until the target is found or all elements have been examined. It can be applied to both sorted and unsorted arrays.
- Binary Search — repeatedly compares the target with the middle element and eliminates half of the remaining search space after each comparison. It is more efficient than linear search but requires the array to be sorted.

The practical also covers successful and unsuccessful searches, explains the difference between iterative and recursive approaches, and compares their time complexities. Linear search has a worst-case complexity of **O(n)**, while binary search has a worst-case complexity of **O(log n)**.

### Practical 3: Heap Sort
Implements Heap Sort using a max heap. The algorithm first converts the input array into a max heap, where every parent node is greater than or equal to its children. It then repeatedly exchanges the root, which contains the largest element, with the last unsorted element and restores the heap property.

This practical demonstrates how a binary heap can be represented using an array and explains the heapify operation used to maintain the structure. Heap Sort is an in-place comparison-based sorting algorithm that does not require additional arrays for merging. It has a best-case, average-case, and worst-case time complexity of **O(n log n)**, with **O(1)** auxiliary space.

### Practical 4: Factorial Using Iteration and Recursion
Calculates the factorial of a non-negative integer using two approaches. The factorial of `n`, written as `n!`, is the product of all positive integers from 1 to `n`, with `0!` defined as 1.

- Iteration — uses a loop to multiply the numbers from 1 to `n`. This approach avoids function-call overhead and uses constant auxiliary space.
- Recursion — repeatedly calls the function with a smaller value until reaching the base case `0! = 1`. This approach clearly demonstrates the relationship `n! = n × (n - 1)!`.

Both approaches have **O(n)** time complexity. The iterative method uses **O(1)** extra space, whereas the recursive method uses **O(n)** stack space because of the recursive calls. The practical also highlights the importance of a correct base case and valid input handling.

### Practical 5: 0/1 Knapsack Using Dynamic Programming
Solves the 0/1 Knapsack problem using dynamic programming. Given a collection of items, where each item has a weight and a value, the objective is to select items with maximum total value without exceeding the capacity of the knapsack. Each item can either be selected once or left unselected; it cannot be divided or selected multiple times.

The solution builds a table in which each entry represents the best value possible for a particular number of items and capacity. For every item, the algorithm compares the result of including it with the result of excluding it. The table is then traced backwards to identify the items that form the optimal solution.

The dynamic programming solution has **O(nW)** time complexity and **O(nW)** space complexity, where `n` is the number of items and `W` is the knapsack capacity. This practical demonstrates overlapping subproblems, optimal substructure, and how dynamic programming avoids repeated calculations.

### Practical 6: Matrix Chain Multiplication
Determines the most efficient order for multiplying a sequence of matrices. Matrix multiplication is associative, so the order of multiplication can be changed without changing the final result; however, different orders may require very different numbers of scalar multiplications.

Dynamic programming is used to evaluate every possible split of the matrix chain. The algorithm stores the minimum multiplication cost for each subchain and records the split that produces that minimum. After the table is completed, the stored split positions are used to display the optimal parenthesization.

The practical shows why multiplying matrices in their listed order is not always efficient and explains how the cost depends on the dimensions of the matrices. Its time complexity is **O(n³)** and its space complexity is **O(n²)**, where `n` is the number of matrices.

### Practical 7: Coin Change Using Dynamic Programming
Finds the minimum number of coins required to make a specified amount from a given set of denominations. An unlimited number of coins of each denomination may be used, and the order in which coins are selected does not affect the result.

The dynamic programming approach creates an array where each position stores the minimum number of coins needed to form that amount. It builds the solution from smaller amounts to larger amounts by checking every available denomination. If no combination can form the required amount, the solution returns `-1`.

This practical demonstrates the optimal substructure of the problem and the use of a sentinel value to represent unreachable amounts. For `n` coin denominations and target amount `A`, the time complexity is **O(nA)** and the space complexity is **O(A)**. It also distinguishes the minimum-coin version of Coin Change from versions that count the total number of possible combinations.

### Practical 8: Graph Traversal
Implements two fundamental graph traversal algorithms for visiting all reachable vertices in a graph:

- Breadth-First Search (BFS) — explores vertices level by level using a queue. It visits all adjacent vertices before moving to the next level and can be used to find the shortest path in an unweighted graph.
- Depth-First Search (DFS) — explores as far as possible along each branch before backtracking, using recursion or an explicit stack. It is useful for connected-component detection, cycle detection, and path exploration.

The practical represents a graph using an adjacency list and maintains a visited set to ensure that each vertex is processed only once, including when the graph contains cycles. It explains the difference between traversing directed and undirected graphs and shows how the starting vertex affects the order of traversal.

For a graph with `V` vertices and `E` edges, both BFS and DFS have **O(V + E)** time complexity when an adjacency list is used. Their auxiliary space complexity is **O(V)**. The practical also emphasizes that traversal order can vary depending on the order in which neighboring vertices are stored.
