# 📁 Day 01: SQL Lesson 1 - SELECT Queries 101

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



> ### 📝 Exercise 1 — Tasks & Solutions
> 
> **1. Find the title of each film**
> ```sql
> SELECT title 
> FROM movies;
> ```
> *Status: ✓ (Completed)*
> 
> ---
> 
> **2. Find the director of each film**
> ```sql
> SELECT director 
> FROM movies;
> ```
> *Status: ✓ (Completed)*
> 
> ---
> 
> **3. Find the title and director of each film**
> ```sql
> SELECT title, director 
> FROM movies;
> ```
> *Status: ✓ (Completed)*
> 
> ---
> 
> **4. Find the title and year of each film**
> ```sql
> SELECT title, year 
> FROM movies;
> ```
> *Status: ✓ (Completed)*
> 
> ---
> 
> **5. Find all the information about each film**
> ```sql
> SELECT * 
> FROM movies;
> ```
> *Status: ✓ (Completed)*
