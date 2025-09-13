# Binary Trees – Concepts & Key Points

## 📌 What is a Binary Tree?
A **binary tree** is a hierarchical data structure in which each node has at most **two children**:
- The **left child**
- The **right child**

It is commonly used in computer science for efficient searching, sorting, and hierarchical data representation.

---

## 📌 Difference Between a Binary Tree and a Binary Search Tree (BST)
- **Binary Tree**
  - A general structure where each node can have up to two children.
  - No specific ordering rules are required.
  
- **Binary Search Tree (BST)**
  - A specialized type of binary tree.
  - **Left child** contains values smaller than the parent.
  - **Right child** contains values greater than the parent.
  - Enables efficient searching, insertion, and deletion.

---

## 📌 Gain in Terms of Time Complexity Compared to Linked Lists
- **Linked List**
  - Search: `O(n)`
  - Insertion/Deletion (at known position): `O(1)`
  
- **Binary Search Tree (Balanced)**
  - Search: `O(log n)`
  - Insertion: `O(log n)`
  - Deletion: `O(log n)`

✅ This makes BSTs much more efficient for searching compared to linked lists, especially for large datasets.

---

## 📌 Depth, Height, and Size of a Binary Tree
- **Depth of a node**: The number of edges from the root to that node.
- **Height of a node**: The number of edges on the longest path from that node down to a leaf.
- **Height of the tree**: Height of the root node.
- **Size of the tree**: Total number of nodes in the tree.

---

## 📌 Traversal Methods of a Binary Tree
There are different ways to visit (traverse) all nodes:

1. **Depth-First Traversals**
   - **Pre-order (Root → Left → Right)**
   - **In-order (Left → Root → Right)**
   - **Post-order (Left → Right → Root)**

2. **Breadth-First Traversal**
   - **Level-order traversal** (visit nodes level by level)

---

## 📌 Types of Binary Trees
- **Complete Binary Tree**
  - All levels are completely filled except possibly the last.
  - The last level has nodes as far left as possible.

- **Full Binary Tree**
  - Every node has either **0 or 2 children**.
  - No node has only one child.

- **Perfect Binary Tree**
  - Both **full** and **complete**.
  - All internal nodes have 2 children and all leaves are at the same level.

- **Balanced Binary Tree**
  - A tree in which the difference between the heights of left and right subtrees of any node is at most **1**.
  - Example: AVL trees, Red-Black trees.

---

## ✅ Summary
Binary trees form the foundation for more advanced data structures like **heaps, AVL trees, Red-Black trees, and B-trees**.  
Understanding their properties, traversals, and variations is essential for efficient problem-solving in algorithms and system design.

