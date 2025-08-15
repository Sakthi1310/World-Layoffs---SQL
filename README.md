📊 Layoffs Data Cleaning & Analysis (MySQL)
📌 Project Overview

This project involves data cleaning and exploratory data analysis (EDA) on a global layoffs dataset using MySQL.
The primary goal was to clean raw, inconsistent, and incomplete data and then extract meaningful insights through SQL queries.

🛠 Skills & Tools Used

SQL (MySQL) – Data cleaning, transformation, and analysis

CTEs & Window Functions – Ranking, rolling totals, deduplication

String Functions – TRIM(), SUBSTRING(), STR_TO_DATE()

Aggregations – SUM(), AVG(), MAX(), MIN()

Data Filtering – Handling NULLs, blanks, duplicates

🔹 Data Cleaning Steps

Removed duplicates using ROW_NUMBER() in a staging table.

Standardized text data – trimmed spaces, fixed inconsistent naming (Crypto% → Crypto, United States. → United States).

Fixed date format using STR_TO_DATE() and converted to DATE type.

Handled NULL or blank values in key fields by filling from other records or removing rows where both layoffs fields were null.

Dropped unnecessary columns after cleaning (row_num).

📈 Exploratory Data Analysis

Companies with the highest layoffs overall and per year.

Industries & countries most affected.

Layoffs trend over time (monthly & yearly).

Rolling totals of layoffs to visualize cumulative impact.

Stages of companies (Startup, Post-IPO, etc.) with the most layoffs.

📂 Files in Repository

layoffs.sql – SQL scripts for cleaning & analysis.

layoffs.csv – Raw dataset.

README.md – Project documentation.

🚀 Key Insights

Some companies laid off 100% of staff.

Tech & Crypto industries were among the most affected.

Layoffs peaked in specific months, reflecting economic downturns.
