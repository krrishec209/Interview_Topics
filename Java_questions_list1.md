Java Interview preparation
------------------------------
Java
-------
1. class loader
 - class loader are part of jre that is reponsible for loading classes into memory.

2. Garbage collection 
3. WeakReference, SoftReference, PhantomReference
4. HashMap vs WeakHashMap
5. String
 String constant pool
6. StringBuffer vs StringBuilder
 - Both StringBuffer and StringBuilder is mutable
 - StringBuffer is thread-safe because of synchronization
 - StringBuilder is not thread-safe. It provides better performance because there is no synchronization overhead.

7. Array vs Collection
8. ArrayList vs LinkedList

9. How to make list thread-safe
 - Collections.SynchronizedList(list);
 - CopyOnWriteArrayList(); //this is also thread-safe but it uses copy on write algorithm 

10. Queue
 - In java queue is an interface which extends collection
 - queue follows FIFO principle
 - LinkedList, ArrayDeque
 - PriorityQueue

11. Set 
 - set doesn't allow duplicates
 - HashSet, LinkedHashSet, TreeSet

12. Map
 - map is used to hold key-value pair
 - HashMap, LinkedHashMap, TreeMap

13. Internal working of hashmap
14. Serialization, deserialization

15. Comparator vs Comparable
 - comparable is used for natural sorting order
 - comparator is used for custom sorting order

16. Fail-fast vs fail-safe
 - fail-fast means iterator throws ConcurrentModificationException 
 if structure is modified while iterating over it - (ArrayList, LinkedList)
 - fail-safe means iterator doesnot throw exception if structure is modified while iterating over it
 eg: CopyOnWriteArrayList(), ConcurrentHashMap()

17. Multithreading in java
 - Thread class
 - Runnable interface

 inter-thread communication
 wait(),notify(), notifyAll() methods
 
 sleep,join methods
 User thread vs Daemon thread
 Runnable vs Callable interfaces

18. Synchronization vs Concurrency
19. Thread pool

20. shutdown hook
 - shutdown hooks are executed before program exits
 - Runtime.addShutdownHook(Thread t);

21. Executor framework
 - ExecutorService is a framework provided by Java's 
 java.util.concurrent package that simplifies thread management and execution. It provides 
 thread pooling and asynchronous execution of tasks, improving performance and resource utilization.

22. Design patterns
 - Creational pattern
 - Structural pattern
 - Behavioral pattern


23. java 8 features
 - Stream api 
 - functional interfaces
 - lambda expressions
 - Method references
 - static and default method in interfaces
 - Date and time api
 - Optional class

24. Object oriented principles
 - Abstraction
 - Encapsulation
 - Polymorphism

25. Exception handling

26. Inheritance, abstract class and interfaces 
27. super, this, transient and volatile keywords
28. File handling (I/O)
