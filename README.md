Data Structures
1. Arrays - collection of items stored at contagious memory locations.
    Built-in almost all of the programming languages. Used to implement list ADT as it is simple to construct handle a collection of items. Compact Arrays are arrays that have no gap, ie  if there are N items in the array (that has size M, where M ≥ N), then only index [0..N-1] are occupied and other indices [N..M-1] should remain empty. 
    Operations in Arrays include: get, search, insert, remove. the time complexity of the operations in the best case is 0(1) and in the worst case is 0(n). The size of the compact array is not infinite but a finite number.
    Need for Arrays include: Storing mulitple values, Processing many values easily and quickly and efficiently sorting and searching.
    Declaring an array: name, have same data type and its length. Example: let numbers = [1, 2, 3];

2. Linked Lists - Data Structure consisting of a group of vertices (nodes) which together represent a sequence.
    Dynamic data structure that allows for constant time insertion and removal at any point in the linked list. used to implement list, stack, Queue, and Deque ADTs.
    Operations in Linked Lists include: get, insert, remove, search, the time complexity of the operations in the best case is 0(1) while in the worst case is 0(n).
    It uses pointers/references to allow items/data to be non-contiguous in memory (that is the main difference with a simple array). The items are ordered from index 0 to index N-1 by associating item i with its neighbour item i+1 through a pointer. 
    Example: Linked List [22 (head)->2->77->6->43->76->89 (tail)].The head pointer points to a0 — it is 22, nothing points to the head item, The current number of elements N in the Linked List — N = 7 elements. The tail pointer points to aN-1 — it is a6 = 89, nothing is after the tail item.
    Examples of Linked List; singly, doubly, circular and circular-doubly linked lists.

3. Stack
    It is a particular kind of Abstract Data Type in which the main operations on the collection are the addition of an item to the collection, known as push, only to the top of the stack and removal of an item, known as pop, only from the top of the stack. 
    It is known as Last-In-First-Out (LIFO) data structure.
    Operations in Stack include: insert (push), remove (pop) and peek. All the operations are 0(1).
    Its applications iclude: Bracket matching, redo and undo button and postfix calculator. 

4. Queue - It is a Abstract Data Type in which the items in the collection are kept in order.
    The main operations on the collection are the addition of items to the back position (enqueue) and removal of items from the front position (dequeue).
    It is known as First-In-First-Out (FIFO) data structure as the first item to be enqueued will eventually be the first item to be dequeued, as in real life queues.

5. Hash tables - Store key and value pairs in a memory efficient way using the hash function. 
    Translates keys into numerical indices located within a fixed block of memory. Mostly used for associative arrays, database indexing, caches and sets. Operations include; search, insert, remove. 
    Properties of a good hash function: fast to compute, use minimum slots, scatter the keys into different base addresses and minimum collisions as possible. To solve collision we can use the open addressing and separate chaining methods. The open addressing method include linear probing, Quadratic probing and double hashing.