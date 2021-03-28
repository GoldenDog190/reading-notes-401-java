# Read: Trees

## [Trees](https://codefellows.github.io/common_curriculum/data_structures_and_algorithms/Code_401/class-15/resources/Trees.html)

**Trees**
  * Terminology
    - Node - A Tree node is a component which may contain it’s own values, and references to other nodes
    - Root - The root is the node at the beginning of the tree
    - K - A number that specifies the maximum number of children any node may have in a k-ary tree.
    - Left - A reference to one child node, in a binary tree
    - Right - A reference to the other child node, in a binary tree
    - Edge - The edge in a tree is the link between a parent and child node
    - Leaf - A leaf is a node that does not have any children
    - Height - The height of a tree is the number of edges from the root to the furthest leaf.
  * Traversals - traversing a tree allows us to search for a node, and print out the contents of a tree
    - 2 categories of traversals:
      * Depth First - prioritizes going through the depth of the tree first and there are multiple ways to carry out depth first traversal, and each method changes the order in which we search/print the root. To traverse through a tree is to use recursion. 
        - 3 methods of Depth First: 
        Pre-order: root >> left >> right
        In-order: left >> root >> right
        Post-order: left >> right >> root
      * Breadth First - 