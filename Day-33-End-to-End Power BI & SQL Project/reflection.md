# Internet Sales Analysis: End-to-End Power BI & SQL Project

## 📌 Project Overview
This project was born out of a business request to transition from static reports to an interactive visual dashboard. The goal was to analyze three years of internet sales data to track performance against budget, identify top-selling products, and understand customer purchasing behavior across different geographic regions.

## 🛠️ Tech Stack
* SQL (MySQL): Data Extraction, Cleansing, and Transformation.

* Power BI: Data Modeling (Star Schema), DAX for KPIs, and Interactive Dashboard Design.

* Excel: Budget data source.

* CSV: Facts, Customers and Product data source.

## 📋 1. Business Request & User Stories
The Sales Manager requested a shift toward visual reporting to better understand what is being sold, to whom, and when, with a specific focus on comparing performance against a defined 2021 budget.

### 📋 Business Request & User Stories

| No | Role | Request | User Value | Acceptance Criteria |
|:---|:---|:---|:---|:---|
| **1** | Sales Manager | Dashboard overview of internet sales | Follow which customers and products sell best | A Power BI dashboard updating daily |
| **2** | Sales Rep | Detailed sales per customer | Identify top customers for follow-up/upselling | Filterable dashboard by customer |
| **3** | Sales Rep | Detailed sales per product | Track high-performing product lines | Filterable dashboard by product |
| **4** | Sales Manager | Sales vs. Budget comparison | Monitor performance against financial goals | KPI visuals and graphs comparing Sales to Budget |

## 🗄️ 2. Data Cleansing & Transformation (SQL)
To ensure the data was "ready for BI," I performed extensive cleansing in MySQL. This involved filtering out unnecessary columns and renaming fields for better readability in Power BI.

**Key Steps:**

* Fact vs. Dimension Identification: Segregated core transaction data (FACT_InternetSales) from descriptive attributes (DIM_Products, DIM_Customers, DimCalendar).

* SQL Formatting: Used a code beautifier to ensure the scripts were professional and maintainable.

* Date Alignment: Cleansed the DimDate table to ensure a continuous 2-year look-back period as requested by the business.

![Optional: Insert a code block here with one of your SQL scripts, e.g., the DIM_Date or DIM_Product transformation]()

## 📐 3. Data Modeling
After importing the cleaned tables into Power BI, I established a Star Schema to optimize performance.

Relationship Management: Created 1-to-many relationships between the Dimension tables and the Fact table.

![](https://github.com/omolola-A/120-days-data-analytics-journey/blob/main/Day-32b.png)
Measures Table: Created a dedicated key_measures table to house all DAX calculations (Total Sales, Budget, Variance).

## 📊 4. The Dashboard (Visual Analysis)
The final solution consists of three specialized report pages:

**I. Sales Overview**

![](https://github.com/omolola-A/120-days-data-analytics-journey/blob/main/Day-32.png)

A high-level executive view focusing on performance vs. budget.

Insight: In 2021, the company exceeded its $21.1M budget by $1.14M.

Insight: The "Bikes" category accounts for over 95% of total revenue.

**II. Customer Details** 
A deep dive into demographics and purchasing patterns.

Feature: Includes gender distribution and a "Top 10 Customers" bar chart to identify high-value clients.

![](https://github.com/omolola-A/120-days-data-analytics-journey/blob/main/Day-33.png)

**III. Product Details**
Focused on inventory and product-line performance.

Feature: Ability to filter by Product Category and Sub-category.

![](https://github.com/omolola-A/120-days-data-analytics-journey/blob/main/Day-33b.png)

## 💡 Key Insights
* Revenue Growth: Sales scaled from $5.8M (2019) to a peak of $22.2M (2021).

* Market Leadership: London and Paris consistently lead as the top-performing cities across all three years.

* Seasonality: A recurring sales surge is visible starting in July, peaking in December, suggesting strong year-end demand.

PowerBi Link: https://app.powerbi.com/links/XDyJaNHIvP?ctid=f3dd754b-d19f-4c2c-9144-105b4d4cad00&pbi_source=linkShare
