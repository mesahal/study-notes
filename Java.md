# Java Learning Sheet

| Topic | Subtopic / Learning Item | Status (To Do / Done) |
|-------|---------------------------|------------------------|
| Java Basics | Introduction to Java, JVM, JDK, JRE differences | |
|  | Installing JDK, Setting Environment Variables, Configuring IDE (IntelliJ/Eclipse/VS Code) | |
|  | Writing and Running First Java Program (Hello World) | |
|  | Java Program Structure (package, class, main method, syntax rules) | |
|  | Java Compilation Process (source → bytecode → execution) (added) | |
|  | JDK Tools – javac, java, jar, javadoc (added) | |
|  | Data Types (Primitive & Non-Primitive) | |
|  | Variables (Local, Instance, Static) | |
|  | Type Casting (Widening vs Narrowing) | |
|  | Operators – Arithmetic & Relational | |
|  | Operators – Logical & Bitwise | |
|  | Operators – Assignment & Unary | |
|  | Input and Output in Java (Scanner, BufferedReader, System.in/out) | |
|  | Java Naming Conventions (Packages, Classes, Methods, Variables, Constants) | |
|  | Java Coding Standards & Best Practices (added) | |
| Control Flow | If-else statements (nested if, else-if ladder) | |
|  | Switch-case (with enums, strings, fall-through concept) | |
|  | Switch Expressions (Java 12+) (added) | |
|  | Loops – for, while, do-while | |
|  | Break and Continue (use cases, labeled break) | |
|  | Enhanced for-loop (iterating arrays & collections) | |
|  | Pattern Matching for instanceof (Java 16+) (added) | |
| OOP Fundamentals | What is OOP & Why it is needed | |
|  | Encapsulation – Concept & Benefits | |
|  | Encapsulation – Writing Getters/Setters in Java | |
|  | Abstraction – Concept (hiding implementation details) | |
|  | Abstraction – Abstract Classes (rules, usage, examples) | |
|  | Abstraction – Interfaces (default, static methods, functional interfaces) | |
|  | Inheritance – Concept & Syntax | |
|  | Inheritance – Method Overriding | |
|  | Inheritance – Multiple Inheritance via Interfaces | |
|  | Polymorphism – Compile-time (Method Overloading) | |
|  | Polymorphism – Runtime (Method Overriding, dynamic dispatch) | |
|  | Polymorphism – Real-world examples | |
|  | Object Cloning: Shallow vs Deep Copy | |
|  | Object Relationships: IS-A (Inheritance) vs HAS-A (Composition/Association) | |
|  | Object Class Methods – toString, equals, hashCode, clone (added) | |
|  | this | |
|  | and | |
|  | super | |
|  | keywords (added) | |
|  | Inner Classes – static, non-static, anonymous (added) | |
|  | Introduction to SOLID & Other Principles (DRY, YAGNI, KISS) | |
|  | OOP Design Principles – Single Responsibility Principle | |
|  | OOP Design Principles – Open/Closed & Liskov Substitution | |
|  | OOP Design Principles – Interface Segregation & Dependency Inversion | |
|  | Coupling & Cohesion | |
| JVM Internals | JVM Architecture Overview | |
|  | Class Loaders – Bootstrap, Extension, Application | |
|  | JVM Memory Areas – Heap, Stack, Metaspace, Code Cache, Native Memory | |
|  | JVM Execution Engine & Bytecode Interpreter | |
|  | JIT Compiler Basics (C1, C2 compilers) | |
|  | JVM Garbage Collection Overview | |
|  | Class File Structure Basics (added) | |
|  | Java Native Interface (JNI) Basics (added) | |
| Advanced Java | Exception Handling – try, catch, finally | |
|  | Exception Handling – Checked vs Unchecked Exceptions | |
|  | Custom Exceptions | |
|  | throw vs throws (breakdown) | |
|  | Try-with-resources & AutoCloseable (breakdown) | |
|  | Exception Best Practices (breakdown) | |
|  | Java Collections – List (ArrayList, LinkedList) | |
|  | Java Collections – Set (HashSet, LinkedHashSet, TreeSet) | |
|  | Java Collections – Map (HashMap, LinkedHashMap, TreeMap, ConcurrentHashMap) | |
|  | ArrayList vs LinkedList performance (breakdown) | |
|  | HashMap Internal Working (breakdown) | |
|  | ConcurrentHashMap Internal Working (breakdown) | |
|  | Fail-fast vs Fail-safe Iterators (breakdown) | |
|  | Generics in Java (Type Parameters, Generic Methods) | |
|  | Generics – Bounded Types & Wildcards (added) | |
|  | Generics – Type Erasure Deep Dive (added) | |
|  | PECS Principle (Producer Extends, Consumer Super) (added) | |
|  | Streams API – Introduction, Intermediate Ops (map, filter, sorted) | |
|  | Streams API – Terminal Ops (collect, reduce, forEach) | |
|  | Parallel Streams (added) | |
|  | Streams API – Custom Collectors (breakdown) | |
|  | Lambda Expressions – Syntax, Scope, Capturing Variables | |
|  | Lambda Expressions – Method References (added) | |
|  | Functional Interfaces – Predicate, Function, Supplier, Consumer | |
|  | Multithreading Basics (Creating Threads, Runnable vs Thread) | |
|  | Synchronization – synchronized keyword, locks, monitors | |
|  | Executor Framework – Thread Pools, Future, Callable | |
|  | Java 8 Date and Time API (LocalDate, LocalDateTime, Instant, ZonedDateTime) (added) | |
|  | Optional API Basics (added) | |
| Java Memory Management | Stack vs Heap Memory | |
|  | Object Creation & Lifetime | |
|  | Java Memory Model (JMM) & Visibility (happens-before rules) | |
|  | References in Java – Strong, Weak, Soft, Phantom | |
|  | Escape Analysis & Object Allocation Optimizations | |
|  | OutOfMemoryError & Common Memory Leaks (added) | |
|  | Tools for Detecting Memory Leaks – MAT (added) | |
| Garbage Collection (GC) | GC Algorithms – Mark & Sweep, Mark & Compact, Copying | |
|  | GC Collectors – Serial, Parallel, CMS, G1, ZGC, Shenandoah, Epsilon | |
|  | GC Tuning Flags & Parameters | |
|  | Generational GC Concepts (added) | |
|  | GC Logs – Reading & Interpreting (added) | |
|  | Stop-the-World Events (STW) | |
|  | Profiling Memory with VisualVM, JConsole, JMC | |
| Concurrency & Multithreading | Thread Lifecycle (new, runnable, waiting, timed waiting, terminated) | |
|  | Thread States & Scheduling | |
|  | Synchronization & Locks (intrinsic, reentrant lock) | |
|  | Semaphore, Mutex (added breakdown) | |
|  | ReentrantReadWriteLock (added) | |
|  | Volatile Keyword & Happens-Before Relationship | |
|  | ThreadLocal for Thread-Specific Data | |
|  | Thread Safety Issues – Race Conditions, Deadlocks | |
|  | Deadlock Detection & Avoidance (added) | |
|  | Executor Framework & Thread Pools | |
|  | Fork/Join Framework | |
|  | Phaser & CountDownLatch (added) | |
|  | Java Virtual Threads (Project Loom) | |
|  | Thread-safe Collections (ConcurrentHashMap, CopyOnWriteArrayList) | |
|  | CompletableFuture for Asynchronous Programming | |
|  | Producer-Consumer Problem (added) | |
| Java Performance Optimization | Profiling Tools – VisualVM, JProfiler, Flight Recorder | |
|  | CPU-bound vs I/O-bound Applications | |
|  | Efficient Data Structures & Algorithms in Java | |
|  | String Performance – String, StringBuilder, StringBuffer | |
|  | String Interning & String Pool (added) | |
|  | Caching Strategies (LRU, Guava Cache, Redis basics) | |
|  | Lazy Initialization & Memoization | |
|  | Reducing Object Creation | |
|  | Escape Analysis Deeper (breakdown) | |
|  | Benchmarking Pitfalls – JIT, Warmup, Dead Code Elimination (added) | |
|  | Using Primitive Collections (Trove, FastUtil) | |
|  | Optimizing Database Access (Batching, Prepared Statements, Indexing) | |
| Java Advanced Features | Generics & Type Erasure | |
|  | Records (Data Carrier Classes) | |
|  | Sealed Classes (Java 17+) (added) | |
|  | Pattern Matching for Switch (Java 17+) (added) | |
|  | Var Keyword (Java 10) (added) | |
|  | Wildcards – Upper Bounded, Lower Bounded | |
|  | Reflection & Metadata Programming | |
|  | Annotations & Custom Annotations | |
|  | Lambda Expressions & Functional Programming in-depth | |
|  | Stream API – Custom Collectors, Parallel Streams | |
|  | Optional API – Avoiding NullPointerException | |
|  | Java I/O – Streams vs Readers/Writers | |
|  | NIO & NIO.2 – Buffers, Channels, File API | |
|  | Serialization & Deserialization (Java Serializable, JSON, XML) | |
|  | Java Cryptography Basics (Hashing, Encryption, Decryption) | |
|  | Internationalization (i18n) & Localization | |
|  | Module System (Java 9+) (added) | |
| JVM Monitoring & Debugging | JStack – Taking & Analyzing Thread Dumps | |
|  | JMap, JInfo, JStat, JHat, jps – Tools Overview | |
|  | Thread Contention & Deadlock Analysis | |
|  | Log Analysis & Structured Logging (SLF4J, Logback, Log4j2) | |
|  | Exception Profiling & Root Cause Analysis | |
|  | Remote Debugging with JDWP (added) | |
|  | Analyzing Heap Dumps (MAT) (added) | |
| Testing & Best Practices | Unit Testing with JUnit 5 – Assertions & Parameterized Tests | |
|  | Mocking with Mockito – Basics & Best Practices | |
|  | Integration Testing – TestContainers, Spring Boot Testing | |
|  | Performance Testing with JMH (Java Microbenchmark Harness) | |
|  | Code Profiling & Refactoring | |
|  | Test Pyramid – Unit, Integration, E2E (added) | |
|  | TDD & BDD – JUnit + Cucumber (added) | |
|  | Mutation Testing – Pitest (added) | |
|  | Code Coverage Tools – Jacoco (added) | |
|  | SOLID Principles & Design Patterns (Singleton, Factory, Observer, Strategy, Builder, Proxy etc.) | |
|  | Design Patterns – Creational (breakdown) | |
|  | Design Patterns – Structural (breakdown) | |
|  | Design Patterns – Behavioral (breakdown) | |
|  | Best Practices for Large-Scale Java Applications (Logging, Exception Handling, Packaging, Modularization) | |
|  | Error Handling Best Practices (added) | |
