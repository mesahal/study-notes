# Database Learning Sheet

## 🟢 BEGINNER LEVEL

| Topic | Subtopic / Learning Item | Status (To Do / Done) |
|-------|---------------------------|------------------------|
| **Database Fundamentals** | What is a Database? | |
|  | DBMS vs RDBMS | |
|  | Types of Databases: Relational, NoSQL, In-memory, Graph, Time-series | |
|  | Database vs Data Warehouse vs Data Lake | |
|  | Tables, Rows, Columns | |
|  | Primary Key, Foreign Key, Candidate Key | |
|  | Composite Keys and Surrogate Keys | |
|  | ER Diagrams & Data Modeling Basics | |
|  | Entity Relationship Modeling – Entities, Attributes, Relationships | |
|  | Database Architecture: 1-tier, 2-tier, 3-tier | |
|  | ACID vs BASE Concepts | |
|  | Data Integrity (Entity, Referential, Domain, User-defined integrity) | |
|  | Transactions in DBMS – Concepts, Lifecycle | |
|  | Relational Algebra & Relational Calculus Basics | |
|  | Database Design Principles | |
| **SQL Basics** | SQL Syntax Overview | |
|  | DDL – CREATE, ALTER, DROP | |
|  | DML – INSERT, UPDATE, DELETE | |
|  | DQL – SELECT, WHERE, ORDER BY, LIMIT | |
|  | DCL – GRANT, REVOKE, DENY | |
|  | TCL – COMMIT, ROLLBACK, SAVEPOINT | |
|  | SQL Data Types – Numeric, String, Date/Time, Boolean | |
|  | Numeric Data Types – INT, DECIMAL, FLOAT, DOUBLE | |
|  | String Data Types – VARCHAR, CHAR, TEXT, BLOB | |
|  | Date/Time Data Types – DATE, TIME, DATETIME, TIMESTAMP | |
|  | Using Aliases and Expressions in Queries | |
|  | Basic Functions – String, Numeric, Date Functions | |
|  | String Functions – CONCAT, SUBSTRING, LENGTH, UPPER, LOWER | |
|  | Numeric Functions – ROUND, CEIL, FLOOR, ABS, MOD | |
|  | Date Functions – NOW, DATE, YEAR, MONTH, DAY | |
|  | Set Operators – UNION, INTERSECT, EXCEPT | |
|  | Temporary Tables vs Table Variables | |
|  | SQL Query Execution Order | |
| **NoSQL Basics** | NoSQL Overview & CAP Theorem | |
|  | Types of NoSQL – Key-Value, Document, Column, Graph | |
|  | MongoDB Basics – CRUD Operations | |
|  | MongoDB Schema Design Principles | |
|  | Redis Basics – Data Structures | |
|  | Redis for Caching – Expiry, Persistence (RDB, AOF) | |
|  | SQL vs NoSQL – Use Cases, Advantages, Trade-offs | |
|  | Eventual Consistency vs Strong Consistency | |

## 🟡 INTERMEDIATE LEVEL

| Topic | Subtopic / Learning Item | Status (To Do / Done) |
|-------|---------------------------|------------------------|
| **SQL Intermediate** | Joins – INNER, LEFT, RIGHT, FULL JOIN | |
|  | Joins – CROSS JOIN, SELF JOIN, Semi & Anti Join | |
|  | GROUP BY & HAVING | |
|  | Aggregate Functions – COUNT, SUM, AVG, MIN, MAX | |
|  | Subqueries – Scalar Subqueries, Non-Correlated Subqueries | |
|  | Correlated Subqueries & EXISTS/NOT EXISTS | |
|  | Nested Queries | |
|  | Views – Creating, Updating, Dropping | |
|  | Indexes – Basics, Usage, Benefits | |
|  | Constraints – NOT NULL, UNIQUE, CHECK, DEFAULT, FOREIGN KEY | |
|  | SQL Functions – COALESCE, NULLIF, CASE WHEN, CAST | |
|  | Common Table Expressions (CTE, Recursive CTE) | |
|  | Window Functions – ROW_NUMBER, RANK, LEAD, LAG, NTILE | |
| **ORM & Hibernate / JPA** | ORM Concept & Benefits | |
|  | JPA & Hibernate Overview | |
|  | JPA Entity Mapping Basics | |
|  | JPA Entity Lifecycle Management | |
|  | EntityManager vs EntityManagerFactory | |
|  | Entity Mapping – @Entity, @Table, @Id, @Embeddable, @GeneratedValue | |
|  | JPA Entity Lifecycle (Transient, Managed, Detached, Removed) | |
|  | JPA Relationships – @OneToOne, @OneToMany, @ManyToMany, @ManyToOne | |
|  | JPA Cascade Types – ALL, PERSIST, MERGE, REMOVE, REFRESH, DETACH | |
|  | JPA Fetching Strategies – Lazy vs Eager | |
|  | Hibernate Dirty Checking | |
|  | Hibernate Flush Modes – AUTO, COMMIT, MANUAL | |
|  | JPQL – Basic Queries, Named Queries | |
|  | JPA Criteria API – Joins, Subqueries, Predicates | |
|  | Spring Data JPA Specifications (Dynamic Queries) | |
|  | JPA Projections – DTO vs Interface Projections | |
|  | Hibernate Caching – First Level, Second Level, Query Cache | |
|  | Hibernate Caching – Integration with Ehcache/Redis | |
|  | Transactions in Hibernate – Programmatic | |
|  | Transactions in Hibernate – Declarative | |
|  | JPA Locking Strategies (Optimistic, Pessimistic) | |
|  | JPA Auditing (@CreatedDate, @LastModifiedBy) | |
|  | JPA Entity Listeners & Callbacks | |
|  | N+1 Select Problem & Solutions | |
|  | Hibernate Interceptors & Event Listeners | |
|  | Hibernate Dialects & Database Compatibility | |
|  | Result Transformation to DTO and Projections | |
|  | Common JPA/Hibernate Exceptions & Solutions | |
|  | Batch Processing & Fetch Size Optimization | |
|  | Multi-tenancy Support in Hibernate | |
| **NoSQL Intermediate** | MongoDB Aggregation Framework Basics | |
|  | MongoDB Aggregation Framework – $lookup, $unwind, $group, $project | |
|  | MongoDB Index Types – Single, Compound, Multikey, Text, GeoSpatial | |
|  | Redis Pub/Sub & Streams | |
|  | Redis Eviction Policies – LRU, LFU, RANDOM, NOEVICT | |
|  | Cassandra Basics – Wide-Column Storage | |
|  | Cassandra Partitioning & Replication | |
|  | Cassandra Consistency Levels (ONE, QUORUM, ALL) | |
|  | Cassandra Data Modeling Best Practices | |
|  | NoSQL Indexing & Query Patterns | |
|  | Polyglot Persistence – Mixing SQL & NoSQL | |

