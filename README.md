practical 1:sorting algorithms   

Summary

This repository contains Python implementations of five fundamental sorting algorithms: Bubble Sort, Selection Sort, Insertion Sort, Merge Sort, and Quick Sort. Each program accepts user input, sorts the given data in ascending order, and displays the sorted output along with the algorithm's theoretical time complexity, space complexity, and the number of comparisons and swaps (where applicable). The code is written in a simple and well-commented manner, making it suitable for beginners and academic practicals.

Conclusion

This practical demonstrates the implementation and comparison of different sorting algorithms in Python. It highlights the differences in their efficiency, time complexity, and space complexity. Simple algorithms such as Bubble, Selection, and Insertion Sort are suitable for small datasets, while Merge Sort and Quick Sort provide better performance for larger datasets. This repository serves as a useful reference for understanding the working, performance, and practical applications of sorting algorithms in Data Structures and Design and Analysis of Algorithms (DAA).

Practical 2: Linear Search and Binary Search
Summary
This practical implements and compares two searching algorithms: Linear Search and Binary Search. Linear Search checks each element sequentially until the target is found, while Binary Search repeatedly divides a sorted array into smaller portions to locate the target efficiently. The program accepts a sorted list and a search element as input, displays whether the element is present, and measures the execution time of both algorithms.

Conclusion
This practical demonstrates that Linear Search is simple and can be used on any list, but it has a time complexity of O(n). Binary Search is more efficient for sorted arrays, with a time complexity of O(log n). Therefore, Binary Search is preferable when working with large, sorted datasets, while Linear Search is useful for small or unsorted lists.

Practical 3: Heap Sort
Summary
This practical implements the Heap Sort algorithm using a Max Heap. The program first builds a Max Heap from the input elements and then repeatedly moves the largest element to the end of the array. After restoring the heap property, the process continues until the entire array is sorted in ascending order.

Conclusion
Heap Sort is an efficient comparison-based sorting algorithm with a time complexity of O(n log n) in the best, average, and worst cases. It sorts the elements in place and requires only O(1) additional space. This practical demonstrates how heap data structures can be used to perform reliable and efficient sorting.

Practical 4: Factorial Using Iteration and Recursion
Summary
This practical calculates the factorial of a number using two different approaches: iteration and recursion. In the iterative method, a loop multiplies all integers from 1 to the given number. In the recursive method, the factorial function calls itself with a smaller value until it reaches the base case of 0 or 1.

Conclusion
Both iterative and recursive approaches produce the same factorial result. The iterative method is generally more memory-efficient because it uses O(1) auxiliary space. The recursive method clearly demonstrates the concept of function calls and base cases, but it requires O(n) stack space. Both methods have a time complexity of O(n).

Practical 7: Coin Change Using Dynamic Programming
Summary
This practical solves the Minimum Coin Change Problem using Dynamic Programming. The program accepts a set of coin denominations and a target amount, then calculates the minimum number of coins required to form that amount. It stores previously calculated results in a dynamic programming array to avoid repeating the same calculations. If the amount cannot be formed using the available coins, the program reports that no solution exists.

Conclusion
The Dynamic Programming approach provides an efficient solution to the Minimum Coin Change Problem by storing and reusing intermediate results. The algorithm has a time complexity of O(n × amount), where n is the number of coin denominations, and a space complexity of O(amount). This practical demonstrates how dynamic programming can solve optimization problems by breaking them into smaller overlapping subproblems.
