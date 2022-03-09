# Big o
Algorithm Efficiency Analysis The efficiency of an algorithm or function is expressed using the big O(oh) notation. Two factors are used to assess its efficiency:
- Running Time
- Memory Space

Big O is made up of four primary components:
- If your algorithm has two different steps, you combine them together: If a first step takes O(a) time and a second step takes O(b) time, the result is O(a+b).

- Drop constants: if you get an O(2n) result, just drop the 2 ---> O (n)

- If you have separate inputs, you'll use different variables to represent them. For example, if you have two arrays and wish to discover the common elements, you'll use two variables. Because there are two arrays, n should not be the array size; instead, define an as size array 1 and b as size array b ---> O(a*b).
- Remove non-dominant terms: if the first step takes O(n) and the second step takes O(n2), the result is O(n+n2). BUT, in reality, this means ---> O(n2).

# Reading Linked List
A linked list is a data structure with nodes that connect to the next node in the list.<br>

Singly - Singly refers to the node's number of references. There is just one reference in a singly linked list, and the reference points to the next node in the linked list.<br>

Doubly - The term "doubly" refers to the fact that the node has two (double) references. There is a reference to both the Next and Previous node in a doubly linked list.<br>


Individual items/links that live in a linked list are referred to as nodes. Each link's data is stored in each node.
<br>

Next - There is a property named Next on each node. The reference to the next node is stored in this property.<br>

Head - In a linked list, the Head is a reference type of type Node to the first node.<br>

Current - The Current reference is a sort of Node reference that is currently being examined. When traversing a full linked list, this node is typically used. When traversing, it's common practice to set the current to the head to ensure that you're starting at the top of the linked list.

