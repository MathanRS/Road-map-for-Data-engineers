# 📚 Curriculum

## Module 01: Python Fundamentals (16 Lessons)

### 1. Introduction *(Free)*
Learn why Python is the most important language for data engineers, how it fits into the data engineering stack, and the three-step path from basics to building production pipelines.

### 2. Installation & Setup *(Free)*
Install Python and Jupyter Notebook on Windows, macOS, and Linux. Set up your local development environment and write your first Python code in under 10 minutes.

### 3. Strings *(Free)*
Learn how to create, index, slice, concatenate, and format strings in Python. Master the string operations you will use every day as a data engineer.

### 4. Numbers & Variables
Learn Python number types, arithmetic operations, variable assignments, and type checking. Build a solid foundation for working with data in Python.

### 5. Lists, Tuples & Sets
Learn Python's three core collection types—lists for ordered mutable data, tuples for fixed data, and sets for unique values. Includes indexing, slicing, and common operations.

### 6. Dictionaries
Master Python dictionaries—create, access, modify, and nest key-value pairs. The most important data structure for working with JSON, APIs, and configuration.

### 7. Conditionals & Loops
Learn Python control flow—if/elif/else for decisions, for loops for iteration, and while loops for repeated execution. Includes practical examples with real data patterns.

### 8. Comprehensions & Lambda
Write concise Python with list comprehensions and lambda functions. Learn how to install and import packages to extend Python's capabilities.

### 9. Exceptions & File I/O
Learn to handle errors gracefully with try/except and read/write files in Python. Two essential skills for building reliable data pipelines.

### 10. Functions
Learn how to write reusable Python functions with `def`, positional and keyword arguments, default values, `*args`, `**kwargs`, and return values. The foundation of clean, modular code.

### 11. OOP Basics
Understand Object-Oriented Programming in Python from scratch. Learn classes, objects, attributes, methods, and the difference between instance, class, and static methods.

### 12. NumPy Basics
Learn NumPy from scratch—create arrays, understand shapes and dtypes, use built-in methods like `arange`, `zeros`, `ones`, `linspace`, and generate random numbers for data work.

### 13. Pandas Fundamentals
Learn the basics of pandas—create Series and DataFrames, read CSV files, explore data with `info`, `head`, `unique`, `value_counts`, and filter rows using boolean conditions.

### 14. Pandas Manipulation
Master pandas data manipulation—column operations, apply functions, sorting, pivot tables, `groupby` aggregations, and combining DataFrames with `concat`, `merge`, and `join`.

### 15. DateTime in Pandas
Learn how to convert strings to datetime, extract year/month/day, calculate age, filter by date ranges, and set datetime indexes for fast time-based queries in pandas.

### 16. File Formats
Learn how to read and write JSON, CSV, Excel, and Avro files in Python using built-in modules and pandas. Understand when to use each format in data engineering.

---

## Module 02: Python for Data Engineers (10 Lessons)

### 17. DE Data Structures *(Free)*
Master `dict`, `defaultdict`, `Counter`, `deque`, `namedtuple`, and `dataclass`—the six data structures that cover 90% of pipeline code. Learn when to use each with real pipeline examples.

### 18. DE File I/O *(Free)*
Read and write CSV, JSON, Parquet, and Avro files in Python. Understand format tradeoffs, performance characteristics, and when to use each in production pipelines.

### 19. Working with APIs *(Free)*
Build production-grade API integrations with pagination, rate limiting, retry with exponential backoff, and timeout handling. The four things every API pipeline needs.

### 20. DE Error Handling
Learn fail-graceful error handling for production pipelines—dead-letter queues, circuit breakers, structured logging, and the error handling spectrum from fail-fast to fail-silent.

### 21. Generators & Iterators
Process 50GB files with 50MB of memory using generators. Learn `yield`, generator expressions, chunked reading, and chained generators for memory-efficient pipeline code.

### 22. Decorators
Write reusable decorators for logging, timing, and retry—the three cross-cutting concerns every pipeline function needs. Apply the DRY principle to infrastructure code.

### 23. Context Managers
Prevent resource leaks in pipeline code with context managers. Learn custom context managers for database connections, temporary files, locks, and Spark sessions.

### 24. Concurrency
Parallelize API calls, file downloads, and database queries with `ThreadPoolExecutor`, `ProcessPoolExecutor`, and `asyncio`. Know when to use each and avoid the GIL trap.

### 25. Testing with pytest
Test transformation logic, mock external dependencies, and validate data quality with `pytest`. Learn testing patterns that let you change pipeline code with confidence.

### 26. Packaging & Structure
Structure pipeline code for production with proper project layout, configuration management, dependency pinning, and wheel packaging for Airflow, EMR, and Databricks.

---

## Module 03: Projects (4 Lessons)

### 27. Spotify Pipeline P1 *(Free)*
Build a real-world ETL data pipeline using the Spotify API and AWS. Part 1 covers the architecture overview, Spotify API authentication, and setting up AWS services (S3, Lambda, Glue, Athena).

### 28. Spotify Pipeline P2
Use the Spotipy library to extract playlist data from the Spotify API, parse nested JSON into albums, artists, and songs DataFrames, and transform them for loading.
