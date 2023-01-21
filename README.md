JavaScript Code of Streak - Day15

Q) Write a JavaScript program to create and display Singly Linked List.

Explanation:

A singly linked list is a type of linked list that is unidirectional, that is, it can be traversed in only one direction from head to the last node (tail).

Each element in a linked list is called a node. A single node contains data and a pointer to the next node which helps in maintaining the structure of the list.
The first node is called the head; it points to the first node of the list and helps us access every other element in the list. The last node, also sometimes called the tail, points to NULL which helps us in determining when the list ends.

In this program, firstly a node constructor is created - node with a class. It takes the data and next arguements.
Then the main container constructor is created — linked list constructor, which will be the container of all our nodes.
The head property points to the first node in the list.

As our linked list’s starting point is the head, it will point to nowhere (null) initially, because when we first create a list, there will be no nodes to point to.
The next constructor item in our Linked List class is the length of the linked list and it’s optional. We assign 0 to the length because as we know, initially our list will have no nodes.
