# WEEK 3 – DAY 1
# INTRODUCTION TO ROW_NUMBER() IN MYSQL

This practice session focuses on the ROW_NUMBER() window function in MySQL using employee datasets.

Concepts covered:

- Sequential numbering
- Salary-based ordering
- Department-wise numbering
- Joining date analysis

---

# Key Learning

ROW_NUMBER() generates a unique number for every row based on sorting conditions.

Example:

```sql
ROW_NUMBER() OVER(
    ORDER BY salary DESC
)
```

---

# Main Scenarios

- Employee salary ordering
- Department-wise employee tracking
- Latest employee joining analysis
- Department joining sequence analysis

---

# SQL Features Used

```sql
ROW_NUMBER()
OVER()
PARTITION BY
ORDER BY
```

---

# Practical Applications

- HR analytics
- Payroll systems
- Employee reporting
- Data organization

---

# Database Support

- MySQL 8+
- MariaDB

---

# Skills Gained

- Window function basics
- Sorting techniques
- Department analysis
- Analytical SQL querying

---