## 🔴 ADVANCED LEVEL

| Topic | Subtopic / Learning Item | Status (To Do / Done) |
|-------|---------------------------|------------------------|
| **SQL Advanced** | Stored Procedures – Creating, Parameters, Execution | |
|  | Functions – Scalar & Table-Valued | |
|  | Triggers – BEFORE, AFTER, INSTEAD OF, Use Cases | |
|  | Transactions – BEGIN, COMMIT, ROLLBACK | |
|  | Transactions – Savepoints, Rollback strategies | |
|  | ACID Properties – Atomicity, Consistency, Isolation, Durability | |
|  | Isolation Levels – READ UNCOMMITTED | |
|  | Isolation Levels – READ COMMITTED | |
|  | Isolation Levels – REPEATABLE READ | |
|  | Isolation Levels – SERIALIZABLE | |
|  | Locks & Deadlocks – Types of Locks (Shared, Exclusive) | |
|  | Locks & Deadlocks – Deadlock Detection & Prevention | |
|  | Query Optimization – Execution Plans (MySQL, PostgreSQL, Oracle) | |
|  | Query Optimization – Index Usage & Statistics | |
|  | Performance Tuning – Query Rewriting, Partitioning, Hints | |
|  | Advanced Indexing – Covering Index, Filtered Index, Expression Index | |
| **Database Design & Advanced Topics** | Normalization – 1NF | |
|  | Normalization – 2NF | |
|  | Normalization – 3NF | |
|  | Normalization – BCNF | |
|  | Denormalization – When & Why | |
|  | Indexing – Clustered, Non-Clustered | |
|  | Indexing – Composite Index | |
|  | Partitioning – Horizontal | |
|  | Partitioning – Vertical | |
|  | Partitioning – Range, List, Hash | |
|  | Sharding Basics – Concept, Advantages, Implementation | |
|  | Query Execution Lifecycle in RDBMS | |
|  | Concurrency Control in DB – Optimistic vs Pessimistic | |
|  | Query Performance Tuning – EXPLAIN, ANALYZE, Index Hints | |
|  | Database Security – Users, Roles, Permissions | |
|  | Database Security – Data Encryption at Rest & Transit | |
|  | Database Replication – Master-Slave | |
|  | Database Replication – Master-Master | |
|  | Database Clustering – Shared Nothing vs Shared Disk | |
|  | Backup & Recovery – Full Backup | |
|  | Backup & Recovery – Incremental Backup | |
|  | Backup & Recovery – Point-in-Time Recovery | |
|  | Data Warehousing Basics – Star Schema, Snowflake Schema, ETL | |
|  | Big Data Integrations – Hadoop, Spark with Databases | |
|  | Cloud Databases – AWS RDS, Aurora, DynamoDB, GCP Spanner, Azure CosmosDB | |
|  | Modeling Monetary Data (Precision, Scale) | |
|  | JSON / XML Data Types in RDBMS (Postgres, MySQL, Oracle) | |
|  | Materialized Views – Concept & Use Cases | |
|  | Temporal Tables (Time-Travel Queries) | |
|  | Change Data Capture (CDC – Debezium, Kafka Connect) | |
|  | Data Archiving Strategies (Cold Storage, Historical Tables) | |
