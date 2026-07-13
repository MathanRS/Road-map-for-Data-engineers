# 🗄️ SQL Curriculum

---

# Module 01: SQL Basics & Introduction (13 Lessons)

### 1. What is SQL *(Free)*
SQL is the universal language of data. Learn why SQL is non-negotiable for data engineers, how it differs from general programming, and what SQL mastery actually means in DE.

### 2. SQL for Data Engineers *(Free)*
See how SQL is actually used in production data engineering—temp tables, window functions, MERGE, CTEs, and complex JOINs in a real BigQuery pipeline that processes logistics data.

### 3. How Databases Work *(Free)*
Understand the building blocks of relational databases—tables, rows, columns, schemas, data types, constraints, and indexes. The foundation for every SQL query you will ever write.

### 4. Environment Setup
Install PostgreSQL, DuckDB, and connect to cloud free tiers. The opinionated guide to which SQL environment to use for learning, local development, and interview practice.

### 5. SQL & Data Types
Understand what SQL is, the types of SQL commands (DDL, DML, DCL, TCL), essential SQL keywords, data types, and write your first basic queries with SELECT and WHERE.

### 6. Project: Sales Data
Build a sales table from scratch, insert data, and explore it using SELECT, WHERE, GROUP BY, ORDER BY, and SQL operators like AND, OR, LIKE, IN, and BETWEEN.

### 7. Relational vs NoSQL
When to choose SQL databases vs NoSQL—document stores, key-value, column-family, and graph databases. The decision framework for data engineers.

### 8. SELECT & FROM
Write your first SQL queries with SELECT and FROM. Learn column selection, aliases, DISTINCT, and LIMIT—plus why SELECT * is fine for exploration but terrible for production.

### 9. WHERE Filtering
Filter rows with WHERE, comparison operators, logical operators, IN, BETWEEN, LIKE, and IS NULL. Master the three-valued logic trap that catches most beginners.

### 10. ORDER BY & LIMIT
Sort query results with ORDER BY, limit output with LIMIT, and paginate with OFFSET. Learn why OFFSET is slow on large datasets and keyset pagination is better.

### 11. ALTER TABLE
Learn how to modify existing tables in PostgreSQL using ALTER TABLE—rename columns, add new columns, change data types, and drop columns with practical examples.

### 12. Keys (PK, FK, Composite)
Understand primary keys, foreign keys, composite keys, unique keys, candidate keys, super keys, and alternate keys—with practical PostgreSQL examples.

### 13. Inactive Free Users *(Practice)*
Practice SQL fundamentals with a real-world query challenge.

---

# Module 02: SQL Fundamentals (11 Lessons)

### 14. ACID Properties *(Free)*
Understand the four ACID properties that guarantee reliable database transactions—with real-world bank transfer examples and SQL transaction commands.

### 15. Normalization *(Free)*
Learn database normalization from scratch—first, second, and third normal forms explained with a step-by-step customer orders example.

### 16. INSERT, UPDATE, DELETE *(Free)*
Load warehouses, fix bad data, and implement SCDs with INSERT, UPDATE, DELETE, and MERGE. The DML operations that data engineers use but most SQL courses skip.

### 17. JOINs
Master every JOIN type with visual diagrams, performance considerations, and the specific join pitfalls that trip up interview candidates.

### 18. GROUP BY & Aggregations
Turn millions of rows into answers with GROUP BY and aggregation functions. Covers HAVING, SQL execution order, conditional aggregations, and NULL traps in COUNT and AVG.

### 19. Subqueries
Build complex logic with scalar, table, and correlated subqueries. Learn when subqueries run once vs once-per-row, and why CTEs are usually a better choice.

### 20. CASE Statements
Master SQL's if-then-else with CASE expressions. Covers simple CASE, searched CASE, CASE inside aggregations, and COALESCE for NULL handling.

### 21. Set Operations
Combine query results with UNION, UNION ALL, EXCEPT, and INTERSECT while understanding performance tradeoffs.

### 22. NULL Handling
Master three-valued logic, COALESCE, NULLIF, and NULL handling patterns that prevent silent data corruption.

### 23. CTEs
Turn nested subqueries into readable, named steps with CTEs. Covers chained CTEs and CTE vs temp table vs view tradeoffs.

