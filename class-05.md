# Read: Linked Lists


## [Linked Lists](https://codefellows.github.io/common_curriculum/data_structures_and_algorithms/Code_401/class-05/resources/singly_linked_list.html)

**What is a Linked List**
* *Linked List* - a sequence of Nodes that are connected/linked to each other, and the defining feature of it is that each Node references the next Node in the link.
* Two types of Linked List
  - *Singly* - refers to the number of references the node has. 
    * Singly linked list - has only one reference, and the reference points to the Next node in a linked list
  - *Doubly* - refers to there being two references within the node
    * Doubly linked list - a reference to both the Next and Previous node
* *Node* - individual items/links that live in a linked list, and contains the data for each link
* *Next* - a property each node contains, and contains the reference to the next node
* *Head* - a reference type of type Node to the first node in a linked list
* *Current* - a reference type of type Node that is currently being looked at
* *Traversal* - traversing a linked list
  - Not able to use a foreach or for loop, so you have to use the Next value.
  - Next property - lead us where the next node is and allow us to extract the data appropriately.
  - while() loop - allows us to continually check that the Next node in the list is not null
  - Current node - tell us where exactly in the linked list we are and will allow us to move/traverse forward until we hit the end
  - NullReferenceException - gets thrown when you try to traverse on a node that is null.
* Big O 
  - Big O of time for Includes would be O(n), and in the worse case the node we are looking for will be the very last node in the linked list. 
    * n - represents the number of nodes in the linked list
  - Big O of space for Includes would be O(1), and this is because there is no additional space being used. 
* Adding a node O(1) - order of operations is extremely important when it comes to working with a Linked List.
  - To add a node with an O(1) efficiency, replace the current Head of the linked list with the new node, without losing the reference to the next node in the list.
* Adding a node O(n) - to add a node to the middle of the list first create a new node, and set the value, and then you can start adding the Add method
* Print out nodes by using the Print() method, and we will be leveraging our Current Node and a while loop to traverse through the existing linked list. The while loop will check and make sure we are not at the end of a linked list, and before before the while loop restarts move Current to equal the next node in the list. At the end it will point to null.


## [What’s a Linked List, Anyway pt1](https://medium.com/basecs/whats-a-linked-list-anyway-part-1-d8b7e6508b9d)

****

## [What’s a Linked List, Anyway pt2](https://medium.com/basecs/whats-a-linked-list-anyway-part-2-131d96f71996)

****