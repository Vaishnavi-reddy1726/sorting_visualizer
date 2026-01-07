# Sorting-Visualizer
A pictorial representation demonstrating how Data Structures and Algorithms can be used to sort any data.



![Screenshot 2023-01-07 162427](https://user-images.githubusercontent.com/74191100/211145941-92a66622-9fcd-4c67-9255-aef4b82652c3.png)





# How Visualization Works

The visualizer represents each element of the array as a colored bar. When an algorithm is running:
Yellow bars indicate elements currently being compared.
Red bars indicate elements being swapped or actively modified.
Green bars show elements that are in their correct sorted position.
While the sorting process is in progress, interactive buttons are disabled to avoid interference. Bar heights and colors update dynamically to reflect the algorithm’s operation.


## **Bubble Sort**

Bubble Sort repeatedly compares adjacent elements and swaps them if they are in the wrong order. Larger elements “bubble” to the top with each pass.

Complexity: O(n²) and Best For: Small datasets

## **Insertion Sort**

Insertion Sort builds a sorted portion of the array one element at a time. Each new element is placed in the correct position within the sorted section.

Complexity: O(n²) and Best For: Small or nearly sorted datasets

## **Selection Sort**

Selection Sort repeatedly finds the minimum element from the unsorted part and places it at the beginning. It gradually grows the sorted portion of the array.

Complexity: O(n²) and Best For: Small datasets

## **Merge Sort**

Merge Sort is a divide-and-conquer algorithm. It splits the array into smaller subarrays, sorts them, and then merges them back together in order.

Complexity: O(n log n) and Best For: Large datasets

Note: Requires extra memory for merging; faster than quadratic algorithms.

## **Heap Sort**

Heap Sort converts the array into a heap structure, repeatedly removes the largest element, and places it in the sorted portion.

Complexity: O(n log n) and Best For: Large datasets

Note: Efficient in time but works in place with minimal additional memory.

## **Quick Sort**

Quick Sort selects a pivot and partitions the array such that elements smaller than the pivot go to the left and larger elements go to the right. It recursively applies this process to each partition.

Complexity: Average O(n log n), Worst O(n²) and Best For: Large datasets

Note: Fast and widely used but not stable; equal elements may change relative positions.

**How This Project Helps**

**Visual Learning** : See exactly how each sorting algorithm operates step by step.

**Comparative Understanding** : Observe differences in efficiency and behavior between algorithms.

**Interactive Exploration** : Modify array size and elements to test algorithms dynamically.