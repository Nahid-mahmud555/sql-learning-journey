

#  Day 01: SQL Lesson 1 - SELECT Queries 101

---

##  What Did I Learn Today? (Key Learnings)

* **What is a Query?** A query is a command given to a database to declare what data we are looking for, where to find it, and how to transform it.
* **Database Structure (Table, Row, Column):**
  * **Table:** Represents an entity (e.g., `movies`).
  * **Row:** Represents a specific instance in the table (e.g., an individual movie record).
  * **Column:** Represents the common properties shared by all instances (e.g., title, director, year).
* **Best Practice:** Avoid using `SELECT *` on massive production databases in the real world to prevent performance bottlenecks; always query only the specific columns you need.

---

##  Commands & Syntax Learned

1. **Select Specific Columns:**
   ```sql
   SELECT column_name, another_column 
   FROM table_name;

   ## 📊 Table: movies

| id | title | director | year | length_minutes |
| :--- | :--- | :--- | :--- | :--- |
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

## 📝 Exercise 1 — Tasks

- [x] Find the title of each film
- [x] Find the director of each film
- [x] Find the title and director of each film
- [x] Find the title and year of each film
- [x] Find all the information about each film

