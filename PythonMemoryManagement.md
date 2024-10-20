Python Memory Management:

Mempry management in Python involves a combination of automatic garbage collection, reference counting and various internal optimizations to effieciently mannage memory allocation and deallocation. Understanding these mechanisms can help developers write more efficient and robust applications.

1. Key Concepts in Python Memory Management.
2. Memory Allocation and Deallocation
3. Reference Counting
4. Garbage Collection
5. The GC Module
6. Memory Management Best Practices.

##### Reference Counting :
Reference counting is the primary method python uses to manage memory. Each object in python maintains a count of references pointing to it. When the reference count drops to zero, the memory occupied by the object is deallocated.

###### Garbage collection :
Python includes a cyclic garbage collector to handle reference cycles. Reference cycles occur when objects referebce each other, preventing thier refereence counts from reachig zero.




