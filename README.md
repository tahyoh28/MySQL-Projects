# 🛠️ MySQL Project – Sakila Database SQL Exercises

## 📝 Project Summary
This project explores SQL querying techniques using the **Sakila sample database**, a fictional DVD rental system. The workbook demonstrates essential SQL skills including table exploration, filtering, pattern matching, joins, aggregations, and group-based logic through practical business questions.

---

## 🎯 Objectives
- Learn to **explore relational tables** with basic queries
- Apply **string filters and pattern matching** using `LIKE`
- Use **INNER JOINs** to combine data across multiple tables
- Aggregate and group data using `GROUP BY`, `HAVING`, and functions like `COUNT()`, `SUM()`, and `AVG()`
- Retrieve business insights such as **payment summaries**, **staff performance**, and **film popularity**

---

## 🔍 SQL Exercises Overview

### 🔹 Basic Exploration & Filtering (Q1–Q10)
- Retrieve actor names and filter by specific conditions (e.g., first name “Joe” or last name containing “GEN” or “LI”)
- Find long-duration films and customers with specific name patterns
- Use `IN` to filter countries and `LIKE` for flexible searches
- Get film descriptions ending with certain keywords

### 🔹 Aggregations & Advanced Filtering (Q11–Q14)
- Use aggregate functions like `COUNT(DISTINCT ...)` to find unique actor last names
- Determine film due dates and calculate average runtime
- Explore payment records from a specific date

### 🔹 JOIN Operations & Business Insights (Q15–Q27)
- **INNER JOINs** to combine:
  - Staff and address details
  - Staff payments with dates and totals
  - Film and actor participation counts
  - Inventory and film data (e.g., copies of "Hunchback Impossible")
- **Customer payment tracking:**
  - Show total paid by each customer
  - Alphabetically sort payment data
- **Analytical queries:**
  - Find the actor in the most films
  - Discover the most common actor surname
  - Identify unique and repeated actor last names using `HAVING`

---

## 🗃️ Tables Used
- `actor`, `film`, `film_actor`, `customer`, `payment`, `staff`, `address`, `inventory`, `country`

---

## 🧠 Key Takeaways
- SQL enables detailed, flexible queries to derive business insight from structured data
- Filtering, joining, and aggregating are powerful tools to answer real-world data questions
- The **Sakila** database is a rich learning environment with realistic business relationships

---

## 🛠️ Tools & Features
- **MySQL Workbench** for database querying and reverse engineering schema
- **Sakila Sample Database** as the relational data source
- SQL Features: `SELECT`, `WHERE`, `LIKE`, `IN`, `JOIN`, `GROUP BY`, `HAVING`, `ORDER BY`, aggregate functions
