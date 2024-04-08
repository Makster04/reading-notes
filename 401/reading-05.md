# [Implementation: Linked List(Allegedly Reading-05)](https://github.com/codefellows/seattle-code-javascript-401d59/tree/main/class-05)

## Explaining a Linked List (Why, What, How):
* **WHY use a Linked List?**
* Linked Lists are used as a fundamental data structure in computer science due to their dynamic memory allocation and efficient insertions and deletions, especially when compared to arrays. They are particularly useful when the size of the data structure is not fixed, as they can dynamically grow and shrink as needed.

**WHAT is a Linked List?**
* A Linked List is a data structure consisting of a sequence of nodes, where each node contains a piece of data and a reference/pointer to the next node in the sequence. This structure allows for efficient insertion and deletion operations, but it requires traversal from the head node to access elements.

**HOW does a Linked List work?**
* In a Singly Linked List, each node contains a value and a reference to the next node. Traversal through the list involves starting from the head node and moving to the next node until reaching the end (where the next node is null). Adding a node to the beginning of the list (O(1) operation) involves creating a new node, setting its next reference to the current head, and updating the head reference. Adding a node elsewhere in the list (O(n) operation) requires traversing to the appropriate position, adjusting references, and inserting the new node. Printing the elements involves traversing the list and outputting each node's value until reaching the end.

## Resources
* **[Big O: Analysis of Algorithm Efficiency](https://codefellows.github.io/common_curriculum/data_structures_and_algorithms/Code_401/class-05/resources/big_oh.html)**
* **[Linked List](https://codefellows.github.io/common_curriculum/data_structures_and_algorithms/Code_401/class-05/resources/singly_linked_list.html)]**
* **[Read: What’s a Linked List, Anyway pt1](https://medium.com/basecs/whats-a-linked-list-anyway-part-1-d8b7e6508b9d)**
* **[What’s a Linked List, Anyway pt2](https://medium.com/basecs/whats-a-linked-list-anyway-part-2-131d96f71996)**
