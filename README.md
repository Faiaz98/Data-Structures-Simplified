# Data-Structures-Simplified

This repository aims to make data structures more simplified and easy to understand, especially for beginners or anyone new to the topic. It's also a personal project for me to learn and master the core principles of data structures.

## Types of Data Structures
- Linear Data Structures
- Non-Linear Data Structures

## Linear Data Structures
- Arrays
- Linked Lists
- Stacks
- Queue

## Non-Linear Data Structures
- Trees
- Graphs
- Hash Tables
- Heaps

## Arrays Simplified:

An array is like a row of boxes where you can store items. Each box has a number called an index. Think of it as a line of mailboxes in an apartment building.

## Key Points:

- Fixed Size: Arrays have a fixed size, meaning you decide how many boxes (or elements) there will
  be when you create it.
- Indexed: Each box in the array has an index starting from 0. This helps you find and access items
  quickly.
- Homogeneous: All the items in an array must be of the same data types, like all letters,     
  numbers, or objects.
- Contiguous Memory: The items are stored one after another in memory, which allows for fast 
  access to any element using its index.

## Example:

Let's say you have an array of numbers: `[3, 8, 12, 5, 9]`.
- Index 0: 3
- Index 1: 8
- Index 2: 12
- Index 3: 5
- Index 4: 9

You can access the numbers by specifying their index, like `array[2]` to get `12`.

## Common Operations:
- Access: Get the value at a specific index.
- Insertion: Add a new item at a particular position.
- Deletion: Remove an item from a specific position.
- Update: Change the value at a certain index.

## Usage:

Array are used in various algorithms, data storage, and representing mathematical concepts.



## Linked List Simplified:

Imagine a chain of connected blocks. Each block holds a piece of information and points to the next block in the chain, forming a sequence. That's what a linked list is like.

## Key Points:

- Nodes: Each block in the linked list is called a "node". It contains both data and a reference
  (or pointer) to the next node in the sequence.
- Dynamic Size: Unlike arrays, linked lists can grow or shrink dynamically because each node points
  to the next one,
- No Contiguous Memory: Nodes can be scattered in memory, not necessarily next to each other.
- Types:
     - Singly Linked Lists: Each node points to the next one in the sequence. It's like a chain
       where you can only move forward.
     - Doubly Linked Lists: Each node points to both the next and previous nodes. It's like a path
       with signs pointing both forward and backward.
     - Circular Linked Lists: The last node points back to the first one, forming a loop, it's like
       a loop where you can keep going around and around.

## Examples:

- Singly Linked List: In `[A -> B -> C -> D]`, each element (A, B, C, D) is a node containing a      letter and a pointer to the next node.
- Doubly Linked List: In `[A <-> B <-> C <-> D]`, each element (A, B, C, D) is a node containing
  a letter and pointers to both the next and previous nodes.
- Circular Linked List: In `[A -> B -> C -> D -> A]`, each element (A, B, C, D) is a node   
  containing a letter and a pointer to the next node, with the last node pointing back to the
  first one.

## Common Operations: 

- **Insertion**: Add a new node at the beginning, end, or middle of the list.
- **Deletion**: Remove a node from the list.
- **Traversal**: Visit each node in the list sequentially.
- **Search**: Look for a specific node in the list.

## Usage:

Linked lists are used in situations where dynamic size and efficient insertion and deletion operations are required, such as implementing stacks, queues, and hash tables.

## Stacks Simplified:

Imagine a stack of books where you can only add or remove books from the top. That's what a 
stack is like in programming.

## Key Points:

- **LIFO(Last In, First Out)**: The last item added to the stack is the first one to be removed.    It's like a stack of plates where you take the top one first.
- **Operations**: Stacks support two main operations:
      - **Push**: Add an item to the top of the stack.
      - **Pop**: Remove the item from the top of the stack.

- **Types**:
      
    - **Array-based Stack**: Implement using arrays, providing fast access but with a fixed size.
    - **Linked List-based Stack**: Implement using linked lists, allowing dynamic size but 
      slightly slower access.

## Example:

- Array-based Stack: imagine a stack `[5, 8, 12]`. If you push 3 onto the stack, it becomes
  `[5, 8, 12, 3]`. If you pop, you'll get 3 removed from the top.

- Linked List-based Stack: Imagine a stack with elements A->B->C. If you push D onto the stack,
  it becomes D->A->B->C. If you pop, you'll get D removed from the top.


## Common Operations:

- Push: Add an item to the top of the stack.
- Pop: Remove the item from the top of the stack.
- Peek: View the item at the top of the stack without removing it.
- Check Empty: Determine if the stack is empty.
- Check Full (for array-based stacks): Determine if the stack is full.

## Usage:

Stacks are used in various algorithms and applications, such as managing function calls in 
programming language, implementing undo functionality in text editors, and parsing expressions
in compilers.



## Queues Simplified:

Imagine a line of people waiting for a roller coaster ride. The person who gets in line first
is the first one to get on the ride. That's what a queue is like in programming.

## Key Points:

- FIFO(First In, First Out); the first item added to the queue is the first one to be removed.
  It's like waiting in line at a grocery store.
- Operations: Queues support two main operations:
      - Enqueue: Add an item to the back of the queue.
      - Dequeue: Remove the item from the front of the queue.

## Types:

- Array-based Queue: Implemented using arrays, providing fast access but with a fixed size.
- Linked-List Queue: Implemented using linked lists, allowing dynamic size but with slightly
  slower access.


## Examples:

- Array-based Queue: Imagine a queue `[5, 8, 12]`. If you enqueue 3 into the queue, it becomes
  `[5, 8, 12, 3]`. If you dequeue, you'll get 5 removed from the front.
- Linked List-based Queue: Imagine a queue with elements A->B->C. If you enqueue D into the queue,
  it becomes A->B->C->D. If you dequeue, you'll get A removed from the front.


## Common Operations:

- Enqueue: Add an item to the back of the queue.
- Dequeue: Remove the item from the front of the queue.
- Peek: View the item at the front of the queue without removing it.
- Check Empty: Determine if the queue is empty.
- Check Full(for array-based queues): Determine if the queue is full.


## Usage:

Queues are used in various scenarios, such as managing tasks in a computer operating system(e.g.,
CPU scheduling), handling requests in network protocols, and implementing breadth-first search in graph algorithms.
