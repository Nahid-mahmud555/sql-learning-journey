# Day 02: SQL Lesson 2 - Queries with Constraints (Pt. 1)

---

## 🎯 What Did I Learn Today? (Key Learnings)

### 1. The Problem with Large Datasets
In real-world production databases, tables can contain millions of rows. Reading every row whenever we need information is inefficient, slow, and consumes unnecessary resources.

### 2. The `WHERE` Clause
The `WHERE` clause is used to filter specific records from a table. SQL evaluates each row against a condition and only returns the rows that satisfy that condition.

### 3. Performance Benefits
Applying constraints reduces the amount of data returned, making results easier to analyze while also improving query performance by minimizing unnecessary processing and data transfer.

### 4. Logical Operators (`AND` / `OR`)
Logical operators allow multiple conditions to be combined:

- `AND` → All conditions must be true.
- `OR` → At least one condition must be true.

### 5. SQL Readability Best Practice
A common SQL convention is:

- SQL Keywords → `SELECT`, `FROM`, `WHERE`, `AND`, `OR`
- Table & Column Names → `movies`, `title`, `year`

This improves readability and maintainability.

---

# 📚 Commands & Syntax Learned

## 1. Select Query with Constraints

```sql
SELECT column_name, another_column
FROM table_name
WHERE condition
  AND/OR another_condition;
```

## 2. Numerical & Comparison Operators

| Operator | Meaning | Example |
|-----------|---------|---------|
| `=` | Equal to | `id = 6` |
| `!=` | Not equal to | `id != 6` |
| `<` | Less than | `year < 2000` |
| `<=` | Less than or equal to | `year <= 2000` |
| `>` | Greater than | `length_minutes > 100` |
| `>=` | Greater than or equal to | `year >= 2010` |
| `BETWEEN ... AND ...` | Value exists within a range (inclusive) | `year BETWEEN 2000 AND 2010` |
| `NOT BETWEEN ... AND ...` | Value does not exist within a range | `year NOT BETWEEN 2000 AND 2010` |
| `IN (...)` | Value exists in a list | `id IN (1, 3, 5)` |
| `NOT IN (...)` | Value does not exist in a list | `id NOT IN (1, 3, 5)` |

---

# ⚠️ Common Gotcha Avoided

## Semicolon Placement (`;`)

A semicolon marks the end of an SQL statement.

❌ Incorrect:

```sql
SELECT *
FROM movies;
WHERE id = 6;
```

✅ Correct:

```sql
SELECT *
FROM movies
WHERE id = 6;
```

Always place the semicolon at the very end of the complete query.

---

# 📊 Practice Dataset: `movies`

| id | title | director | year | length_minutes |
|----|--------|-----------|------|---------------|
| 1 | Toy Story | John Lasseter | 1995 | 81 |
| 2 | A Bug's Life | John Lasseter | 1998 | 95 |
| 3 | Toy Story 2 | John Lasseter | 1999 | 93 |
| 4 | Monsters, Inc. | Pete Docter | 2001 | 92 |
| 5 | Finding Nemo | Andrew Stanton | 2003 | 107 |
| 6 | The Incredibles | Brad Bird | 2004 | 116 |
| 7 | Cars | John Lasseter | 2006 | 117 |
| 8 | Ratatouille | Brad Bird | 2007 | 115 |
| 9 | WALL-E | Andrew Stanton | 2008 | 104 |
| 10 | Up | Pete Docter | 2009 | 101 |

---

# 📝 Practice Questions

1. Find the movie with a row `id` of 6

2. Find the movies released in the `year`s between 2000 and 2010

3. Find the movies **not** released in the `year`s between 2000 and 2010

4. Find the first 5 Pixar movies and their release `year`

---

# 🚀 Day 02 Summary

Today I learned how to filter data using the `WHERE` clause, apply comparison operators, work with ranges using `BETWEEN`, exclude ranges using `NOT BETWEEN`, and understand why query constraints are important for both readability and database performance. I also practiced retrieving specific records from a dataset and learned proper SQL syntax conventions to avoid common mistakes.
