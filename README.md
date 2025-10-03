# implementation-of-big-o-notation-in-c-
Implementation of Big O Notation in C++

Aim

To explore and understand the concept of Big O Notation by analyzing the time complexity of different operations in C++.

Software Required

Online C++ Compiler


Theory

Big O Notation is a mathematical concept used in computer science to describe the upper bound of an algorithm’s running time or space requirement in terms of input size n.

It provides a way to analyze how an algorithm’s performance scales as the size of the input data increases, helping developers choose efficient algorithms.

Why Big O Notation?

Hardware (CPU speed, RAM, etc.) may vary, but Big O notation focuses on growth rate rather than exact execution time.

It allows comparison of algorithms independently of machine specifications.

Common Time Complexities

1. O(1) – Constant Time

Execution time remains constant regardless of input size.

Example: Accessing the first element of an array.



2. O(n) – Linear Time

Execution time grows proportionally with input size.

Example: Traversing/printing all elements of a list.



3. O(n²) – Quadratic Time

Execution time grows as the square of input size.

Example: Printing all possible pairs in an array (nested loops).


Explanation of the Code

The program demonstrates three functions, each representing different time complexities:

1. getFirstElement() – O(1):

Directly accesses and returns the first element of a vector.

Independent of vector size.



2. printElements() – O(n):

Iterates through all elements using a loop.

Execution time grows linearly with input size.



3. printPairs() – O(n²):

Uses nested loops to print all element pairs.

Time grows quadratically with input size.

This comparison shows how algorithms scale differently with data growth.

Algorithm

1. Start.


2. Create a vector of integers with sample data.


3. Implement a function getFirstElement() to access the first element. (O(1))


4. Implement a function printElements() to iterate and print all elements. (O(n))


5. Implement a function printPairs() to print every possible pair. (O(n²))


6. Call all three functions with the vector.


7. Observe execution results for each function.


8. End.


Conclusion

The program highlights the practical effect of time complexities on algorithm efficiency:

O(1): Constant Time

Extremely fast, independent of dataset size.

Ideal for direct lookups and accessing indexed elements.
O(n): Linear Time

Grows proportionally with input size.

Suitable for small to moderately large datasets.
O(n²): Quadratic Time

Growth is rapid, making it inefficient for large datasets.

Acceptable only for small input sizes or when quadratic relationships are unavoidable.
