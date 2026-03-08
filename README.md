# B-Tree-Implementation-in-Python
B-Tree Implementation in Python
# B-Tree Implementation in Python

## Project Description

This project implements a **B-Tree data structure** using Python.
A B-Tree is a self-balancing tree structure commonly used in databases and file systems to efficiently store and search large amounts of data.

## Features

* Insert keys into the B-Tree
* Automatically split nodes when they become full
* Search for a key in the tree
* Print the tree structure by levels
* Different tree traversal methods:

  * In-order traversal
  * Pre-order traversal
  * Post-order traversal
  * Level-order traversal

## Technologies Used

* Python 3

## Classes in the Program

### BTreeNode

Represents a node in the B-Tree.

* `keys` – stores the keys inside the node
* `children` – references to child nodes
* `leaf` – indicates if the node is a leaf node

### BTree

Main class that manages the B-Tree operations.

Key functions:

* `insert(key)` → Inserts a key into the tree
* `split_child(parent, i)` → Splits a full node
* `search(key)` → Searches for a key in the tree
* `print_tree()` → Prints the tree structure

## Traversal Methods

The program supports several tree traversal techniques:

* **In-order Traversal** – visits nodes in sorted order
* **Pre-order Traversal** – visits the root before children
* **Post-order Traversal** – visits children before the root
* **Level-order Traversal** – visits nodes level by level

## Example Usage

```python
btree = BTree(3)

btree.insert(10)
btree.insert(20)
btree.insert(5)
btree.insert(6)
btree.insert(12)

btree.print_tree()

print("In-order:", btree.in_order_traversal())
```

## Project File

* `btree.py` – Python implementation of the B-Tree data structure

## Author

Rtal
