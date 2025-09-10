# Java Learning Sheet

## 🟢 BEGINNER LEVEL

| Topic | Subtopic / Learning Item | Status (To Do / Done) |
|-------|---------------------------|------------------------|
| **Java Basics** | Introduction to Java, JVM, JDK, JRE differences | |
|  | Installing JDK, Setting Environment Variables, Configuring IDE (IntelliJ/Eclipse/VS Code) | |
|  | Writing and Running First Java Program (Hello World) | |
|  | Java Program Structure (package, class, main method, syntax rules) | |
|  | Java Compilation Process (source → bytecode → execution) | |
|  | JDK Tools – javac, java, jar, javadoc | |
|  | Data Types (Primitive & Non-Primitive) | |
|  | Primitive Data Types – byte, short, int, long, float, double, char, boolean | |
|  | Non-Primitive Data Types – String, Arrays, Classes, Interfaces | |
|  | Variables (Local, Instance, Static) | |
|  | Variable Scope and Lifetime | |
|  | Type Casting (Widening vs Narrowing) | |
|  | Implicit vs Explicit Type Casting | |
|  | Operators – Arithmetic & Relational | |
|  | Operators – Logical & Bitwise | |
|  | Operators – Assignment & Unary | |
|  | Operator Precedence and Associativity | |
|  | Input and Output in Java (Scanner, BufferedReader, System.in/out) | |
|  | Console Input/Output Methods | |
|  | File Input/Output Basics | |
|  | Java Naming Conventions (Packages, Classes, Methods, Variables, Constants) | |
|  | Java Coding Standards & Best Practices | |
|  | Code Documentation with JavaDoc | |
| **Control Flow** | If-else statements (nested if, else-if ladder) | |
|  | Switch-case (with enums, strings, fall-through concept) | |
|  | Switch Expressions (Java 12+) | |
|  | Loops – for, while, do-while | |
|  | For Loop Variations – Traditional, Enhanced, Nested | |
|  | While vs Do-While Loop Differences | |
|  | Break and Continue (use cases, labeled break) | |
|  | Enhanced for-loop (iterating arrays & collections) | |
|  | Pattern Matching for instanceof (Java 16+) | |
|  | Control Flow Best Practices | |
| **Arrays & Strings** | Arrays – Declaration, Initialization, Accessing Elements | |
|  | Array Operations – Copying, Searching, Sorting | |
|  | Multi-dimensional Arrays | |
|  | String Class – Immutability, String Pool | |
|  | String Methods – length, charAt, substring, indexOf, replace | |
|  | String Comparison – equals vs ==, compareTo | |
|  | StringBuilder vs StringBuffer | |
|  | String Formatting – printf, format, String.format | |
|  | Regular Expressions in Java | |
|  | Arrays and Strings Best Practices | |
| **OOP Fundamentals** | What is OOP & Why it is needed | |
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
|  | Object Class Methods – toString, equals, hashCode, clone | |
|  | this and super keywords | |
|  | Inner Classes – static, non-static, anonymous | |
|  | Introduction to SOLID & Other Principles (DRY, YAGNI, KISS) | |
|  | OOP Design Principles – Single Responsibility Principle | |
|  | OOP Design Principles – Open/Closed & Liskov Substitution | |
|  | OOP Design Principles – Interface Segregation & Dependency Inversion | |
|  | Coupling & Cohesion | |

## 🟡 INTERMEDIATE LEVEL

| Topic | Subtopic / Learning Item | Status (To Do / Done) |
|-------|---------------------------|------------------------|
| **Exception Handling** | Exception Handling – try, catch, finally | |
|  | Exception Handling – Checked vs Unchecked Exceptions | |
|  | Custom Exceptions | |
|  | throw vs throws | |
|  | Try-with-resources & AutoCloseable | |
|  | Exception Best Practices | |
| **Java Collections** | Java Collections – ArrayList Implementation & Usage | |
|  | Java Collections – LinkedList Implementation & Usage | |
|  | Java Collections – ArrayList vs LinkedList Performance | |
|  | Java Collections – HashSet Implementation & Usage | |
|  | Java Collections – LinkedHashSet vs HashSet | |
|  | Java Collections – TreeSet Implementation & Usage | |
|  | Java Collections – HashMap Implementation & Usage | |
|  | Java Collections – LinkedHashMap vs TreeMap | |
|  | Java Collections – ConcurrentHashMap Implementation | |
|  | Fail-fast vs Fail-safe Iterators | |
| **Generics** | Generics in Java (Type Parameters, Generic Methods) | |
|  | Generics – Bounded Types & Wildcards | |
|  | Generics – Type Erasure Deep Dive | |
|  | PECS Principle (Producer Extends, Consumer Super) | |
| **Streams API** | Streams API – Introduction & Basics | |
|  | Streams API – Intermediate Operations (map, filter, sorted) | |
|  | Streams API – Terminal Operations (collect, reduce, forEach) | |
|  | Streams API – Parallel Streams | |
|  | Streams API – Custom Collectors | |
| **Lambda Expressions** | Lambda Expressions – Syntax & Basics | |
|  | Lambda Expressions – Scope & Capturing Variables | |
|  | Lambda Expressions – Method References | |
|  | Functional Interfaces – Predicate & Function | |
|  | Functional Interfaces – Supplier & Consumer | |
| **Multithreading Basics** | Multithreading – Thread Creation & Lifecycle | |
|  | Multithreading – Runnable vs Thread | |
|  | Synchronization – synchronized keyword, locks, monitors | |
|  | Executor Framework – Thread Pools, Future, Callable | |
| **Java 8+ Features** | Java 8 Date and Time API (LocalDate, LocalDateTime, Instant, ZonedDateTime) | |
|  | Optional API Basics | |
| **Memory Management** | Stack vs Heap Memory | |
|  | Object Creation & Lifetime | |
|  | Java Memory Model (JMM) & Visibility (happens-before rules) | |
|  | References in Java – Strong, Weak, Soft, Phantom | |
|  | Escape Analysis & Object Allocation Optimizations | |
|  | OutOfMemoryError & Common Memory Leaks | |
|  | Tools for Detecting Memory Leaks – MAT | |

