# LINKED-LIST-IMPLEMENTATION

COMPANY : CODTECH IT SOLUTIONS

NAME : VASU PATHAK 

INTERN ID : CT04DF1007

DOMAIN : C PROGRAMMING

DURATION : 4 WEEKS

MENTOR NAME : NEELA SANTHOSH KUMAR

Detailed Description:

A linked list is a linear data structure where each element (called a node) contains two parts:

1. Data – to store the value


2. Pointer – to store the address of the next node



Unlike arrays, linked lists are dynamic in nature, meaning they can grow or shrink in size during execution without memory wastage. This makes them highly useful for building efficient data-handling systems.

For this task, I wrote a C program that defines a structure for a node using struct, and uses dynamic memory allocation with malloc() to create new nodes at runtime. The program includes:

Functions for inserting a node at the beginning, end, and a specific position

Functions to delete a node from the beginning, end, and specific position

A traversal function to display the list contents


The program is menu-driven, allowing the user to select operations interactively.



Tools and Support Used:

To complete  this program, I took help from the following platforms:

YouTube: I watched tutorials explaining linked list concepts visually. These helped me understand how pointers link nodes together and how to manage memory without memory leaks.

ChatGPT: Helped me debug issues like pointer errors, segmentation faults, and off-by-one logic mistakes. Also guided me to make the code more modular by separating logic into well-structured functions.

Grok Learning AI: Provided interactive C practice challenges that strengthened my understanding of pointer manipulation and recursion in linked lists.



Applications of Linked List:

Dynamic memory allocation – used in scenarios where the size of data is not known in advance

Implementing stacks, queues, and graphs

Memory-efficient insertion/deletion – better than arrays as no shifting is needed

Undo features in text editors (backtracking through previous states)

Hash tables with chaining – linked lists are used to handle collisions in hash maps

Operating systems – used in job scheduling, memory management, and process handling



Challenges Faced:

Pointer Management: Initially struggled with managing NULL pointers and proper linking of nodes. Fixed them through step-by-step tracing and debugging.

Memory Leaks: At first, I forgot to free memory using free(), which caused memory leaks. ChatGPT helped me integrate proper cleanup functions.

Boundary Conditions: Faced difficulties handling insertions and deletions at invalid or edge-case positions (like empty list, head deletion, etc.).

Traversals: Debugging infinite loops caused by incorrect next pointer assignments helped me improve my logical thinking in data structures.


Conclusion:

This task gave me in-depth practical knowledge about how memory and pointers work in C. It taught me how to create self-growing and self-shrinking data structures that are the foundation of more advanced systems. With the help of YouTube tutorials, ChatGPT support, and Grok AI practice, I was able to implement a clean, modular, and user-friendly linked list program. This has laid a strong foundation for learning more complex data structures like doubly linked lists, trees, and graphs in the future.

OUTPUT
![Image](https://github.com/user-attachments/assets/405421dd-397b-431d-806f-536e744d3da8)
