# 🧩 Bubble Sort – Summary Analysis

## Time Complexity
- The time graph shows a **rapid increase in execution time** as the input size grows, confirming a **quadratic growth pattern (O(n²))**.  
- For small datasets, performance is acceptable, but as `n` increases, the number of pairwise comparisons and swaps rises dramatically.  
- The algorithm’s nested loops make it inefficient for large datasets.

## Space Complexity
- The space graph increases linearly with input size since it depends only on the array storage.  
- Bubble Sort is **in-place**, meaning it requires only **O(1)** extra space beyond the input array.

## ➡️ Conclusion
Bubble Sort is simple to understand and implement but highly **inefficient for large datasets** due to its **O(n²)** time complexity.  
It is suitable mainly for **educational purposes** or **very small data inputs**, where performance is not a concern.
