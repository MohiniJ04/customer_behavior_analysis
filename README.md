Customer Shopping Behavior Analysis

End-to-End Data Analytics Project

Overview

This project analyzes customer shopping behavior using transactional data to uncover insights into spending patterns, product preferences, customer segments, and subscription behavior. The analysis follows a complete data analytics workflow—starting with Python-based data preparation, moving to SQL-driven business analysis, and concluding with interactive dashboards and professional reporting.

The goal is to support data-driven business decisions related to customer retention, pricing strategy, and targeted marketing.

Dataset

Records: 3,900 customer purchases

Columns: 18

Data Type: Structured transactional data

Key Features:

Customer details: Age, Gender, Location, Subscription Status

Purchase information: Item Purchased, Category, Purchase Amount, Season

Shopping behavior: Discounts, Promo Codes, Previous Purchases, Frequency

Feedback & logistics: Review Rating, Shipping Type

Data Quality

Missing values found in the Review Rating column

No major structural issues after cleaning

Tools & Technologies

Python: Pandas, NumPy, Matplotlib, Seaborn

Jupyter Notebook: Data analysis and documentation

SQL Server / PostgreSQL: Data storage and querying

SQL: Business-focused data analysis

Power BI: Interactive dashboard creation

Gamma: Professional presentation (PPT)

Project Steps
1. Data Loading & Initial Exploration (Python)

Imported the dataset using Pandas

Reviewed structure, data types, and summary statistics

Checked for missing and inconsistent values

2. Exploratory Data Analysis (EDA)

Analyzed purchase distributions and customer demographics

Studied relationships between discounts, subscriptions, and spending

Identified trends across age groups, gender, and product categories

3. Data Cleaning & Feature Engineering

Imputed missing values in Review Rating using category-level medians

Standardized column names using snake_case

Created new features:

age_group (binned customer ages)

Purchase behavior indicators

Removed redundant columns after consistency checks

Prepared final dataset for database insertion

4. SQL-Based Business Analysis

The cleaned dataset was loaded into the SQL database and analyzed using SQL queries to answer key business questions, including:

Revenue comparison by gender

Spending behavior of discount users

Top-rated and most purchased products

Subscriber vs. non-subscriber spending patterns

Customer segmentation (New, Returning, Loyal)

Revenue contribution by age group

Shipping type impact on purchase value

5. Power BI Dashboard

An interactive dashboard was built using Power BI, connected directly to the SQL database.
Key features include:

KPIs for revenue, purchases, and customer segments

Product and category-level insights

Filters for demographics, subscription status, and shipping type

Clean, business-friendly visual layout

6. Reporting & Presentation

A structured analytical report was created to summarize findings

A professional presentation (PPT) was designed using Gamma to communicate insights clearly to stakeholders

Dashboard Highlights

Revenue and customer segmentation overview

Top-performing products and categories

Subscription and discount impact analysis

Age group and shipping preference insights

Key Results & Insights

Subscribers contribute higher average revenue than non-subscribers

Loyal customers show significantly higher lifetime value

Certain products rely heavily on discounts, indicating pricing sensitivity

Specific age groups and shipping types generate higher revenue

High-rated products align strongly with repeat purchases

Business Recommendations

Strengthen subscription programs with exclusive benefits

Introduce loyalty rewards for repeat customers

Optimize discount strategies to protect margins

Promote top-rated and high-performing products

Focus marketing efforts on high-revenue customer segments

How to Run the Project

Clone the repository

Open the Jupyter Notebook and install required Python libraries

Run the notebook for EDA and data cleaning

Load the cleaned dataset into SQL Server/PostgreSQL

Execute SQL queries for analysis

Open the Power BI file and refresh the database connection

Review the report and Gamma presentation

Skills Demonstrated

Data Cleaning & EDA (Python)

SQL Querying & Database Integration

Business-Oriented Data Analysis

Interactive Dashboard Development

Insight Communication & Storytelling

End-to-End Data Analytics Workflow
