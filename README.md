📊 Data Warehouse & Analytics Project
This project showcases a complete end-to-end Data Warehouse and Advanced Analytics pipeline built using Microsoft SQL Server, following best practices of Medallion Architecture.

🚀 Project Structure
Data Ingestion
Raw ERP and CRM data (CSV files) were loaded and cleaned to form the Bronze Layer.

Data Transformation & Modeling
Created normalized and enriched tables in the Silver Layer.
Applied Star Schema modeling with Fact and Dimension tables in the Gold Layer.

Exploratory Data Analysis (EDA)
Performed key business explorations:

Dimensions & Measures

Date Range Exploration

Ranking & Performance Analysis

Cumulative & Change over Time Analysis

Data Segmentation

Part-to-Whole Analysis

Advanced Analytics Reports

report_customers.sql: In-depth customer trends and KPIs

report_products.sql: Product-wise sales, orders, and performance

| Filename                        | Description                            |
| ------------------------------- | -------------------------------------- |
| `00_init_database.sql`          | Database setup and initial load        |
| `01_database_exploration.sql`   | Schema overview and integrity checks   |
| `02_dimensions_exploration.sql` | Dimension tables exploration           |
| `04_measures_exploration.sql`   | Analysis of key metrics                |
| `06_ranking_analysis.sql`       | Top-N analysis by sales and quantity   |
| `08_cumulative_analysis.sql`    | Running totals and trends over time    |
| `10_data_segmentation.sql`      | Clustering and segment-based analysis  |
| `12_report_customers.sql`       | Final reporting on customer behavior   |
| `13_report_products.sql`        | Final reporting on product performance |

🧰 Tech Stack
SQL Server 2022

SSMS (SQL Server Management Studio)

Star Schema Modeling

Medallion Architecture (Bronze → Silver → Gold)

📈 Outcomes
Delivered actionable business insights on customers, sales, and products

Built a scalable and analytical-ready data warehouse

Demonstrated advanced SQL techniques for segmentation, ranking, and temporal analysis

