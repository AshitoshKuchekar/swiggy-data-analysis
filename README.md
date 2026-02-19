🍔 Swiggy Data Analysis Project

This project focuses on analyzing and cleaning a real-world dataset inspired by Swiggy, one of India's leading food delivery platforms.

The dataset contains multiple relational tables covering food items, menus, orders, restaurants, and users.

The objective of this project is to:

Clean and preprocess raw data

Transform and structure relational tables

Perform exploratory data analysis (EDA)

Build an interactive Power BI dashboard

Generate actionable business insights

🛠️ Tools & Technologies Used

Python (Pandas, NumPy, Matplotlib, Seaborn, Plotly)

SQL (Data querying & transformations)

Power BI (Dashboard & Visualization)

Excel / CSV (Raw Data Storage)

📊 Dataset Overview

The dataset consists of 6 relational tables:

Food

Menu

Orders

Orders Type

Restaurant

Users

📌 Dataset Scale

👥 100,000 users

📋 5.2 million rows in Menu table

Multiple relational joins between tables

📂 Tables & Column Structure
🍲 Food Table

Columns:
f_id, item, veg_or_non_veg

📋 Menu Table

Columns:
menu_id, r_id, f_id, cuisine, price

📝 Orders Table

Columns:
order_date, sales_qty, sales_amount, currency, user_id, r_id

🛍️ Orders Type Table

Columns:
order_id, type

🍴 Restaurant Table

Columns:
id, name, country, city, rating, rating_count, cuisine, link, address

👥 Users Table

Columns:
user_id, name, age, gender, marital_status, occupation

🧹 Data Cleaning Process
✅ Null Value Handling

Identified missing values in all tables

Applied appropriate imputation techniques:

Mode for categorical variables

Mean/Median where applicable

Ensured no critical business data was lost

✅ Data Standardization

Standardized column naming conventions

Corrected data types

Removed duplicates

Validated relational integrity between tables

🛠️ Data Formatting & Transformation

Renamed columns for clarity and readability

Removed irrelevant columns

Dropped unnecessary tables

Ensured proper primary & foreign key relationships

Structured data for analytical querying

📊 Power BI Workflow

Imported cleaned datasets into Power BI

Used Power Query for:

Merging tables

Creating calculated columns

Extracting date components (Year, Month, Quarter)

Built relationships between:

Users ↔ Orders

Restaurants ↔ Orders

Menu ↔ Food

Created interactive dashboards with KPIs and filters

📈 Key Business Insights

🥗 Vegetarian options generated 122 million in sales,
which is 7.2% higher than non-vegetarian items

👑 Top 10% of customers contributed nearly 80% of total sales

📍 Tirupati recorded the highest order amount at 43 million

📊 Strong Pareto distribution observed in customer spending behavior

📌 Project Agenda
🧹 Data Cleaning

Handle null values

Validate relationships

Ensure data consistency

🛠️ Data Formatting

Rename columns

Drop unnecessary fields

Improve schema structure

📊 Data Visualization

KPI cards

Sales trends

City-wise analysis

Customer segmentation

Cuisine performance analysis

📁 Project Structure
Swiggy/
│
├── Raw Dataset/
├── Processed Data (Python)/
├── Screenshot Dashboard/
├── swiggy.ipynb
├── Swiggy.pbix
└── README.md

🚀 Project Outcome

This project demonstrates:

Real-world data cleaning skills

Relational data modeling

Business KPI development

SQL-based analysis

Professional dashboard creation in Power BI

It reflects a complete end-to-end Data Analyst workflow suitable for industry-level portfolio presentation.
