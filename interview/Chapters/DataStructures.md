## Chapter 1 :  Data Structures

Data structures are foundational in computer science and are pivotal in coding interviews. For this chapter, we will cover data structures, their importance and use in programming, and the how to levargage the knowledge in programming. [What is a data structure](https://www.geeksforgeeks.org/data-structures/) A data structure is a storage that is used to store and organize data. It is a way of arranging data on a computer so that it can be accessed and updated efficiently.

## 1.1 Arrays

[What is an Array?](https://www.geeksforgeeks.org/what-is-array/) An array is a collection of items of same data type stored at contiguous memory locations. Arrays are the simplest and most widely used data structures in computer programming. An array is a collection of elements, each identified by an array index or key. These elements are stored at contiguous memory locations, which makes accessing them very efficient. Arrays are fundamental in understanding how data is stored and manipulated in memory.

Arrays are used in almost every aspect of programming and serve as the basis for more complex data structures. They are especially useful in situations where we need to store a list of elements that we want to access randomly or sequentially. Understanding arrays is crucial for grasping concepts like memory management and algorithm optimization.

#### Deep dive
- [Data Structures 101: Arrays — A Visual Introduction for Beginners](https://www.freecodecamp.org/news/data-structures-101-arrays-a-visual-introduction-for-beginners-7f013bcc355a/) 

- [Khan Academy - Arrays](https://www.khanacademy.org/computing/computer-programming/programming/arrays/pt/intro-to-arrays)

### 1.2 Linked List

Linked lists are a step up from arrays in terms of complexity. They are a linear data structure consisting of a sequence of elements, each linked to the next. Unlike arrays, the elements in a linked list, known as nodes, are not stored in contiguous memory locations. Each node contains a reference to the next node in the sequence.

This structure allows for efficient insertion and removal of elements from any position in the list, as these operations do not require the data structure to be reorganized. Linked lists are crucial for understanding more complex data structures like trees and graphs and are often used in scenarios where arrays are not efficient.

#### Deep dive
- [How Does a Linked List Work? A Beginner's Guide to Linked Lists](https://www.freecodecamp.org/news/how-linked-lists-work/)

- [Linked Lists](https://www.youtube.com/watch?v=R9PTBwOzceo)

### 1.3 Trees

Trees are a type of data structure that store elements in a hierarchical manner. They are non-linear and consist of nodes connected by edges. The topmost node is known as the root, and each node can have zero or more child nodes. Trees are particularly useful in scenarios where data naturally forms a hierarchy.

Trees are used in various applications such as database management, file system organization, and in managing hierarchical data. They are also fundamental in various algorithms and are a key component of data structures like sets and maps.


#### Deep dive

- [Everything you need to know about tree data structures](https://www.freecodecamp.org/news/all-you-need-to-know-about-tree-data-structures-bceacb85490c/)

- [Data structures: Introduction to Trees](https://www.youtube.com/watch?v=qH6yxkw0u78)

### 1.4 Graphs

Graphs are used to represent relationships between pairs of objects. A graph consists of nodes (or vertices) and edges (connections between nodes). They are key in solving complex, real-world problems that involve modeling networks, like social networks, computer networks, and transportation systems.

Graphs can be either directed or undirected and can include weights on their edges. They are a cornerstone in computer science, with applications in various algorithms, from finding the shortest path in a network to analyzing social networks.


#### Deep dive

- [How to think in graphs: An illustrative introduction to Graph Theory and its applications](https://www.freecodecamp.org/news/i-dont-understand-graph-theory-1c96572a1401/)

- [Khan Academy - Graph Representation](https://www.khanacademy.org/computing/computer-science/algorithms/graph-representation/a/describing-graphs)

### 1.5 Stacks and Queues

Stacks and queues are fundamental data structures used in almost every aspect of computer programming. A stack is a collection of elements that follows the Last In, First Out (LIFO) principle. In contrast, a queue is a collection of elements that follows the First In, First Out (FIFO) principle.

These structures are used in various algorithmic processes, such as managing the execution of function calls (stack) and handling asynchronous data (queues). Understanding these concepts is vital for grasping more complex data structures and algorithms.

#### Deep dive

- [Data Structures 101: Stacks](https://www.freecodecamp.org/news/data-structures-101-stacks-696b3282980/)

- [Introduction to Stacks and Queues (Data Structures & Algorithms #12)](https://www.youtube.com/watch?v=A3ZUpyrnCbM)

- [Queue - Data Structure](https://devopedia.org/queue-data-structure)

### 1.6 Hash Tables

Hash tables, also known as hash maps, are a type of data structure that provides efficient data retrieval through key-value pair mappings. They are designed to optimize searching, insertion, and deletion operations, all of which can, ideally, be performed in constant time, i.e., O(1) complexity. This efficiency is achieved through a hashing function that maps keys to specific locations in the table.

The concept of hashing and hash tables is fundamental in computer science and is widely used in various applications. For instance, they are the backbone of data structures like sets and maps in many programming languages, and they are used in database indexing, caching, and in implementing associative arrays.

Understanding hash tables is crucial for any software developer, as they are a key tool for designing efficient algorithms and data storage mechanisms. Hash tables help in handling large sets of data, where quick access is essential. They are particularly useful in situations where direct indexing of data is not feasible.

#### Deep dive

- [Hash Table Data Structure | Illustrated Data Structures](https://www.youtube.com/watch?v=jalSiaIi8j4)

- [Hash Tables | What, Why & How to Use Them](https://khalilstemmler.com/blogs/data-structures-algorithms/hash-tables/)

## Coding Challenges

Once you are done covering the above, you can practice what you've learnt here

Practice these :

- [Hacker Rank Data Structure Challenges](https://www.hackerrank.com/domains/data-structures)

- [Code Wars Data Structure Challenges](https://www.codewars.com/collections/data-structures)