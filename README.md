# 🎵 Music Store SQL Analysis

A **SQL-based data analysis project** using **PostgreSQL** to analyze a digital music store's customer behavior, sales performance, artists, genres, and geographic trends.

The project focuses on solving real-world business questions using SQL queries ranging from **Easy to Moderate and Advanced levels**.

---

## 📌 Project Overview

The objective of this project is to analyze the Music Store database and extract meaningful business insights using SQL.

The analysis helps answer questions related to:

* 👨‍💼 Employee hierarchy
* 🌍 Invoice distribution by country
* 💰 Sales and invoice values
* 🏙️ Top-performing cities
* 👤 Customer spending
* 🎸 Rock music listeners
* 🎤 Top Rock artists
* 🎵 Track duration analysis
* 💳 Customer spending by artist
* 🌎 Most popular genres by country
* 🏆 Top customers by country

The project uses **PostgreSQL** as the relational database management system.
Schema- Music Store Database  
![MusicDatabaseSchema](https://user-images.githubusercontent.com/112153548/213707717-bfc9f479-52d9-407b-99e1-e94db7ae10a3.png)
---

## 🛠️ Technologies & Tools

| Tool          | Purpose                                 |
| ------------- | --------------------------------------- |
| 🐘 PostgreSQL | Database & SQL queries                  |
| 🖥️ pgAdmin 4 | Database management & query execution   |
| 🔗 SQL        | Data analysis and business insights     |
| 🐙 GitHub     | Project documentation & version control |

---

## 🗄️ Database Schema

The project is based on a relational **Music Store Database** containing information about customers, invoices, tracks, albums, artists, genres, employees, playlists, and related entities.

### Database Structure

```text
Music Store Database
│
├── Customer
├── Invoice
├── InvoiceLine
├── Track
├── Album
├── Artist
├── Genre
├── MediaType
├── Playlist
├── PlaylistTrack
└── Employee
```

The relationships between these tables allow SQL queries to connect customers, purchases, tracks, artists, and genres for analysis.

---

## 📊 Analysis Categories

The SQL questions are divided into three difficulty levels:

### 🟢 Easy

Basic SQL queries involving filtering, sorting, aggregation, and grouping.

Examples:

1. Find the **senior-most employee** based on job title.
2. Find the **country with the most invoices**.
3. Identify the **top invoice values**.
4. Find the **city with the highest total invoice amount**.
5. Find the **customer who has spent the most money**.

These questions focus on fundamental SQL concepts such as:

```text
SELECT
WHERE
ORDER BY
GROUP BY
SUM()
COUNT()
LIMIT
```

---

### 🟡 Moderate

Intermediate queries involving multiple tables, joins, aggregation, and subqueries.

Examples:

1. Find customers who listen to **Rock music**.
2. Find the **Top 10 Rock artists** based on track count.
3. Find tracks whose duration is **longer than the average song length**.

Important concepts:

```text
INNER JOIN
LEFT JOIN
GROUP BY
HAVING
Subqueries
Aggregate Functions
ORDER BY
```

The project specifically analyzes Rock listeners, Rock artists, and tracks above the average song duration.

---

### 🔴 Advanced

Advanced SQL queries are used to identify business insights across multiple dimensions.

Examples:

#### 1. Customer Spending by Artist

Determine how much each customer has spent on individual artists.

**Output:**

```text
Customer Name
Artist Name
Total Amount Spent
```

#### 2. Most Popular Genre by Country

Determine the most purchased music genre for every country.

If multiple genres have the same maximum number of purchases, all tied genres should be returned.

#### 3. Top Customer by Country

Find the customer who spent the most money in each country.

If multiple customers have the same highest spending amount, all tied customers should be returned.

These advanced problems involve concepts such as:

```text
Multiple JOINs
CTEs
Subqueries
Aggregate Functions
Window Functions
PARTITION BY
Ranking
Handling Ties
```

---

## 🧠 SQL Concepts Practiced

This project helped strengthen the following SQL concepts:

* SELECT statements
* WHERE filtering
* ORDER BY
* GROUP BY
* HAVING
* DISTINCT
* LIMIT
* Aggregate functions

  * `COUNT()`
  * `SUM()`
  * `AVG()`
  * `MAX()`
  * `MIN()`
* INNER JOIN
* LEFT JOIN
* Multiple-table JOINs
* Subqueries
* Common Table Expressions (CTEs)
* Window Functions
* `PARTITION BY`
* Ranking
* Data aggregation
* Handling ties
* Business-oriented SQL analysis

---

## 📁 Project Structure

```text
Music-Store-SQL-Analysis/
│
├── README.md
│
├── dataset/
│   └── music_store_database
│
├── sql/
│   ├── easy_queries.sql
│   ├── moderate_queries.sql
│   └── advanced_queries.sql
│
├── schema/
│   └── music_store_schema.png
│
└── screenshots/
    └── query_outputs/
```

---

## 🔍 Sample Business Questions

Some of the key questions answered through SQL include:

```sql
-- Who is the senior-most employee?

-- Which country has the most invoices?

-- Which city generates the highest revenue?

-- Who is the highest-spending customer?

-- Who are the top Rock artists?

-- Which tracks are longer than the average track?

-- How much has each customer spent on each artist?

-- What is the most popular genre in each country?

-- Who is the highest-spending customer in each country?
```

---

## 📈 Business Insights

The analysis can help a music store understand:

### Customer Behavior

Identify high-value customers and understand their purchasing patterns.

### Sales Performance

Analyze invoice totals and identify high-performing cities and countries.

### Music Preferences

Determine popular genres and identify customers interested in specific genres.

### Artist Performance

Identify artists with a high number of tracks and analyze customer spending by artist.

### Geographic Trends

Compare customer purchasing behavior and genre preferences across countries.

---

## 🎯 Project Objective

The primary objective is to use SQL to transform raw relational data into meaningful business information that can support decision-making and help understand the store's business growth.

---

## 🚀 How to Run the Project

### 1. Install PostgreSQL

Install PostgreSQL and **pgAdmin 4**.

### 2. Create the Database

Create a new PostgreSQL database:

```sql
CREATE DATABASE music_store;
```

### 3. Import the Dataset

Load the Music Store database/schema into PostgreSQL.

### 4. Open pgAdmin 4

Connect to:

```text
PostgreSQL
    ↓
music_store
    ↓
Query Tool
```

### 5. Execute SQL Queries

Open the SQL files from the project:

```text
sql/
├── easy_queries.sql
├── moderate_queries.sql
└── advanced_queries.sql
```

Run the queries in pgAdmin 4 and analyze the results.

---

## 📚 Learning Outcomes

Through this project, I practiced:

* Writing SQL queries for real-world business problems
* Working with relational databases
* Joining multiple tables
* Performing aggregations
* Using subqueries and CTEs
* Applying advanced SQL techniques
* Analyzing customer purchasing behavior
* Finding top-performing customers, artists, genres, and locations
* Translating business questions into SQL queries

---

## 👨‍💻 Author

**Jayant Bhoyar**

🎯 Aspiring Data Analyst

### Skills

```text
SQL | PostgreSQL | Power BI | Python | Excel | Data Analysis
```

---

## ⭐ Project Highlights

```text
📌 Database       : Music Store
🐘 RDBMS          : PostgreSQL
🖥️ Tool           : pgAdmin 4
📊 Difficulty     : Easy → Moderate → Advanced
🔎 Focus          : SQL & Business Data Analysis
```

---

## 📌 Keywords

`PostgreSQL` `SQL` `pgAdmin4` `DataAnalysis` `MusicStore` `Database` `SQLQueries` `DataAnalytics` `CTE` `Subquery` `WindowFunctions` `Joins` `BusinessAnalytics`
