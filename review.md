# Data Engineering Interview Roadmap (3 Years Experience)

> Based on our conversation, I don't think your problem is SQL or Python. Your problem is that you know many **terms**, but you don't yet know **when to apply each concept**. That's exactly what interviewers test for someone with **3 years of experience**.

If I were interviewing a 3-year Data Engineer, this is the roadmap I'd expect.

---

# Phase 1: Core Data Engineering Concepts (Must Know) ⭐⭐⭐⭐⭐

You already know some of these.

- ✅ Batch vs Stream Processing
- ✅ ETL vs ELT
- ✅ OLTP vs OLAP
- ✅ Data Warehouse vs Data Lake vs Lakehouse
- ✅ File Formats (CSV, JSON, Parquet, Avro, ORC)
- ⭐ Data Modeling (Fact & Dimension Tables)
- ⭐ Star Schema vs Snowflake Schema
- ⭐ SCD Type 1 & Type 2
- ⭐ Upsert (MERGE)
- ⭐ Incremental Load vs Full Refresh
- ⭐ Idempotency
- ⭐ Data Quality
- ⭐ Data Lineage
- ⭐ Data Observability
- ⭐ Schema Evolution
- ⭐ Partitioning
- ⭐ Clustering
- ⭐ Delivery Guarantees

---

# Phase 2: SQL (Very Important) ⭐⭐⭐⭐⭐

A 3-year engineer is expected to be comfortable with SQL.

## You should know

- Joins
- Window Functions
- CTEs
- Subqueries
- CASE WHEN
- GROUP BY
- HAVING
- MERGE
- DELETE
- UPDATE
- UPSERT
- ROW_NUMBER()
- RANK()
- DENSE_RANK()
- LEAD()
- LAG()
- Date Functions
- Performance Tuning

## Interviewers love questions like

- Find the second highest salary.
- Remove duplicate records.
- Find consecutive login days.

---

# Phase 3: Python ⭐⭐⭐⭐☆

Not advanced software engineering.

## Mostly

- Reading Files
- Functions
- Exception Handling
- Classes (Basic)
- List Comprehension
- Dictionaries
- JSON
- CSV
- Pandas Basics
- Logging

---

# Phase 4: Spark / PySpark ⭐⭐⭐⭐⭐

If your resume has Spark, expect many questions.

## Know

- DataFrame
- RDD (Basic)
- Transformations
- Actions
- Lazy Evaluation
- Narrow vs Wide Transformation
- Shuffle
- Repartition
- Coalesce
- Broadcast Join
- Caching
- Partitioning
- Spark Architecture

---

# Phase 5: Airflow ⭐⭐⭐⭐⭐

Interviewers almost always ask:

- What is a DAG?
- Scheduler
- Executor
- Worker
- Retries
- Catchup
- Backfill
- XCom
- Sensors
- Operators
- Trigger Rules
- Failure Handling

---

# Phase 6: Cloud (AWS / Azure / GCP)

## AWS

- S3
- Glue
- Lambda
- IAM
- CloudWatch
- Redshift
- Athena
- Secrets Manager
- EventBridge

## Azure

- ADLS
- Synapse
- Data Factory
- Databricks
- Key Vault

## GCP

- BigQuery
- Dataflow
- Cloud Storage
- Pub/Sub
- Composer

---

# Phase 7: Databases

Know

- Primary Key
- Foreign Key
- Index
- Clustered Index
- Non-clustered Index
- Normalization
- Denormalization
- Transactions
- ACID
- CAP Theorem (Basic)
- Locks
- Deadlocks

---

# Phase 8: System Design (3 Years)

Not as deep as senior engineers.

But you should answer

- Design a pipeline for e-commerce orders.
- Design a real-time dashboard.
- Design a CDC pipeline.

---

# Phase 9: Performance Optimization

Very common.

- How to optimize Spark?
- How to optimize SQL?
- How to reduce Glue job runtime?
- How to reduce Snowflake cost?
- Partitioning
- Broadcast Join
- Predicate Pushdown
- Caching
- File Size Optimization
- Compression

---

# Phase 10: Scenario Questions ⭐⭐⭐⭐⭐

These decide interviews.

Examples

- Pipeline failed halfway.
- Duplicate records.
- Late arriving data.
- Null values.
- Schema changed.
- One source stopped sending data.
- Customer reports wrong dashboard.
- 100 million rows.
- Pipeline takes 8 hours.
- How do you debug?

---

# Phase 11: Resume Questions

Every interviewer asks

- Explain your project.
- Explain architecture.
- Explain one pipeline.
- Biggest challenge.
- Failure.
- Optimization.
- Business impact.

---

# Phase 12: Behavioral

- Tell me about yourself.
- Conflict.
- Deadline.
- Mistake.
- Leadership.
- Ownership.
- Communication.

---

# Topics Many Candidates Forget

These often differentiate stronger candidates.

- CDC (Change Data Capture)
- Watermarking
- Checkpointing
- Delta Lake
- Apache Iceberg
- Apache Hudi
- Medallion Architecture (Bronze → Silver → Gold)
- Slowly Changing Dimensions (Type 1 & Type 2)
- Data Contracts
- Secrets Management
- CI/CD for Data Pipelines
- Unit Testing for ETL
- Data Catalog (AWS Glue Catalog, Microsoft Purview)
- Orchestration vs Scheduling
- Compression Formats (Snappy, Gzip)
- Small File Problem in Spark
- Why Parquet is Faster than CSV
- Why Partitioning Improves Performance

---

# My Assessment of You

After talking with you for a while, here's where I think you stand today.

## Strengths

- You learn quickly.
- You can relate concepts together.
- You're willing to admit gaps and improve.
- You already have relevant project experience.

## Needs Work

- Applying the right concept to the right problem.
- Structuring answers instead of mentioning every related topic.
- Explaining the **why**, not just naming technologies.
- Building confidence without guessing.

---

# What I'd Recommend

Don't study random YouTube videos anymore. Follow a structured plan.

For every topic:

1. Learn the **definition**.
2. Understand **why it exists**.
3. Study a **real-world example**.
4. Practice **interview questions**.
5. Answer **scenario-based questions**.

Then move to the next topic.

---

## Final Advice

If we continue practicing this way, I believe you can reach the level expected in many **3-year Data Engineering interviews** much faster than by memorizing definitions alone.

The goal isn't to remember keywords—it's to know **when** and **why** to use each concept.
