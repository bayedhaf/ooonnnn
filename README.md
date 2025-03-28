# Best Algorithms for Common Problem Categories  

## 1. Searching Algorithms  
### Binary Search (Best for sorted data)  
#### Time Complexity:  
𝑂(log𝑛)  
#### Usage:  
Efficiently searches a sorted array by repeatedly dividing the search interval in half.  

---

## 2. Sorting Algorithms  
### Merge Sort (Best for large datasets)  
#### Time Complexity:  
𝑂(𝑛log𝑛)  
#### Usage:  
Stable sorting ideal for linked lists and large datasets.  
#### Advantages:  
Predictable performance, works well with external storage.  

### Quick Sort (Best average performance)  
#### Time Complexity:  
𝑂(𝑛log𝑛) average, 𝑂(𝑛²) worst-case  
#### Usage:  
Faster than Merge Sort in practice due to cache efficiency.  

### Heap Sort (Best for in-place sorting)  
#### Time Complexity:  
𝑂(𝑛log𝑛)  
#### Usage:  
Memory-efficient for space-constrained environments.  

---

## 3. Graph Algorithms  
### Dijkstra's Algorithm (Shortest path in weighted graphs)  
#### Time Complexity:  
𝑂(𝑉log𝑉 + 𝐸) (with priority queue)  
#### Usage:  
Finds shortest paths from a source node (non-negative weights).  

### Kruskal's Algorithm (Minimum Spanning Tree)  
#### Time Complexity:  
𝑂(𝐸log𝐸)  
#### Usage:  
Connects all graph nodes with the least total edge weight.  

---

## 4. Dynamic Programming  
### Fibonacci Sequence (DP approach)  
#### Time Complexity:  
𝑂(𝑛)  
#### Usage:  
Optimizes problems with overlapping subproblems (e.g., Fibonacci, Knapsack).  

### 0/1 Knapsack Problem  
#### Time Complexity:  
𝑂(𝑛𝑊)  
#### Usage:  
Solves resource allocation with weight/benefit trade-offs.  

---

## 5. Greedy Algorithms  
### Huffman Coding (Data compression)  
#### Time Complexity:  
𝑂(𝑛log𝑛)  
#### Usage:  
Generates optimal prefix codes for lossless compression.  

---

## 6. Divide and Conquer  
### Merge Sort (Stable sorting)  
#### Time Complexity:  
𝑂(𝑛log𝑛)  
#### Usage:  
Reliable for large, stable-sort needs.  

### Quick Sort (Average-case efficiency)  
#### Time Complexity:  
𝑂(𝑛log𝑛) average case  
#### Usage:  
Preferred for general-purpose sorting.  
