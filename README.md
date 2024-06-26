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
- Hash Tables (can be considered linear when considering separate chaining or linear probing 
  collision resolution).
- Strings (can be considered as linear sequence of characters)
- Vectors (in certain programming languages like C++)

## Non-Linear Data Structures
- Trees:
      - Binary Trees
      - Binary Search Trees
      - AVL Trees
      - B-Trees
      - Red-Black Trees
      - Trie Trees
      - Splay Trees
      - Segment Trees
      - Fenwick Trees (Binary Indexed Trees)
- Graphs:
      - Directed Graphs
      - Undirected Graphs
      - Weighted Graphs
      - Acyclic Graphs (DAGs)
      - Bipartite Graphs
      - Complete Graphs
      - Sparse Graphs
      - Dense Graphs
      = Connectivity Graphs
- Heaps:
      - Binary Heaps (Min-Heap, Max-Heap)
      - Fibonacci Heaps
- Hash Maps (also known as Hash Tables):
      - Sperate Chaining Hash Tables
      - Linear Probing Hash Tables
      - Quadric Probing Hash Tables
      - Double Hashing
- Graphical Models:
      - Spatial Trees (Quad Trees, Oct Trees)
      - KD-Trees (K-Dimensional Trees)
      - R-Trees (Rectangular or Region Trees)
      - Bounding Volume Hierarchies (BVH)


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



## Hash Tables Simplified:

Imagine a library where each book has a unique code, and there are shelves labeled with those codes. When you want to find a book, you go directly to the shelf labeled with its code, making
the search quick and efficient. That's what a hash table is like.

## Key Points:

- Key-Value Pairs: A hash table stores data in the form of key-value pairs.
  Each key is unique and is associated with a corresponding value.