### 24. Rising Temperature (Self-Join) *(Practice)*
Solve a common interview problem using self-joins.

---

# Module 03: Intermediate SQL (11 Lessons)

### 25. ROW_NUMBER & RANK *(Free)*
Master ROW_NUMBER, RANK, and DENSE_RANK for deduplication, top-N analysis, and ranking scenarios.

### 26. LAG & LEAD *(Free)*
Compare records across time periods, detect event gaps, and solve time-series problems using window functions.

### 27. Running Totals & Averages *(Free)*
Calculate running totals, moving averages, and cumulative metrics with SUM/AVG OVER.

### 28. NTILE & Percentiles
Divide rows into quantiles and calculate percentile rankings with NTILE, PERCENT_RANK, and CUME_DIST.

### 29. String Functions
Parse URLs, extract domains, clean text data, and manipulate strings using SQL functions.

### 30. EXISTS vs IN vs JOIN
Compare three approaches to semi-joins and understand correctness and performance implications.

### 31. Views & CTAS
Create reusable query layers with Views, CTAS, and temporary tables.

### 32. Casting
Convert between numeric, string, date, and timestamp data types using CAST and database-specific syntax.

### 33. Date & Time Functions
Master DATE_TRUNC, DATEADD, DATEDIFF, EXTRACT, and timezone handling across major SQL platforms.

### 34. Stored Procedures
Create reusable SQL logic using stored procedures and functions in PostgreSQL.

### 35. Cumulative Revenue by Category *(Practice)*
Practice window functions and aggregations in a business scenario.

---

# Module 04: Advanced SQL (10 Lessons)

### 36. Recursive CTEs *(Free)*
Traverse hierarchies, generate date spines, and solve graph problems using recursive queries.

### 37. PIVOT & UNPIVOT *(Free)*
Transform rows into columns and columns into rows using standard and platform-specific techniques.

### 38. GROUPING SETS & CUBE *(Free)*
Generate subtotals and multidimensional aggregations efficiently.

### 39. JSON & Semi-Structured Data
Work with JSON in PostgreSQL, Snowflake, BigQuery, and Redshift. Extract fields and flatten nested structures.

### 40. Query Optimization
Use EXPLAIN plans to diagnose bottlenecks and optimize slow SQL queries.

### 41. Indexing Strategies
Choose and implement effective indexing strategies for different query workloads.

### 42. Temp Tables vs CTEs vs Views
Understand persistence, performance, and use cases for each intermediate storage technique.

### 43. SQL Anti-Patterns
Avoid common SQL mistakes including SELECT *, DISTINCT misuse, and NOT IN with NULL values.

### 44. Platform-Specific SQL
Learn dialect differences across PostgreSQL, BigQuery, Snowflake, Redshift, and Databricks SQL.

### 45. Pivoting Sales by Region *(Practice)*
Apply pivoting techniques to build analytical reports.

---

# Module 05: SQL Interview Patterns (13 Lessons)

### 46. Deduplication *(Free)*
Master the ROW_NUMBER-based deduplication pattern used in interviews and production systems.

### 47. Running Totals *(Free)*
Calculate cumulative metrics while handling gaps and time-series edge cases.

### 48. YoY & MoM Growth *(Free)*
Compute growth metrics using LAG, date arithmetic, and defensive SQL techniques.

### 49. Gaps and Islands
Identify consecutive sequences, streaks, and missing values using advanced SQL patterns.

### 50. Sessionization
Group user events into sessions using inactivity thresholds and window functions.

### 51. Funnel Analysis
Calculate multi-step conversion funnels and user drop-off rates.

### 52. Retention Cohorts
Build cohort retention tables and analyze long-term user engagement.

### 53. Top-N per Group
Find top-performing records within categories using ranking functions.

### 54. Pivot & Cross-tab
Generate cross-tab reports using CASE expressions and aggregations.

### 55. Self-Joins
Compare rows within the same table for relationship and sequence analysis.

### 56. Hierarchy Traversal
Navigate organizational structures and dependency trees using recursive SQL.

### 57. Moving Averages
Calculate rolling metrics with window functions and date-spine techniques.

### 58. Delete Duplicate Emails *(Practice)*
Solve a classic SQL interview challenge involving duplicate records.
