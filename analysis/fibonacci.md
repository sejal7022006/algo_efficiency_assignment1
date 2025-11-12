# 🧩 Fibonacci Algorithm – Summary Analysis

## Recursive Version
- Extremely slow for larger inputs due to repeated subproblem computation.  
- **Time Complexity:** O(2ⁿ)  
- **Space Complexity:** O(n) (call stack)  
- Graph shows steep time increase after *n = 20*.

## Dynamic Programming Version
- Stores previous results, avoiding redundant calls.  
- **Time Complexity:** O(n)  
- **Space Complexity:** O(n)  
- Graph remains almost flat, showing minimal growth in time.

## ➡️ Conclusion
Dynamic Programming is **much faster and more efficient**, proving the power of memoization in optimizing recursive algorithms.
