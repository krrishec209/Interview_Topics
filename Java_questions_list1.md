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


*********************

As a Java developer, 

Please learn:

1. Core Java Mastery
- OOP principles (SOLID, DRY, KISS)
- Generics, Lambda expressions, Functional interfaces
- Java Streams API (map/reduce, collectors)
- Java Collections framework
- Java Reflection API
- Exception handling

2. Multithreading & Concurrency
- Thread synchronization, Executors, Locks
- Fork/Join framework
- Understanding of race conditions, deadlocks, and thread pools
- Concurrency utilities (java.util.concurrent)

3. Design Patterns & Architecture
- Common design patterns (Singleton, Factory, Builder)
- Architectural patterns (MVC, - Microservices, Event-Driven Architecture)
- Dependency Injection (DI), Inversion of Control (IoC)

4. Java Memory Management
- Garbage Collection (G1, CMS, ZGC)
- JVM heap and stack management
- Profiling tools (JProfiler, VisualVM)
- Analyzing memory leaks, thread dumps, and heap dumps

5. Classloaders and Reflection
- Custom class loaders
- Dynamic class loading
- Reflection for runtime behavior manipulation

6. Spring Framework & Spring Boot
- Spring Core (Dependency Injection, AOP)
- Spring Boot (Auto-configuration, Microservices support)
- Spring Security (OAuth2, JWT)
- Spring Data (JPA, Hibernate integration)
- Spring Cloud (Netflix OSS, Circuit Breakers)

7. Microservices Architecture
- Service discovery (Eureka, Consul)
- Load balancing, distributed tracing, and circuit breaking
- API Gateway (Zuul, NGINX)
- Asynchronous communication with Kafka, RabbitMQ

8. RESTful Web Services
- REST principles, building APIs
- JSON/XML handling
- API versioning, OpenAPI/Swagger documentation

9. Java I/O and NIO
- Blocking vs non-blocking I/O (NIO)
- Asynchronous I/O, channels, selectors
- File handling, serialization and deserialization

10. Reactive Programming
- Project Reactor, RxJava
- Event-driven architecture, backpressure
- Reactive streams, non-blocking IO

11. JPA/Hibernate
- ORM principles, entity relationships
- Lazy vs eager loading
- Caching strategies, query optimization

12. Database Optimization
- SQL optimization, indexing, and transactions
- NoSQL databases (MongoDB, Cassandra)
- ACID principles, CAP theorem

13. Distributed Systems
- Consistency, availability, partitioning (CAP)
- Event sourcing, CQRS (Command Query Responsibility Segregation)
- Distributed caching (Redis, Hazelcast)
- Tools: Apache ZooKeeper, Consul, etcd

14. Testing & TDD/BDD
- Unit testing (JUnit, Mockito)
- Integration and functional testing
- Behavior-driven development (Cucumber)

15. CI/CD & DevOps
- Continuous integration (Jenkins, CircleCI)
- Containerization with Docker
- Orchestration with Kubernetes
- Source control (Git), versioning, branching strategies

16. Performance Tuning & Optimization
- JVM tuning, garbage collection optimization
-Tools for profiling and monitoring (Prometheus, Grafana)

𝗝𝗼𝗶𝗻 𝗺𝘆 𝘁𝗲𝗹𝗲𝗴𝗿𝗮𝗺 𝗰𝗵𝗮𝗻𝗻𝗲𝗹 - https://t.me/rani_dhage1
𝗝𝗼𝗶𝗻 𝗺𝘆 𝗪𝗵𝗮𝘁𝘀𝗔𝗽𝗽 𝗖𝗵𝗮𝗻𝗻𝗲𝗹 - ‎https://lnkd.in/dGiTMANS

#1. "Domain Knowledge" (example: FinTech)
#2. Oracle Certified Associate, Java SE 8 Programmer
#3. Oracle Certified Professional, Java SE 8 Programmer Certification 
#4. MySQL
#5. Java Data Access

https://www.linkedin.com/posts/rani-dhage_java-coding-backend-activity-7265331164955955200--CdN?utm_source=share&utm_medium=member_desktop&rcm=ACoAAARSzbgBGEbWHnTkxyPnkFaeZcnK-pW0lqg
