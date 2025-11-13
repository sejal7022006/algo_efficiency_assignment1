# 🧩 Insertion Sort – Summary Analysis

## Time Complexity
- The time graph shows a **sharp increase in execution time** as input size grows, confirming its **O(n²)** behavior.  
- For small datasets, the algorithm performs efficiently since it requires minimal comparisons and shifts.  
- However, as `n` increases, the number of comparisons and swaps grows quadratically, resulting in slower performance.

## Space Complexity
- The space complexity graph increases linearly with input size due to the array size itself.  
- Insertion Sort is **in-place**, meaning it requires only a **constant amount of extra memory (O(1))** besides the input array.

## ➡️ Conclusion
Insertion Sort performs well for **small or nearly sorted datasets**, offering simplicity and low memory usage.  
However, it becomes inefficient for large inputs because of its **quadratic time complexity**, making it unsuitable for large-scale sorting tasks.
