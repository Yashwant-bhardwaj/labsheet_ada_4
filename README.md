What is Quick Sort?
Quicksort is a divide-and-conquer sorting algorithm that works by selecting a pivot element and partitioning the array into two subarrays—one with elements smaller than the pivot and another with elements greater than the pivot. These subarrays are then sorted recursively.

Why is Quick Sort Used?
Efficiency: It has an average-case time complexity of O(n log n), making it one of the fastest sorting algorithms for large datasets.
In-Place Sorting: It doesn’t require extra space like merge sort (except for recursive calls).
Widely Used: It is commonly used in standard libraries (e.g., C’s qsort(), Python’s sorted()) due to its speed and efficiency in most cases.
Advantages of Quick Sort
Fast Performance: On average, it performs better than other sorting algorithms like merge sort and bubble sort.
In-Place Sorting: Requires only O(log n) extra space, unlike merge sort, which needs O(n) extra space.
Efficient for Large Datasets: Works well for large data due to its O(n log n) time complexity.
Used in Libraries: Many programming languages use quicksort or variations of it in their sorting functions.
Disadvantages of Quick Sort
Worst-Case Complexity of O(n²): If the pivot selection is poor (e.g., always choosing the smallest or largest element), performance degrades significantly.
Recursive Calls Use Stack Memory: Deep recursion in an unbalanced partition can cause a stack overflow.
Not Stable: Quicksort does not preserve the relative order of equal elements, making it unstable in its basic form.