## 🔴 ADVANCED LEVEL

| Topic | Subtopic / Learning Item | Status (To Do / Done) |
|-------|---------------------------|------------------------|
| **JVM Internals** | JVM Architecture Overview | |
|  | JVM Memory Areas – Heap, Stack, Metaspace | |
|  | JVM Memory Areas – Code Cache, Native Memory | |
|  | Class Loaders – Bootstrap, Extension, Application | |
|  | JVM Execution Engine & Bytecode Interpreter | |
|  | JIT Compiler Basics (C1, C2 compilers) | |
|  | Class File Structure Basics | |
|  | Java Native Interface (JNI) Basics | |
| **Garbage Collection** | GC Algorithms – Mark & Sweep, Mark & Compact, Copying | |
|  | GC Collectors – Serial, Parallel, CMS, G1, ZGC, Shenandoah, Epsilon | |
|  | GC Tuning Flags & Parameters | |
|  | Generational GC Concepts | |
|  | GC Logs – Reading & Interpreting | |
|  | Stop-the-World Events (STW) | |
|  | Profiling Memory with VisualVM, JConsole, JMC | |
| **Advanced Concurrency** | Thread Lifecycle (new, runnable, waiting, timed waiting, terminated) | |
|  | Thread States & Scheduling | |
|  | Synchronization & Locks (intrinsic, reentrant lock) | |
|  | Semaphore, Mutex | |
|  | ReentrantReadWriteLock | |
|  | Volatile Keyword & Happens-Before Relationship | |
|  | ThreadLocal for Thread-Specific Data | |
|  | Thread Safety Issues – Race Conditions, Deadlocks | |
|  | Deadlock Detection & Avoidance | |
|  | Executor Framework & Thread Pools | |
|  | Fork/Join Framework | |
|  | Phaser & CountDownLatch | |
|  | Java Virtual Threads (Project Loom) | |
|  | Thread-safe Collections (ConcurrentHashMap, CopyOnWriteArrayList) | |
|  | CompletableFuture for Asynchronous Programming | |
|  | Producer-Consumer Problem | |
| **Performance Optimization** | Profiling Tools – VisualVM, JProfiler, Flight Recorder | |
|  | CPU-bound vs I/O-bound Applications | |
|  | Efficient Data Structures & Algorithms in Java | |
|  | String Performance – String, StringBuilder, StringBuffer | |
|  | String Interning & String Pool | |
|  | Caching Strategies (LRU, Guava Cache, Redis basics) | |
|  | Lazy Initialization & Memoization | |
|  | Reducing Object Creation | |
|  | Escape Analysis Deeper | |
|  | Benchmarking Pitfalls – JIT, Warmup, Dead Code Elimination | |
|  | Using Primitive Collections (Trove, FastUtil) | |
|  | Optimizing Database Access (Batching, Prepared Statements, Indexing) | |
| **Advanced Java Features** | Generics & Type Erasure | |
|  | Records (Data Carrier Classes) | |
|  | Sealed Classes (Java 17+) | |
|  | Pattern Matching for Switch (Java 17+) | |
|  | Var Keyword (Java 10) | |
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
|  | Module System (Java 9+) | |
| **JVM Monitoring & Debugging** | JStack – Taking & Analyzing Thread Dumps | |
|  | JMap, JInfo, JStat, JHat, jps – Tools Overview | |
|  | Thread Contention & Deadlock Analysis | |
|  | Log Analysis & Structured Logging (SLF4J, Logback, Log4j2) | |
|  | Exception Profiling & Root Cause Analysis | |
|  | Remote Debugging with JDWP | |
|  | Analyzing Heap Dumps (MAT) | |
| **Testing & Best Practices** | Unit Testing with JUnit 5 – Assertions & Parameterized Tests | |
|  | Mocking with Mockito – Basics & Best Practices | |
|  | Integration Testing – TestContainers, Spring Boot Testing | |
|  | Performance Testing with JMH (Java Microbenchmark Harness) | |
|  | Code Profiling & Refactoring | |
|  | Test Pyramid – Unit, Integration, E2E | |
|  | TDD & BDD – JUnit + Cucumber | |
|  | Mutation Testing – Pitest | |
|  | Code Coverage Tools – Jacoco | |
|  | SOLID Principles – Single Responsibility Principle | |
|  | SOLID Principles – Open/Closed & Liskov Substitution | |
|  | SOLID Principles – Interface Segregation & Dependency Inversion | |
|  | Design Patterns – Creational: Singleton Pattern | |
|  | Design Patterns – Creational: Factory Pattern | |
|  | Design Patterns – Creational: Builder Pattern | |
|  | Design Patterns – Structural: Adapter Pattern | |
|  | Design Patterns – Structural: Decorator Pattern | |
|  | Design Patterns – Structural: Proxy Pattern | |
|  | Design Patterns – Behavioral: Observer Pattern | |
|  | Design Patterns – Behavioral: Strategy Pattern | |
|  | Design Patterns – Behavioral: Command Pattern | |
|  | Best Practices for Large-Scale Java Applications (Logging, Exception Handling, Packaging, Modularization) | |
|  | Error Handling Best Practices | |
