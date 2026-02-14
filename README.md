Data Analytics Project
Overview

This project demonstrates an end-to-end data analytics workflow starting from raw data loading to visualization and reporting.
The goal is to analyze customer purchase behavior, extract insights using SQL and Python, and present the results in an interactive dashboard and presentation format.

Dataset

Source: Customer purchase dataset (CSV format)

Content Includes:

Customer ID

Gender

Age Group

Purchase Amount

Product Category

Review Rating

Shipping Type

Discount Applied

Subscription Status

Previous Purchases

Tools & Technologies

Python – Data loading, cleaning, and EDA

Pandas / NumPy – Data manipulation

Matplotlib / Seaborn – Visualization

SQL (PostgreSQL / MySQL / SQL Server) – Querying and aggregations

Power BI – Dashboard creation

Microsoft PowerPoint / Gamma – Final presentation

Steps
1. Data Loading

Imported CSV dataset into Python using Pandas.

Stored cleaned data into a SQL database.

2. Data Cleaning

Removed duplicates and null values.

Standardized column names.

Converted data types where necessary.

3. Exploratory Data Analysis (EDA)

Gender revenue comparison

Discount impact analysis

Product rating trends

Shipping type spending patterns

Subscription vs non-subscription spending

4. SQL Analysis

Executed multiple analytical queries such as:

Total revenue by gender

Top-rated products

Discount usage percentage

Customer segmentation (New, Returning, Loyal)

Top products per category

Revenue contribution by age group

5. Dashboard

Built an interactive Power BI dashboard including:

Revenue breakdowns

Customer segmentation charts

Product performance visuals

Discount and subscription insights

6. Reporting & Presentation

Created a summarized analytical report.

Designed a presentation using Gamma / PowerPoint to communicate findings.

Dashboard Features

KPI cards (Total Revenue, Avg Purchase, Subscribers)

Bar and Pie charts for demographic analysis

Product performance rankings

Filters for category, gender, and subscription status

Results & Insights

Clear spending differences between genders and shipping types.

Loyal and subscribed customers contribute higher revenue.

Certain product categories dominate discount usage.

Repeat buyers show higher likelihood of subscription.

Age groups vary significantly in revenue contribution.

How to Run
Python
pip install pandas numpy matplotlib seaborn sqlalchemy psycopg2
python analysis.py

SQL

Create database in PostgreSQL / MySQL / SQL Server.

Import cleaned dataset.

Execute the provided SQL queries.

Power BI

Connect Power BI to the database or CSV.
Conclusion
This project showcases practical skills in data preprocessing, SQL analytics, visualization, and business insight generation. It reflects the full lifecycle of a real-world data analytics task and is suitable for academic, portfolio, or recruiter review.

Load tables.

Apply visuals and filters as designed.
