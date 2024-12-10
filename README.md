### GitHub README

## Problem Description  

You are given the root of a binary tree. Imagine yourself standing on the **right side** of the tree. Your task is to return the values of the nodes that are visible from the right side, ordered from top to bottom.  

---

### Solution Approach  

The solution employs a **Breadth-First Search (BFS)** approach to determine the rightmost node at each level of the tree.  

**Steps**:  
1. **Level Order Traversal**:  
   - Use a queue to traverse the tree level by level.  
2. **Track Rightmost Node**:  
   - For each level, process all nodes and record the last node's value (rightmost node) for that level.  
3. **Result Compilation**:  
   - Add the rightmost node values from each level to the result list.  

---

### Time and Space Complexity  

- **Time Complexity**: O(n), where `n` is the number of nodes in the binary tree. Each node is processed once.  
- **Space Complexity**: O(n), for the queue used during the traversal.  

---

For a detailed explanation of the approach, visit the [description here](https://leetcode.com/problems/binary-tree-right-side-view/).
