# WEEK 3 – DAY 5
# INTRODUCTION TO DENSE_RANK() IN MYSQL

This practice session explains ranking functions using employee and order datasets.

Topics covered:

- Order date ranking
- Dense salary ranking
- Department-wise dense ranking

---

# Key Learning

DENSE_RANK() assigns rankings without gaps.

Example:

```sql
DENSE_RANK() OVER(
    ORDER BY salary DESC
)
```

---

# Main Scenarios

- Employee dense ranking
- Department salary analysis
- Order tracking

---

# SQL Features Used

```sql
RANK()
DENSE_RANK()
OVER()
PARTITION BY
ORDER BY
```

---

# Practical Applications

- HR systems
- Employee analytics
- Sales reporting
- Business intelligence

---

# Skills Gained

- Dense ranking concepts
- Analytical querying
- Ranking analysis
- Data ordering

---
