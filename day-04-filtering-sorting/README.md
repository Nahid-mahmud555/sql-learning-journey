# SQL Learning Journey - Day 4: Filtering and Sorting Query Results

Welcome to **Day 4** of my SQL learning journey.

Today's practice focuses on handling unique results, sorting data, and limiting query outputs.

---

## Topics Covered

* Removing duplicate records using `DISTINCT`
* Sorting query results in ascending or descending order using `ORDER BY` (`ASC` / `DESC`)
* Limiting data subsets using `LIMIT` and `OFFSET`

---

## Database Schema: `movies` (Scrambled Order)

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

### 1. List all directors of Pixar movies (alphabetically), without duplicates

```sql id="r3n1f7"
-- Write your query here
```

### 2. List the last four Pixar movies released (ordered from most recent to least)

```sql id="2g8mde"
-- Write your query here
```

### 3. List the first five Pixar movies sorted alphabetically

```sql id="d7c4qp"
-- Write your query here
```

### 4. List the next five Pixar movies sorted alphabetically

```sql id="f9k2ws"
-- Write your query here
```

---

## Environment

* Database: Pixar Movies Database (Scrambled Edition)
* Focus: Filtering unique records and sorting query results
* Concepts Practiced: `DISTINCT`, `ORDER BY`, `ASC`, `DESC`, `LIMIT`, `OFFSET`

---

## Learning Objectives

By completing these exercises, I aim to:

* Understand how to remove duplicate values using `DISTINCT`
* Sort records effectively with `ORDER BY`
* Control result ordering using ascending and descending sorting
* Retrieve specific subsets of data using `LIMIT`
* Navigate larger datasets using `OFFSET`
* Write cleaner and more efficient SQL queries

---
