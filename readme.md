# E-Commerce Sales Data Analysis Project
# Author: Muhammad Shahbaz Khan

# Tools: Python, Pandas, SQL, Matplotlib, Seaborn, Jupyter Notebook
## Project Overview

This project focuses on analyzing an e-commerce sales dataset through four key stages of the data analytics workflow:

1. Data Cleaning & Data Understanding
2. Exploratory Data Analysis (EDA)
3. SQL-Based Data Analysis
4. Data Visualization

The objective was to transform raw transactional data into meaningful business insights that can support decision-making and improve business performance.

---

## Dataset Information

* Total Records: 1,200
* Total Columns: 14
* Dataset Type: E-Commerce Orders Dataset

### Features Included

* Order ID
* Order Date
* Customer ID
* Product
* Quantity
* Unit Price
* Shipping Address
* Payment Method
* Order Status
* Tracking Number
* Items in Cart
* Coupon Code
* Referral Source
* Total Price

---

# Project 1: Data Cleaning & Data Understanding

### Tasks Performed

* Checked dataset structure and data types
* Identified missing values
* Verified duplicate records
* Examined data consistency
* Prepared dataset for analysis

### Key Findings

* Dataset contained 1,200 rows and 14 columns.
* No duplicate rows were found.
* No duplicate Order IDs were detected.
* Coupon_Code contained 309 missing values.
* All remaining columns were complete.
* Missing coupon values indicate many customers placed orders without promotional offers.
* Dataset quality was high and required minimal preprocessing.

---

# Project 2: Exploratory Data Analysis (EDA)

### Revenue Analysis

* Total Revenue: 1,264,761.96
* Average Order Value: 1,053.29
* Highest Order Value: 3,456.40
* Lowest Order Value: 11.39

### Product Performance

* Chair generated the highest revenue.
* Desk ranked second.
* Laptop ranked third.
* Phone generated the lowest revenue.

### Payment Method Analysis

* Online Payment was the most frequently used method.
* Cash, Credit Card, and Debit Card showed similar usage patterns.
* Customers demonstrated a preference for digital payments.

### Order Status Analysis

* Cancelled Orders: 250
* Returned Orders: 247

High cancellation and return rates suggest potential issues related to customer satisfaction, order fulfillment, or delivery processes.

### Coupon Analysis

* Orders with Coupons: 891
* Orders without Coupons: 309

Revenue Generated:

* Coupon Users: 942,360
* Non-Coupon Users: 322,401

Coupon campaigns significantly increased customer spending and overall revenue.

### Referral Source Analysis

Top customer acquisition channels:

1. Social Media
2. Email Marketing
3. Google
4. Facebook
5. Referral Traffic

The business benefits from diversified marketing channels.

---

# Project 3: SQL Analysis

### SQL Concepts Applied

* SELECT
* WHERE
* ORDER BY
* GROUP BY
* COUNT()
* SUM()
* AVG()

### Objectives

* Analyze revenue performance
* Evaluate product sales
* Examine customer acquisition channels
* Measure payment method usage
* Investigate order status trends

SQL queries were used to extract actionable business insights from the dataset.

---

# Project 4: Data Visualization

### Visualizations Created

* Bar Charts
* Line Charts
* Pie Charts
* Histograms
* Box Plots

### Insights Communicated

* Revenue by Product Category
* Payment Method Distribution
* Order Status Distribution
* Coupon Usage Impact
* Referral Source Performance
* Revenue Trends

Visual storytelling helped transform numerical findings into easy-to-understand business insights.

---

# Key Business Insights

* Chairs, Desks, and Laptops are the primary revenue drivers.
* Coupon campaigns effectively increase revenue and customer purchases.
* Digital payment methods are preferred by customers.
* Social Media is the strongest customer acquisition channel.
* High cancellation and return rates require further investigation.
* Improving order fulfillment processes may increase profitability.
* Marketing investments should focus on top-performing products and channels.
* Customer retention strategies should prioritize coupon users.

---

## Tools & Technologies

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* SQL
* Jupyter Notebook

---

## Project Structure

```text
## Project Structure

```text
E-Commerce-Sales-Analysis/
│
├── Data/
│   ├── Dataset_for_Data_Analytics.xlsx
│   ├── cleaned_dataset.csv
│   └── Data_Cleaning.ipynb
│
├── Project_01_Data_Cleaning/
│   └── Data_Cleaning.ipynb
│
├── Project_02_EDA/
│   ├── EDA.ipynb
│   └── Change_Log.xlsx
│
├── Project_03_SQL_Analysis/
│   ├── Ecommerce.db
│   └── SQL_Analysis.ipynb
│
├── Project_04_Data_Visualization/
│   └── Visualization.ipynb
│
├── Project_05_Business_Insights/
│   └── Business_Insights.md
├── README.md

```

```

---

## Conclusion

This project demonstrates the complete data analytics workflow from data cleaning and exploration to SQL querying and visualization. The analysis identified key revenue drivers, customer behavior patterns, marketing effectiveness, and operational improvement opportunities that can support business growth and decision-making.