- Hash Function: It uses a hash function to compute an index(or "hash) for
  each key. This index determines where the key-value pair will be stored
  in the underlying array.

- Fast Access: Retrieving, inserting, or deleting data from a hash table is
  fast, typically with constant time complexity on average (O(1)).

- Collision Handling: Since multiple keys may hash to the same 
  index(collision), hash tables employ collision resolution techniques
  to handle such cases efficiently.

- Dynamic Size: Hash tables can dynamically resize themselves to accommodate
  more key-value pairs as needed, allowing for efficient memory usage.


## Examples:

Suppose you have a hash table storing employee information, where the 
employee ID is the key and the corresponding details (name, department, etc.) are the values. Using a hash function, each employee ID is mapped 
to a specific index in the hash table, making retrieval of employee details
fast.

## Common Operation:

- Insertion: Add a new key-value pair to the hash table.
- Retrieval: Retrieve the value associated with a given key.
- Deletion: Remove a key-value pair from the hash table.
- Update: Modify the value associated with a given key.
- Search: Check if a key exists in the hash table.

## Usage: 

Hash tables are widely used in various applications, including database indexing, caching mechanisms, symbol tables in compilers, implementing associative arrays in programming languages, and storing data in hash-based data structures like sets and maps.



## Strings Simplified:

Imagine a string of beads where each bead represents a character. Strings are sequences of characters, such as letters, numbers, and symbols, arranged in a specific order. They are like words in a sentence or text in a book.

## Key Points:

- Immutable: In many programming languages, strings are immutable, meaning they cannot be changed after they are created. Instead, operations on strings typically create new strings.

- Character Encoding: Strings are typically encoded using a character 
  encoding scheme (e.g. ASCII, UTF-8) that maps characters to numerical
  values for storage and manipulation.

- Operations: Common operations on strings include concatenation (joining   
  two strings together), substring extraction (extracting a portion of a 
  string), and searching for specific characters or substrings.

- Length: The length of a strig refers to the number of characters it contains.

- Indexing: Characters in a string are indexed starting from 0, so you can access individual characters by their index.

  
## Example:

In the string "Hello, World!", each character is a bead in the string of beads. You can access individual characters like "H" at index 0, "e" at index 1, and so on.

## Common Operations:

- Concatenation: Joining two or more strings together.
- Substring Extraction: Extracting a portion of a string.
- Searching: Finding the position of a character or substring within a string.
- Searching: Finding the position of a character or substring within a string.
- Comparison: Comparing two strings to check if they are equal or one comes before the other.


## Usage:

Strings are used extensively in programming for tasks such as text processing, input/output operations, data manipulation, and representing textual data in applications.



## Vectors Simplified:

In programming languages like C++, a vector is a dynamic array that can resize itself automatically as elements are added or removed. It's like having a flexible container that can hold a collection of elements in a specific order.

## Key Pointes:

- Dynamic Size: Unlike traditional arrays, vectors can grow or shrink dynamically, allowing for efficient storage and manipulation of elements.

- Contiguous Memory: Like arrays, elements in a vector are stored in contiguous memory locations, which enables fast random access and iteration.

- Indexed Access: Elements in a vector are accessed using zero-based indexing, similar to arrays.

- Common Operations: Vectors support common operations such as adding elements to the end (push_back), removing elements from the end (pop_back), inserting elements at specific positions, and accessing elements by index.

- Automatic Resizing: When the capacity of a vector is exceeded due to adding new elements, the vector automatically reallocates memory to accommodate more elements.


## Example:

```bash
#include <iostream>
#include <vector>

int main() {
    // Declare a vector of integers
    std::vector<int> numbers;

    // Add elements to the vector
    numbers.push_back(10);
    numbers.push_back(20);
    numbers.push_back(30);

    // Access elements by index
    std::cout << "First element: " << numbers[0] << std::endl;
    std::cout << "Second element: " << numbers[1] << std::endl;

    // Remove the last element
    numbers.pop_back();

    // Print the size of the vector
    std::cout << "Size of the vector: " << numbers.size() << std::endl;

    return 0;
}
```

## Usage:

Vectors are commonly used in C++ and other programming languages for situations where the size of the data structure may change frequently, such as storing a dynamic list of elements, implementing dynamic arrays, and as a more flexible alternative to static arrays.


## Deques Simplified:

A deque (pronounced "deck") is a data structure that allows adding and removing elements from both ends, making it versatile for various applications. Think of it as a double-ended line of people where you can add or remove people from either the front or the back.

## Key Points:

- Double-Ended Operations: You can insert and delete elements from both the front and the back of the deque.
- Dynamic Size: Deque can grow or shrink dynamically as needed.
- Indexed Access: Elements in a deque can be accessed by their index, similar to arrays and vectors.
- Flexible Use: Deques can function as both stacks (LIFO) and queues (FIFO) due to their ability to operate on both ends.

## Example:

In a deque `[A, B, C, D]`, you can perform the following operations:

- Add to the front: `addFront(E)` results in `[E, A, B, C, D]`
- Add to the back: `addBack(F)` results in `[A, B, C, D, F]`
- Remove from the front: `removeFront()` results in `[B, C, D]`
- Remove from the back: `removeBack()` results in `[A, B, C]`

## Common Operations:

- addFront(item): Add an item to the front of the deque.
- addBack(item): Add an item to the back of the deque.
- removeFront(): Remove and return the item from the front of the deque.
- removeBack(): Remove and return the item from the back of the deque.
- peekFront(): View the item at the front without removing it.
- peekBack(): View the item at the back without removing it.
- isEmpty(): Check if the deque is empty.
- size(): Get the number of items in the deque.


## Usage:

Deques are used in various applications such as:

- Implementing both stacks and queues.
- Sliding window problems.
- Managing lists of tasks or jobs where both ends need to be processed.
- Caching algorithms like the Least Recently Used (LRU) cache.


## Example in Python:

```bash
from collections import deque

#create a deque
d = deque()

#Add elements to the deque
d.append('A')   # Add to the back
d.appendleft('B') # Add to the front
d.append('C') # Add to the back

print("Deque after additions: ", d)

#Remove elements from the deque
d.pop()  #remove from the back
d.popleft() #remove from the front

print("Deque after removals: ", d)

```

## Non-Linear Data Structures

## Trees Simplified

Imagine an organizational chart of a company, with the CEO at the top and managers, employees, and interns below in a hierarchical structure. That's what a tree is like in computer science.

## Key Points:

1. Hierarchy: Trees represent a hierarchy with nodes connected in a parent-child relation.
2. Root: The topmost node in a tree is called the root.
3. Nodes: Each element in the tree is called a node.
4. Edges: The connections between nodes are called edges.
5. Leaf Nodes: Nodes without children are called leaf nodes.
6. Subtrees: A node and all its descendants form a subtree.
7. Depth and Height: The depth of a node is the number of edges from the root to the node. The height of a node is the number of edges on the longest path from the node to a leaf.

**Common Type of Tree:**

**1. Binary Trees:**
   -Each node has at most two children, referred to as the left child and the right child.


**Example:**

```plaintext
       A
      / \
     B   C
    / \
   D   E
```

**Explanation:**

- Root: A
- Left child of A: B
- Right child of B: C
- Left child of B: D
- Right child of B: E

**Common Operations:**
- Insertion
- Deletion
- Traversal (in-order, pre-order, post-order)

**2. Binary Search Tree(BST):**
  - A binary tree where the left subtree contains nodes with values less than the parent node, and the right subtree contains nodes with values greater that the parent node.


**Example of a Binary Search Tree (BST):**

```plaintext
       8
      / \
     3   10
    / \    \
   1   6    14
      / \   /
     4   7 13
````

Common Operations:

- Insertion: Add a node to the tree while maintaining the tree's properties.
- Deletion: Remove a node from the tree while maintaining the tree's properties.
- Traversal: Visit all the nodes in a specific order (e.g., in-order, pre-order, post-order, level-order).
- Search: Find a node in the tree.


**3. AVL Trees:**
  - A self-balanced binary search tree where the difference in heights between the left and right subtrees of any nodes is at most one.

**Example:**

```plaintext
       30
      /  \
     20   40
    /  \
   10  25
```

**Explanation:**

- A balanced BST where the heights of the left and right subtrees of any node differ by at most one.
- Self-balancing ensures O(log n) time complexity for insertion, deletions, and lookups.

**Common Operations:**

- Rotations(left and right) to maintain balance.
- Insert, delete, search with balancing.

## 4. B-Trees:

- A balanced tree data structure commonly used in databases and file systems, where each node can have multiple children.


```plaintext
       [10, 20]
      /   |    \
  [5, 7] [15, 17] [25, 30]
```

**Explanation:**

- Multi-way tree used in databases and file systems.
- Each node can contain multiple keys and have multiple children.

**Common Operations:**

- Insert, delete, and search with balancing.
- Nodes split when they exceed maximum capacity.


## 5. Red-Black Trees:

- A self-balancing binary search tree where each node contains an extra bit for denoting the color of the node, either red or black.

**Example:**

```plaintext
       10 (Black)
      /    \
   5 (Red)  15 (Black)
  /  \
3 (Black)  7 (Black)
```

**Explanation:**

- Self-balancing BST with nodes colored red or black.
- Ensures balance with rules to maintain properties (e.g., red nodes cannot have red children).

**Common Operations:**

- Insert, delete with rotations and color flips to maintain balance.
- Search efficiently in O(log n) time.


## 6. Trie Trees (Prefix Trees):

- A tree-like data structure used for storing a dynamic set of strings where the keys are usually strings.

**Example:**

```plaintext
            root
           /  |  \
          t   b   c
         /   / \   \
        r   a   y   a
       /     \
      i       n
     /         \
    e           a
```

**Explanation:**

- Tree used to store strings, with each node representing a character.
- Efficient for prefix searches (e.g., autocomplete).

**Common Operations:**

- Insert, search, and delete words.
- Efficiently finds all words with a given prefix.


## 7. Segment Trees

- A tree used for storing intervals or segments, and allows querying which segments overlap with a given point or interval.

**Example:**
For an array [1, 3, 5, 7, 9, 11]:

```plaintext
                   [36]
                  /    \
             [16]      [20]
            /   \      /   \
          [4]  [12] [16]  [4]
         / \   / \   / \
       [1][3] [5][7] [9][11]
```

**Explanation:**

- Used for range queries and updates.
- Each node represents a segment (range) of the array.

**Common Operations:**

- Build: Construct the tree from an array.
- Query: Find the sum/min/max in a range.
- Update: Modify elements and update the tree.

## 8. Fenwick Trees (Binary Indexed Trees):

- A data structure that provides efficient methods for cumulative frequency tables or cumulative sums.
  
**Example:**

For an array [1, 7, 3, 0, 7, 8, 3, 2, 6, 2]:

```plaintext
  Index:   1  2  3  4  5  6  7  8  9 10
  BIT:    [1, 8, 3, 11, 7, 15, 3, 39, 6, 8]
```

**Explanation:**

- Used for cumulative frequency tables or sums.
- Efficient updates and prefix queries.

**Common Operations:**

- Update: Add a value to an element.
- Query: Get the prefix sum up to a certain index.


## Graph Simplified:

Imagine a map of cities connected by roads. Each city is a node, and each road connecting the cities is an edge. That's what a graph is like in Computer science.

**Key Points:**

- Vertices (Nodes): The points in a graph.
- Edges: The connections between the vertices.
- Directed vs. Undirected Graphs: In a directed graph, edges have a direction (like a one-way street). In an undirected graph, edges have no direction (like a two-way street).
- Weighted vs Unweighted Graphs: In a weighted graph, edges have weight (e.g., distance or cost). In an unweighted graph, all edges are considered equal.
- Adjacency List: A way to represent a graph where each vertex has a list of the vertices it is connected to.
- Adjacency Matrix: A way to represent a graph using a 2D array.

## Types of Graphs:

**1. Undirected Graphs**

**Example**

```plaintext
A -- B
|    |
C -- D
```
**Explanation:**

- Vertices: A, B, C, D
- Edges: (A-B), (A, C), (B-D), (C-D)

Code Example using Adjacency List:

```cpp
#include <iostream>
#include <unordered_map>
#include <vector>
using namespace std;

class Graph {
public:
    void addEdge(const string& u, const string& v) {
        graph[u].push_back(v);
        graph[v].push_back(u);
    }

    void printGraph() {
        for (const auto& node : graph) {
            cout << node.first << " -> ";
            for (const auto& neighbor : node.second) {
                cout << neighbor << " ";
            }
            cout << endl;
        }
    }

private:
    unordered_map<string, vector<string>> graph;
};

int main() {
    Graph g;
    g.addEdge("A", "B");
    g.addEdge("A", "C");
    g.addEdge("B", "D");
    g.addEdge("C", "D");

    cout << "Undirected Graph:\n";
    g.printGraph();
    return 0;
}

```
**2. Directed Graphs**

**Example:**

```plaintext
A → B
↓
C → D
```

**Explanation:**

- Vertices: A, B, C, D
- Edges: (A->B), (A->C), (C->D)

**Example using adjacency list:**

```cpp
#include <iostream>
#include <unordered_map>
#include <vector>
using namespace std;

class DirectedGraph {
public:
    void addEdge(const string& u, const string& v) {
        graph[u].push_back(v);
    }

    void printGraph() {
        for (const auto& node : graph) {
            cout << node.first << " -> ";
            for (const auto& neighbor : node.second) {
                cout << neighbor << " ";
            }
            cout << std::endl;
        }
    }

private:
    unordered_map<string, vector<string>> graph;
};

int main() {
    DirectedGraph dg;
    dg.addEdge("A", "B");
    dg.addEdge("A", "C");
    dg.addEdge("C", "D");

    cout << "Directed Graph:\n";
    dg.printGraph();
    return 0;
}

```


## 3. Weighted Graphs

**Example:**

```plaintext
     4
A -------- B
|        / |
|       /  |
5      1   3
|     /    |
|    /     |
C -------- D
     2
```

**Explanation:**
- Vertices: A, B, C, D
- Edges with weights: (A-B, 4), (A-C, 5), (B-D, 3), (B-C, 1), (C-D, 2)

**Example using adjacency list:**

```cpp
#include <iostream>
#include <unordered_map>
#include <vector>
#include <utility> // for pair
using namespace std;

class WeightedGraph {
public:
    void addEdge(const string& u, const string& v, int weight) {
        graph[u].emplace_back(v, weight);
        graph[v].emplace_back(u, weight);
    }

    void printGraph() {
        for (const auto& node : graph) {
            cout << node.first << " -> ";
            for (const auto& neighbor : node.second) {
                cout << neighbor.first << " (weight " << neighbor.second << ") ";
            }
            cout << endl;
        }
    }

private:
    unordered_map<std::string, vector<std::pair<string, int>>> graph;
};

int main() {
    WeightedGraph wg;
    wg.addEdge("A", "B", 4);
    wg.addEdge("A", "C", 5);
    wg.addEdge("B", "D", 3);
    wg.addEdge("B", "C", 1);
    wg.addEdge("C", "D", 2);

    cout << "Weighted Graph:\n";
    wg.printGraph();
    return 0;
}

```

## 4. Cyclic vs. Acyclic Graphs

**Cyclic Graph Example:**

```plaintext
A → B → C
↑     ↓
← ← D
```

**Explanation:**
- This graph contains a cycle (A->B->C->D->A).


**Acyclic Graph Example:**

```plaintext
A → B → C
↓
D
```

**Explanation:**

- This graph does not contain any cycles.

**Example for Detecting Cycles:**

```cpp
#include <iostream>
#include <unordered_map>
#include <vector>
#include <algorithm> // for fill

class GraphCycle {
public:
    GraphCycle(int vertices) : V(vertices) {}

    void addEdge(int u, int v) {
        graph[u].push_back(v);
    }

    bool isCyclic() {
        vector<bool> visited(V, false);
        vector<bool> recStack(V, false);

        for (int node = 0; node < V; ++node) {
            if (!visited[node] && isCyclicUtil(node, visited, recStack)) {
                return true;
            }
        }
        return false;
    }

private:
    int V;
    unordered_map<int, std::vector<int>> graph;

    bool isCyclicUtil(int v, vector<bool>& visited, vector<bool>& recStack) {
        if (!visited[v]) {
            visited[v] = true;
            recStack[v] = true;

            for (int neighbor : graph[v]) {
                if (!visited[neighbor] && isCyclicUtil(neighbor, visited, recStack)) {
                    return true;
                } else if (recStack[neighbor]) {
                    return true;
                }
            }
        }
        recStack[v] = false;
        return false;
    }
};

int main() {
    GraphCycle gc(4);
    gc.addEdge(0, 1);
    gc.addEdge(1, 2);
    gc.addEdge(2, 0);
    gc.addEdge(2, 3);

    if (gc.isCyclic()) {
        cout << "Graph has a cycle\n";
    } else {
        cout << "Graph has no cycle\n";
    }

    return 0;
}

```



## Heaps Simplified:

Imagine a binary tree where the highest (or lowest) priority element is always the root. This structure is known as a heap.

## Key Points:

- **Binary Heap**: A complete binary tree where each parent node is either greater than or equal to (max-heap) or less than or equal to (min-heap) its children.
- **Heap Property**: In a max heap, the key at the parent node is greater than or equal to the keys of its children, and the highest key is at the root. In a min heap, the key at the parent node is less than or equal to the keys of its children, and the lowest key is at the root.
- **Complete Binary Tree**: All levels of the tree are fully filled except possibly for the last level which is filled from left to right.



## Types of Heaps:

**1. Max Heap**

**Example:**

```plaintext
       10
      /  \
     9    8
    / \  / \
   7  6 5  4
```

**Explanation:**

- The root node has the highest value.
- Every parent node is greater than or equal to its children.


**Common Operation:**

- Insertion: Add the new element at the end and then heapify up.
- Deletion (Extract Max): Remove the root and replace it with the last element, then heapify down.
- Heapify: Adjust the heap to maintain the heap property.


**Example for Max Heap:**

```cpp
#include <iostream>
#include <vector>
#include <algorithm>

class MaxHeap {
private:
    std::vector<int> heap;

    void heapifyUp(int index) {
        if (index && heap[parent(index)] < heap[index]) {
            std::swap(heap[index], heap[parent(index)]);
            heapifyUp(parent(index));
        }
    }

    void heapifyDown(int index) {
        int left = leftChild(index);
        int right = rightChild(index);
        int largest = index;

        if (left < size() && heap[left] > heap[largest])
            largest = left;
        if (right < size() && heap[right] > heap[largest])
            largest = right;

        if (largest != index) {
            std::swap(heap[index], heap[largest]);
            heapifyDown(largest);
        }
    }

    int parent(int i) { return (i - 1) / 2; }
    int leftChild(int i) { return (2 * i + 1); }
    int rightChild(int i) { return (2 * i + 2); }

public:
    int size() { return heap.size(); }
    bool empty() { return size() == 0; }

    void insert(int key) {
        heap.push_back(key);
        int index = size() - 1;
        heapifyUp(index);
    }

    void removeMax() {
        if (size()) {
            heap[0] = heap.back();
            heap.pop_back();
            heapifyDown(0);
        }
    }

    int getMax() {
        if (size()) return heap.front();
        return -1; // or some error value
    }

    void printHeap() {
        for (int i : heap) {
            std::cout << i << " ";
        }
        std::cout << std::endl;
    }
};

int main() {
    MaxHeap maxHeap;
    maxHeap.insert(10);
    maxHeap.insert(9);
    maxHeap.insert(8);
    maxHeap.insert(7);
    maxHeap.insert(6);
    maxHeap.insert(5);
    maxHeap.insert(4);

    std::cout << "Max Heap:" << std::endl;
    maxHeap.printHeap();

    std::cout << "Maximum value: " << maxHeap.getMax() << std::endl;

    maxHeap.removeMax();
    std::cout << "After removing max:" << std::endl;
    maxHeap.printHeap();

    return 0;
}
```

## 2. Min heap

**Example:**

```plaintext
       4
      /  \
     5    8
    / \  / \
   6  7 9  10
```

**Explanation:**

- The root node has the lowest value.
- Every parent node is less than or equal to its children.


**Common Operations:**

- Insertion: Add the new element at the end and then heapify up.
- Deletion (Extract Min): Remove the root and replace it with the last element, then heapify down.
- Heapify: Adjust the heap to maintain the heap property.


**Example for Min heap:**

```cpp
#include <iostream>
#include <vector>
#include <algorithm>

class MinHeap {
private:
    std::vector<int> heap;

    void heapifyUp(int index) {
        if (index && heap[parent(index)] > heap[index]) {
            std::swap(heap[index], heap[parent(index)]);
            heapifyUp(parent(index));
        }
    }

    void heapifyDown(int index) {
        int left = leftChild(index);
        int right = rightChild(index);
        int smallest = index;

        if (left < size() && heap[left] < heap[smallest])
            smallest = left;
        if (right < size() && heap[right] < heap[smallest])
            smallest = right;

        if (smallest != index) {
            std::swap(heap[index], heap[smallest]);
            heapifyDown(smallest);
        }
    }

    int parent(int i) { return (i - 1) / 2; }
    int leftChild(int i) { return (2 * i + 1); }
    int rightChild(int i) { return (2 * i + 2); }

public:
    int size() { return heap.size(); }
    bool empty() { return size() == 0; }

    void insert(int key) {
        heap.push_back(key);
        int index = size() - 1;
        heapifyUp(index);
    }

    void removeMin() {
        if (size()) {
            heap[0] = heap.back();
            heap.pop_back();
            heapifyDown(0);
        }
    }

    int getMin() {
        if (size()) return heap.front();
        return -1; // or some error value
    }

    void printHeap() {
        for (int i : heap) {
            std::cout << i << " ";
        }
        std::cout << std::endl;
    }
};

int main() {
    MinHeap minHeap;
    minHeap.insert(4);
    minHeap.insert(5);
    minHeap.insert(8);
    minHeap.insert(6);
    minHeap.insert(7);
    minHeap.insert(9);
    minHeap.insert(10);

    std::cout << "Min Heap:" << std::endl;
    minHeap.printHeap();

    std::cout << "Minimum value: " << minHeap.getMin() << std::endl;

    minHeap.removeMin();
    std::cout << "After removing min:" << std::endl;
    minHeap.printHeap();

    return 0;
}
```

Heaps are powerful data structures used to maintain a priority queue. They ensure that the highest (or lowest) priority element is always accessible in constant time. By understanding and implementing heaps, you can efficiently manage priority data.
