# Basic Intro to Linked Lists

![image](https://github.com/ConlanSchool/Linked-Lists/assets/121739541/aace6680-5485-427e-a5b9-c04c5ef16740)


---

If you are new to linked lists, we are going to go through the concept and break it down into smaller, more easy to understand pieces.

## What Is a Linked List?

A linked list is a sequential collection of nodes. Each node contains two parts, the data and a link to the next node in the sequence. Each node has information on where they should point to in order to continue the linked list's sequence, forming a connected chain of nodes.

## Why Use Linked Lists?

The reason for using linked lists is because of their versatility and efficiency. When it comes to data structures, an array might seem like an obvious choice due to its simplicity. However, arrays have a few limitations, which are solved using linked lists. 

For example, arrays are of fixed size, meaning you need to specify their size at the time of creation. On the other hand, linked lists are dynamic and can grow and shrink while deployed, making them more flexible for certain applications. 

![image](https://github.com/ConlanSchool/Linked-Lists/assets/121739541/900d35d5-a825-40e2-ba05-7f15eeb54f9d)

---

## Types of Linked Lists

There are actually several types of linked lists. The three main types are:

1. **Singly Linked Lists**: Each node contains data and a pointer to the next node. However, moving back is not possible as there is no reference to the previous node.

2. **Doubly Linked Lists**: Each node contains data and two pointers, one to the next node and another to the previous one. This allows traversal in both directions.

3. **Circular Linked Lists**: Just like the singly linked list, but the last node points back to the first node, creating a loop.

![image](https://github.com/ConlanSchool/Linked-Lists/assets/121739541/ba41625e-be40-4005-926e-415cb01baedf)


---

## Operations of Linked List 

Basic operations that can be performed on linked lists include insertion, deletion, traversal, and search:

1. **Insertion**: A new node can be added at any point. Whether at the beginning, end, or middle, the process involves changing some pointers to include the new node.

2. **Deletion**: Removing a node is also a matter of adjusting pointers. You disconnect the node from the list, and it will be later cleaned up by the garbage collector.

3. **Traversal**: This operation involves moving through the list from the beginning to the end, usually to perform operations on each node.

4. **Search**: You can look for a specific value within the linked list. This is often done in conjunction with traversal.

![image](https://github.com/ConlanSchool/Linked-Lists/assets/121739541/f8574cc6-1c0e-4cf6-834b-8836487e4655)

## TL;DR

Linked lists are versatile, and dynamic data structures that can effectively overcome the limitations of arrays. Their flexibility in size adjustment, direction of traversal, and the ability to perform various operations makes them an essential tool in data handling.

Thank you for reading.
