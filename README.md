## C++ and Data Structures 
# Selection Sorting Algorithm
Selection Sort is a simple comparison-based sorting algorithm. It works by dividing the input array into two subarrays: one that is sorted and one that is unsorted. The algorithm repeatedly selects the minimum (or maximum) element from the unsorted subarray and moves it to the beginning of the sorted subarray. This process continues until the entire array is sorted.

## How Selection Sort Works
1. **Initialization**: The sorted subarray is initially empty, and the unsorted subarray contains all elements.
1. **Selection**: In each pass, the algorithm finds the minimum (or maximum) element from the unsorted subarray.
1. **Swap**: The selected minimum (or maximum) element is then swapped with the first element of the unsorted subarray, which becomes part of the sorted subarray.
1. **Repeat**: Steps 2 and 3 are repeated for the remaining unsorted subarray until the entire array is sorted.

## Uses of Selection Sort
1. **Simple Sorting**: Selection Sort is straightforward to implement and works well for small arrays or lists.
1. **Educational Purposes**: It is often used in educational contexts to teach basic sorting algorithms and their principles.
1. **When Memory Usage is a Concern**: Selection Sort is an in-place sorting algorithm, meaning it doesn't require additional memory for temporary storage, making it useful in memory-constrained environments.

## Advantages of Selection Sort
1. **Simplicity**: Selection Sort is easy to understand and implement, making it a good choice for educational purposes and as a simple sorting algorithm when code simplicity is a priority.
1. **In-Place Sorting**: Selection Sort sorts the array in place, meaning it doesn't require additional memory for sorting.
1. **Deterministic**: Selection Sort has a predictable behavior, making it suitable for scenarios where predictability is important.
1. **Minimal Data Movement**: Selection Sort minimizes data movement, which can be an advantage when data is expensive to move.

## Codes
### [SelectionSort.cpp](https://github.com/Nithish-1804/Selection-Sort/blob/main/SelectionSort%20(19-10).cpp)
