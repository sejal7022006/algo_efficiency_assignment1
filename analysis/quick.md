# ⚡ Quick Sort – Summary Analysis

## 🕒 Time Complexity
- The time graph shows **increasing execution time** as input size grows.
- The rate of increase is roughly **O(n log n)**, with sharper growth between **500–1000 elements**.
- Slight variations appear due to recursion overhead and system conditions.

**Observation Table**

| Input Size (n) | Time (seconds) |
|----------------|----------------|
| 10             | ~0.00002       |
| 100            | ~0.0001        |
| 500            | ~0.0007        |
| 1000           | ~0.0041        |
| 2000           | ~0.0048        |

**Conclusion:**  
Quick Sort performs efficiently in most cases, showing time complexity close to **O(n log n)**.  
However, unbalanced pivots can lead to **O(n²)** in the worst case.

---

## 💾 Space Complexity
- The space graph increases **linearly** with the input size.
- This indicates memory consumption is **proportional to n**, due to recursion and array partitioning.
- The theoretical space complexity is **O(log n)** (average) and **O(n)** (worst case).

**Observation Table**

| Input Size (n) | Estimated Space (bytes) |
|----------------|--------------------------|
| 10             | ~80                      |
| 100            | ~800                     |
| 500            | ~4000                    |
| 1000           | ~8000                    |
| 2000           | ~16000                   |

**Conclusion:**  
Quick Sort’s space grows predictably with input size, mainly due to recursive stack usage.

---

## 📊 Overall Summary

| Metric | Best Case | Average Case | Worst Case |
|--------|------------|---------------|-------------|
| **Time Complexity** | O(n log n) | O(n log n) | O(n²) |
| **Space Complexity** | O(log n) | O(log n) | O(n) |

**Final Insight:**  
Quick Sort is a **divide-and-conquer algorithm** that sorts efficiently for large datasets.  
Its performance depends heavily on the **pivot selection strategy** — good pivots ensure faster sorting with minimal memory use.
