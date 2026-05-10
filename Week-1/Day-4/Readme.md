# Week 1 - Day 4

## Objective
The objective of this session was to learn and practice advanced SQL concepts including Window Functions, Common Table Expressions (CTEs), Recursive Queries, Ranking Functions, Running Totals, and Analytical Queries. The session focused on solving real-world business analysis problems using advanced SQL techniques for reporting, ranking, cumulative calculations, and hierarchical data processing.

---

## Tasks Completed
- Created and populated relational database tables:
  - employees
  - customers
  - orders
- Established relationships using Primary Keys and Foreign Keys
- Executed advanced SQL analytical queries
- Practiced ranking and numbering functions
- Implemented running totals and cumulative calculations
- Used LAG() and LEAD() for previous and next row analysis
- Created recursive queries using Recursive CTEs
- Built multiple CTE-based reporting queries
- Performed department-wise and customer-wise analytical operations
- Generated monthly sales trend reports
- Verified query outputs for correctness
- Organized SQL scripts and documentation in GitHub repository structure

---

## Topics Covered

### Window Functions
- `ROW_NUMBER()`
- `RANK()`
- `DENSE_RANK()`
- `NTILE()`
- `LAG()`
- `LEAD()`

### Aggregate Window Operations
- Running Totals
- Moving Average
- Cumulative Sales
- Department Payroll
- Percentage Contribution Calculations

### Common Table Expressions (CTEs)
- Basic CTEs
- Multiple CTEs
- Recursive CTEs

### Advanced SQL Concepts
- Ranking within departments
- Top-N analysis
- Hierarchical employee relationships
- Time-series analysis
- Monthly sales trend analysis
- Customer spending analysis

### SQL Clauses Used
- `WITH`
- `PARTITION BY`
- `OVER()`
- `ORDER BY`
- `GROUP BY`
- `HAVING`
- `LIMIT`
- `UNION`
- `JOIN`

---

## Query Operations Practiced
- Employee salary ranking
- Department-wise salary analysis
- Running totals and cumulative sums
- Previous and next row comparisons
- Customer spending rankings
- Moving averages
- Recursive hierarchy generation
- Top-performing employee analysis
- Monthly sales growth calculations
- Analytical reporting queries

---

## Platform & Tools Used
- MySQL
- DB Fiddle (Online SQL Playground)
- Databricks
- GitHub
- VS Code

---

## Project Files
```bash
schema.sql        -> Table creation and sample data
queries.sql       -> Advanced SQL analytical queries
outputs/          -> Query execution outputs
README.md         -> Documentation for Day 4
```

---

## Learning Outcomes
Through this practice session, I:

- Understood advanced SQL analytical functions
- Learned how Window Functions operate on grouped datasets
- Practiced ranking and row numbering techniques
- Gained experience with cumulative calculations and moving averages
- Learned how to analyze sequential data using LAG() and LEAD()
- Improved understanding of Common Table Expressions (CTEs)
- Practiced Recursive CTEs for hierarchical queries
- Learned how to generate advanced business reports using SQL
- Improved SQL optimization and analytical thinking skills

---

## Challenges Faced
Initially, understanding Window Functions, especially `PARTITION BY`, running totals, and ranking functions, was slightly challenging. Recursive CTEs and analytical queries involving multiple calculations also required careful understanding. After practicing multiple examples and analyzing outputs step-by-step, the concepts became much clearer and easier to implement.

---

## Conclusion
Successfully completed Week 1 - Day 4 advanced SQL practice tasks and developed a strong understanding of analytical SQL concepts including Window Functions, CTEs, recursive queries, ranking systems, and time-series analysis. This session significantly improved advanced SQL querying skills and built a strong foundation for data analytics, data engineering, and business intelligence workflows.
