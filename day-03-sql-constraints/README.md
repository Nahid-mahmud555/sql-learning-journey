# SQL Learning Journey - Day 3: Queries with Constraints (Part 2)

Welcome to **Day 3** of my SQL learning journey.

Today's practice focuses on text-data operators, case-insensitive comparisons, and wildcard pattern matching.

---

## Topics Covered

* Case-sensitive vs Case-insensitive comparisons (`=`, `!=`, `LIKE`, `NOT LIKE`)
* Wildcard pattern matching (`%`, `_`)
* List filtering (`IN`, `NOT IN`)

---

## Database Schema: `movies`

| id | title               | director       | year | length_minutes |
| :- | :------------------ | :------------- | :--- | :------------- |
| 1  | Toy Story           | John Lasseter  | 1995 | 81             |
| 2  | A Bug's Life        | John Lasseter  | 1998 | 95             |
| 3  | Toy Story 2         | John Lasseter  | 1999 | 93             |
| 4  | Monsters, Inc.      | Pete Docter    | 2001 | 92             |
| 5  | Finding Nemo        | Andrew Stanton | 2003 | 107            |
| 6  | The Incredibles     | Brad Bird      | 2004 | 116            |
| 7  | Cars                | John Lasseter  | 2006 | 117            |
| 8  | Ratatouille         | Brad Bird      | 2007 | 115            |
| 9  | WALL-E              | Andrew Stanton | 2008 | 104            |
| 10 | Up                  | Pete Docter    | 2009 | 101            |
| 11 | Toy Story 3         | Lee Unkrich    | 2010 | 103            |
| 12 | Cars 2              | John Lasseter  | 2011 | 120            |
| 13 | Brave               | Brenda Chapman | 2012 | 102            |
| 14 | Monsters University | Dan Scanlon    | 2013 | 110            |
| 87 | WALL-G              | Brenda Chapman | 2042 | 97             |

---

## Practice Exercises

### 1. Find all the Toy Story movies

```sql
-- Write your query here
```

### 2. Find all the movies directed by John Lasseter

```sql
-- Write your query here
```

### 3. Find all the movies (and director) not directed by John Lasseter

```sql
-- Write your query here
```

### 4. Find all the WALL-* movies

```sql
-- Write your query here
```

---

## Environment

* Database: Pixar Movies Database
* Focus: Text filtering and pattern matching
* Concepts Practiced: `LIKE`, `NOT LIKE`, `%`, `_`, `IN`, `NOT IN`

---

## Learning Objectives

By completing these exercises, I aim to:

* Understand how SQL handles text-based filtering
* Practice pattern matching using wildcards
* Learn when to use `LIKE` and `NOT LIKE`
* Explore filtering with multiple values using `IN` and `NOT IN`
* Improve query-writing skills for real-world datasets

---
