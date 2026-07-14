# Small Business SQL Data Warehouse Project

Welcome to my personal implementation of a modern SQL Data Warehouse! This project demonstrates end-to-end data engineering skills, from raw data ingestion to dimensional modeling and analytical querying.

## Project Overview
This project integrates scattered and inconsistent data from two source systems (**ERP** and **CRM**) into a centralized SQL Server Data Warehouse. 
I implemented a **Medallion Architecture** (Bronze ➡️ Silver ➡️ Gold) to clean, transform, and model the data into a query-optimized Star Schema.

## Tech Stack & Skills
- **Database Engine:** Microsoft SQL Server (T-SQL)
- **Architecture:** Medallion Architecture (Bronze/Silver/Gold)
- **Data Modeling:** Dimensional Modeling (Star Schema with Facts & Dimensions)
- **Version Control:** Git & GitHub

## Data Architecture
Explain briefly how the data flows:
1. **Bronze Layer:** Raw data ingestion from CSV datasets (ERP & CRM).
2. **Silver Layer:** Data cleansing, deduplication, and standardization.
3. **Gold Layer:** Final Star Schema designed for analytics and BI tool consumption.

*(Optional: Insert an architecture diagram here! You can design one on Draw.io and save it in your `docs/` folder)*

## How to Run this Project
Give short instructions on how someone can clone your repo and run the `init_database.sql` and scripts.

## What I Learned & Personal Touches
In this section, write 2-3 sentences about your personal learning journey:
- *"Through this project, I mastered the differences between Inmon and Kimball data warehouse design methodologies."*
- Did you add anything? (e.g., *"I added custom SQL unit tests in the `/tests/` folder to verify data quality after the Silver layer transformation."*)

## Credits & Acknowledgments
This project was built as part of my learning journey following the excellent "SQL Data Warehouse Project" course by **Baraa Khatib Salkini** (Data With Baraa). 
- Original Creator's Repository: [DataWithBaraa/sql-data-warehouse-project](https://github.com/DataWithBaraa/sql-data-warehouse-project)
