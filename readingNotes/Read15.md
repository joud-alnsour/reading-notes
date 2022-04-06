# Trees
Trees are read from the TOP down, the opposite of real trees.<br>

They start with a root and expand from there with edges pointing towards their child nodes.

## Tree Terminology
- **Node:**
Has it's own values and references to other nodes

- **Root:**
The tree's beginning node

- **K:**
Used in a k-ary tree to identify a node's maximum amount of children

- **Ex:** In a binary tree, k = 2

- **Left:**
Refers to the left child node in a tree

- **Right:**
Refers to the right child node in a tree

- **Edge:**
The link between a parent and child node. The line or arrow in a visual.

- **Leaf:**
A node without children. Quite literally like a leaf on a real tree.

- **Height:**
Quantity of edges from the root to the furthest leaf

## Tree Traversals
"The most common way to traverse through a tree is to use recursion."

**Depth First:**

Going through the height of the tree

There are three methods for depth first traversal and each one changes the order we can search or print the root.

- Pre-order: root -> left -> right
- In-order: left -> root -> right
- Post-order: left -> right -> root

**Breadth First:**

Going through the tree node-by-node (can be thought of as width rather than Depth First's height)

Traversal usually uses a queue rather than call stack via recursion

**Binary vs K-ary Trees:**

Binary Trees can only have TWO children (left and right) whereas K-ary tree nodes can have MORE than two child nodes



[Page Link](https://codefellows.github.io/common_curriculum/data_structures_and_algorithms/Code_401/class-15/resources/Trees.html)
