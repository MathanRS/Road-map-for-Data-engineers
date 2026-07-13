# 🚀 PySpark Curriculum

---

# Module 01: PySpark Fundamentals (10 Lessons)

### 1. What is Spark *(Free)*
Understand Spark's distributed architecture—driver, executors, partitions, lazy evaluation, and when to use Spark vs pandas vs DuckDB vs Flink.

### 2. SparkSession Setup *(Free)*
Create and configure SparkSession for development and production. Master the essential configs: shuffle partitions, AQE, memory, and local mode for testing.

### 3. DataFrames Basics *(Free)*
Create PySpark DataFrames from files, lists, and pandas. Define schemas explicitly, inspect data, and understand the key differences between PySpark and pandas DataFrames.

### 4. Transformations
Master the four transformation operations that cover 80% of PySpark code—`select`, `filter`, `withColumn`, and `when/otherwise` for conditional logic.

### 5. Aggregations
Turn millions of raw records into summary tables with `groupBy`, `agg`, and `pivot`. Learn built-in aggregate functions and the `approx_count_distinct` optimization.

### 6. Joins
Master PySpark joins—broadcast joins for small tables, sort-merge joins for large tables, and salt key techniques for skewed data. The #1 PySpark performance skill.

### 7. Window Functions
Compute rankings, running totals, lead/lag, and moving averages with window functions. Includes the most important PySpark pattern: `row_number` deduplication.

### 8. Reading & Writing Data
Read and write data in PySpark with proper schema definition, write modes, partitioning, and file format best practices for production pipelines.

### 9. Handling Dirty Data
Clean real-world data in PySpark—handle nulls, remove duplicates, clean strings, validate types, and build the data cleaning layer every pipeline needs.

### 10. Spark SQL
Run SQL queries in Spark, create managed and external tables, work with views and databases, and understand Spark's relationship to Hive metastore.

---

# Module 02: PySpark Advanced (11 Lessons)

### 11. Execution Model *(Free)*
Understand the execution hierarchy—jobs, stages, tasks—and why shuffles are the #1 performance bottleneck. The mental model for diagnosing every Spark performance problem.

### 12. Partitioning & Bucketing *(Free)*
Reduce data scanned by 33× with partitioning. Eliminate shuffles for repeated joins with bucketing. Know when to use each and avoid the small file problem.

### 13. Broadcast Joins *(Free)*
Eliminate shuffle for dimension table joins by broadcasting small tables to all executors. Learn when to broadcast, when not to, and how to tune the threshold.

### 14. Caching & Persistence
Avoid recomputing expensive DataFrames with caching. Understand storage levels, when to cache vs not, and how to avoid unnecessary memory usage.

### 15. UDFs & Pandas UDFs
UDFs are 2–10× slower than built-in functions. Learn when UDFs are necessary and how Pandas UDFs provide significant performance improvements.

### 16. Spark UI
Read the Spark UI to diagnose data skew, unnecessary shuffles, memory spills, and garbage collection overhead.

### 17. Catalyst & Tungsten
Understand how Spark optimizes your code through Catalyst and Tungsten, and learn how to write optimizer-friendly code.

### 18. Memory Management
Fix `OutOfMemoryError`, diagnose memory spills, tune garbage collection, and understand Spark's unified memory model.

### 19. Structured Streaming
Build real-time pipelines using the DataFrame API. Read from Kafka, process streaming data, handle late events, and write to Delta Lake.

### 20. Data Skew
Detect and fix data skew using Spark UI, salt keys, Adaptive Query Execution (AQE), and smart partitioning strategies.

### 21. RDDs & Low-Level APIs
Learn Spark's low-level RDD API, key-value operations, custom partitioning, and when DataFrames remain the better choice.

---

# Module 03: Interview Patterns (10 Lessons)

### 22. Flatten Nested JSON *(Free)*
Flatten deeply nested JSON into warehouse-ready tables using `explode`, struct access, and `from_json`.

### 23. Deduplication *(Free)*
Master the `row_number` + window function deduplication pattern used extensively in interviews and production.

### 24. SCD Type 2 *(Free)*
Implement Slowly Changing Dimension Type 2 using Delta Lake `MERGE`, including versioning and historical tracking.

### 25. Sessionization
Group clickstream events into user sessions using window functions, conditional flags, and cumulative sums.

### 26. Data Quality Framework
Build a reusable framework for validating data quality with configurable rules and reporting.

### 27. Optimize Spark Job
Identify bottlenecks using Spark UI and improve performance with broadcast joins, partition tuning, and UDF optimization.

### 28. Streaming Pipeline
Build a Structured Streaming pipeline with Kafka, watermarks, window aggregations, and Delta Lake checkpointing.

### 29. Custom Partitioner
Handle extreme data skew using salt-key partitioning while preserving balanced workloads.

### 30. Idempotent Upsert
Create an idempotent upsert pipeline using Delta Lake `MERGE`, schema evolution, and optimized large-scale updates.

### 31. Error Handling Pipeline
Implement structured logging, retry logic, dead-letter queues, and idempotent writes for production-ready pipelines.

---

# Module 04: Databricks (13 Lessons)

### 32. Databricks Overview *(Free)*
Understand why Databricks exists, the problems it solves, and how it integrates with AWS, Azure, and GCP.

### 33. Databricks Architecture *(Free)*
Learn the Databricks control plane and data plane architecture.

### 34. Lakehouse Architecture *(Free)*
Explore the Lakehouse architecture combining the strengths of data lakes and data warehouses.

### 35. Databricks Workspace
Navigate notebooks, SQL editor, clusters, jobs, Delta Lake, libraries, and workspace administration.

### 36. Creating Clusters
Create and configure Databricks clusters with runtime selection, auto-scaling, worker types, and cost optimization.

### 37. Notebook & DBFS
Manage files in DBFS using `dbutils` for reading, writing, copying, moving, and deleting data.

### 38. Delta Lake
Learn Delta Lake fundamentals including ACID transactions, schema enforcement, and transaction logs.

### 39. Advanced Delta Lake
Use Time Travel, `OPTIMIZE`, `Z-ORDER`, and `VACUUM` for performance tuning and storage optimization.

### 40. Databases & Tables
Understand managed vs unmanaged tables, schemas, `LOCATION`, and lifecycle behavior.

### 41. Views
Work with simple, temporary, and global temporary views in Databricks.

### 42. Delta Tables from Files
Create Delta tables from Parquet, CSV, and existing datasets using Spark DataFrames and SQL.

### 43. Medallion Architecture
Implement Bronze, Silver, and Gold layers for scalable Lakehouse pipelines.

### 44. In-Depth Parquet
Understand Parquet internals including columnar storage, row groups, metadata, and compression.

---

# Module 05: PySpark Projects (1 Lesson)

### 45. Spotify Spark Pipeline *(Free)*
Build an end-to-end Spotify ETL pipeline using Spark on AWS Glue—extract from Spotify API, transform with PySpark, load into Snowflake via Snowpipe, and automate with CloudWatch.
