# WEEK 3 – DAY 3
# RANK() FUNCTION IN MYSQL

This project explains how to use the RANK() function with employee and order data.

Topics covered:

- Salary ranking
- Department ranking
- Joining date ranking
- Order amount ranking

---

# Key Learning

RANK() assigns positions to rows based on sorting conditions.

Duplicate values receive the same rank.

Example:

```sql
RANK() OVER(
    ORDER BY salary DESC
)
```

---

# Main Scenarios

- Employee salary comparison
- Department-wise ranking
- Employee joining analysis
- Order amount comparison

---

# SQL Features Used

```sql
RANK()
OVER()
PARTITION BY
ORDER BY
```

---

# Business Use Cases

- Employee performance tracking
- Sales analysis
- HR reporting
- Salary comparison systems

---

# Skills Gained

- Ranking concepts
- Analytical SQL
- Reporting queries
- Window function practice

---
