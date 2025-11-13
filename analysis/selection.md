# 🧩 Selection Sort – Summary Analysis

## Time Complexity
- The time complexity graph shows a **steady quadratic increase** as the input size grows.  
- Selection Sort always performs the same number of comparisons, regardless of data order, confirming its **O(n²)** behavior.  
- This makes it slower for large datasets compared to more efficient algorithms like Merge Sort or Quick Sort.

## Space Complexity
- The space graph increases linearly with the input size, corresponding to the memory occupied by the input array.  
- Selection Sort is an **in-place algorithm**, requiring only **O(1)** additional memory for temporary variable swaps.

## ➡️ Conclusion
Selection Sort is **simple and predictable**, but it is **inefficient for large datasets** because of its **O(n²)** time complexity.  
It performs a fixed number of comparisons and swaps, making it more efficient than Bubble Sort in terms of swaps but still unsuitable for large-scale sorting tasks.
