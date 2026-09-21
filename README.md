
PRACTICAL 1:

Summary :

This practical was used to implement and analyze five sorting algorithms: Bubble Sort, Selection Sort, Insertion Sort, Merge Sort, and Quick Sort. Each algorithm sorts the elements in ascending order, but their working methods and execution times are different.

Bubble Sort repeatedly compares and swaps adjacent elements.(Best Case: O(n)Average Case: O(n²)Worst Case: O(n²))

Selection Sort finds the smallest element and places it in the correct position.(Best Case: O(n²)Average Case: O(n²)Worst Case: O(n²))

Insertion Sort inserts each element into its proper place in the sorted part of the array.(Best Case: O(n) Average Case: O(n²)Worst Case: O(n²))

Merge Sort divides the array into smaller parts, sorts them, and merges them.(Best Case: O(n log n) Average Case: O(n log n)Worst Case: O(n log n))

Quick Sort selects a pivot element and partitions the array into smaller subarrays.(Best Case: O(n log n) Average Case: O(n log n)Worst Case: O(n²))

Conclusion :

From this practical, we learned that every sorting algorithm has its own advantages and disadvantages. Bubble Sort, Selection Sort, and Insertion Sort are simple but slower for large datasets. Merge Sort and Quick Sort are faster and more efficient for large datasets. We also understood that choosing the right sorting algorithm depends on the size of the data and the application requirements.

PRACTICAL 2 :

Summary :

In this practical, we implemented Linear Search and Binary Search algorithms and compared their execution time.

Linear Search checks each element one by one until the element is found.(Best Case: O(1)Average Case: O(n)Worst Case: O(n))

Binary Search searches by dividing the sorted array into two halves, so it is faster.(Best Case: O(1) Average Case: O(log n)Worst Case: O(log n))

Linear Search works on both sorted and unsorted arrays. Binary Search works only on sorted arrays.

Conclusion :

Linear Search is simple and works on both sorted and unsorted arrays. Binary Search is faster but works only on sorted arrays. The time analysis shows that Binary Search takes less time than Linear Search. Therefore, Binary Search is better for large sorted data, while Linear Search is suitable for small or unsorted data.

PRACTICAL 3:

Summary :

Max Heap Sort Explanation
A Max Heap is a binary heap where the largest element is always at the root.

Steps:

Convert the array into a Max Heap. The largest element comes to the first position. Swap the first element with the last element. Remove the last element from the heap. Heapify the remaining elements. Repeat until the array is sorted.

Example:

Array: 40 10 30 20 50

Max Heap: 50 20 30 10 40

After sorting: 10 20 30 40 50 Time Complexity Building Max Heap: O(n) Heapify: O(log n) Best Case: O(n log n) Average Case: O(n log n) Worst Case: O(n log n) Space Complexity

O(log n) with recursive heapify.

Min Heap Sort Explanation
A Min Heap is a binary heap where the smallest element is always at the root.

Steps:

Convert the array into a Min Heap. The smallest element comes to the root. Swap the root with the last element. Remove the last element from the heap. Heapify the remaining elements. Repeat until all elements are sorted.

Example:

Array: 40 10 30 20 50

Min Heap: 10 20 30 40 50

A Min Heap naturally gives the smallest element first. Depending on how the extraction is implemented, it can produce descending order; reversing the result gives ascending order.

Time Complexity Building Min Heap: O(n) Heapify: O(log n) Best Case: O(n log n) Average Case: O(n log n) Worst Case: O(n log n) Space Complexity

O(log n) with recursive heapify.

Simple difference

Max Heap: Largest element → root → commonly used to get ascending order with standard heap sort.

Min Heap: Smallest element → root → commonly used to get descending order with standard extraction, or ascending order after reversing.

Conclusion

Both Max Heap and Min Heap are important heap structures in DAA. Heap Sort has O(n log n) time complexity in the best, average, and worst cases. Max Heap is commonly used for ascending Heap Sort, while Min Heap can be used for descending Heap Sort.

PRACTICAL 4:

Summary :

This practical was used to implement and analyze a factorial program using iterative and recursive methods. Both methods calculate the factorial of a given number, but their working methods and memory usage are different.

Iterative Method calculates the factorial by using a loop and repeatedly multiplying the numbers from 1 to n. Time Complexity: O(n) Space Complexity: O(1)

Recursive Method calculates the factorial by calling the same function repeatedly with a smaller value until it reaches the base condition. Time Complexity: O(n) Space Complexity: O(n)

Conclusion :

From this practical, we learned that both iterative and recursive methods can be used to calculate the factorial of a number. Both methods have O(n) time complexity, but their space requirements are different. The iterative method uses less memory and is more memory efficient, while the recursive method is useful for understanding the concept of recursion. We also learned how to calculate and compare the execution time of both methods.

PRACTICAL 5:

Summary:

The 0/1 Knapsack Problem was implemented using Dynamic Programming to determine the maximum total value that can be obtained without exceeding the given weight capacity of the knapsack. The problem was divided into smaller subproblems, and a dynamic programming table was used to store previously calculated results. This avoids repeated calculations and makes the solution more efficient than a straightforward recursive approach. The final table provides the maximum achievable value for each possible capacity and set of items.

Conclusion
The Dynamic Programming approach provides an efficient and systematic solution to the 0/1 Knapsack Problem. By storing the solutions to overlapping subproblems, it reduces unnecessary computation and solves the problem in O(nW) time, where n is the number of items and W is the knapsack capacity. Thus, dynamic programming is an effective technique for solving optimization problems such as the Knapsack Problem.

PRACTICAL 6:

Summary:

The Chain Matrix Multiplication problem was implemented using Dynamic Programming to determine the most efficient order of multiplying a sequence of matrices. Since matrix multiplication is associative, different parenthesizations can produce different numbers of scalar multiplications. A dynamic programming table was used to store the minimum multiplication cost for different matrix chains, avoiding repeated calculations.

Conclusion
Dynamic Programming provides an efficient method for finding the optimal order of matrix multiplication. It reduces unnecessary computations by storing solutions to smaller subproblems and helps minimize the total number of scalar multiplications required.

PRACTICAL 7:

Summary
The Making Change problem was implemented using Dynamic Programming to find the minimum number of coins required to make a given amount of money. The problem was divided into smaller amounts, and the minimum number of coins for each amount was stored in a table. This avoids recalculating the same subproblems and provides an efficient solution.

Conclusion
Dynamic Programming is an effective technique for solving the Making Change problem. By storing previously calculated results, it reduces repeated computations and efficiently determines the minimum number of coins needed for a given amount. This practical demonstrates how Dynamic Programming can be applied to optimization problems.
