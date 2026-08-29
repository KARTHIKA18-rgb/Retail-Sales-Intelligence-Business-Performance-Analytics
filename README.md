# 📊 Retail Sales Intelligence & Business Performance Analytics

## 📌 Project Overview

This project performs an end-to-end analysis of retail sales data to understand **sales performance, profitability, customer behavior, product performance, regional trends, shipping patterns, and discount impact**.

The project combines **data cleaning, Exploratory Data Analysis (EDA), data visualization, outlier detection, feature engineering, KPI analysis, SQL business analysis, and sales prediction** to generate actionable business insights and support data-driven decision-making.

---

# 🎯 Project Objectives

The main objectives of this project are to:

* 📈 Analyze overall sales and profit performance.
* 🛍️ Identify the best- and worst-performing product categories and sub-categories.
* 👥 Understand customer purchasing behavior across different segments.
* 🌍 Analyze sales and profit performance across regions, states, and cities.
* 📦 Examine shipping mode preferences.
* 💰 Understand the impact of discounts on profitability.
* 📅 Identify monthly and yearly sales trends.
* 🔍 Detect outliers and improve data quality.
* ⚙️ Perform feature engineering for time-based analysis.
* 🗄️ Conduct business analysis using SQL.
* 📊 Create meaningful visualizations for business decision-making.
* 🔮 Use historical sales data for future sales prediction.

---

# 📂 Dataset Description

The project uses a **Retail Sales dataset containing 9,994 records and 21 attributes**.

Each row represents a retail order or product transaction.

## Dataset Features

| Feature       | Description                               |
| ------------- | ----------------------------------------- |
| Row ID        | Unique identifier for each record         |
| Order ID      | Unique identifier for each customer order |
| Order Date    | Date when the order was placed            |
| Ship Date     | Date when the order was shipped           |
| Ship Mode     | Shipping method used                      |
| Customer ID   | Unique customer identifier                |
| Customer Name | Name of the customer                      |
| Segment       | Customer segment                          |
| Country       | Country of the customer/order             |
| City          | City where the order was placed           |
| State         | State associated with the order           |
| Postal Code   | Postal code of the location               |
| Region        | Geographical region                       |
| Product ID    | Unique product identifier                 |
| Category      | Main product category                     |
| Sub-Category  | Product sub-category                      |
| Product Name  | Name of the product                       |
| Sales         | Revenue generated from the transaction    |
| Quantity      | Number of products purchased              |
| Discount      | Discount applied                          |
| Profit        | Profit or loss generated                  |

---

# 🛠️ Technologies & Tools Used

## Programming Language

* 🐍 Python

## Data Analysis Libraries

* Pandas
* NumPy

## Data Visualization Libraries

* Matplotlib
* Seaborn
* Plotly

## Machine Learning & Data Processing

* Scikit-learn
* Label Encoding
* Feature Engineering

## Database & Business Analysis

* SQL

## Development Environment

* Jupyter Notebook

---

# 🔄 Project Workflow

```text
Raw Dataset
     ↓
Data Understanding
     ↓
Data Cleaning
     ↓
Date Conversion
     ↓
Exploratory Data Analysis (EDA)
     ↓
Data Visualization
     ↓
Outlier Detection
     ↓
Feature Engineering
     ↓
KPI Calculation
     ↓
Correlation Analysis
     ↓
SQL Business Analysis
     ↓
Sales Prediction
     ↓
Business Insights & Recommendations
```

---

# 🧹 Data Cleaning & Preprocessing

The following preprocessing steps were performed:

* Checked dataset structure and data types.
* Checked for missing values.
* Converted date columns into datetime format.
* Prepared numerical and categorical variables for analysis.
* Performed outlier detection.
* Applied label encoding where required.
* Created additional features for time-based analysis.

---

# ⚙️ Feature Engineering

New features were created to improve analysis and visualization:

* Year
* Month Number
* Month

These features helped analyze:

* Monthly sales trends
* Yearly performance
* Seasonal patterns
* Sales forecasting

---

# 🔍 Exploratory Data Analysis & Visualizations

## 📅 1. Monthly Sales Trend

### Key Findings

* Sales fluctuate across different months.
* **November and December record the highest sales.**
* **February records the lowest sales.**
* Sales increase strongly during the later months of the year.
* September also shows a noticeable increase.
* The data indicates a clear **seasonal sales pattern**.

### Business Insights

* Increase inventory before the November–December peak season.
* Plan marketing campaigns around high-demand periods.
* Use special promotions during February to improve sales.
* Use seasonal patterns for inventory and workforce planning.

---

## 💰 2. Monthly Profit Trend

### Key Findings

* Monthly profit generally has a positive relationship with sales.
* **December records the highest profit.**
* January has comparatively lower profit.
* High sales do not always result in equally high profit.
* Discounts, product mix, and costs can influence profitability.

### Business Insights

* Focus on high-profit periods to maximize returns.
* Investigate months with high sales but low profit.
* Control excessive discounting.
* Promote products with stronger profit margins.

---

## 📈 3. Yearly Sales Trend by Category

### Key Findings

* Sales generally increased across the years.
* **Technology showed the strongest overall sales performance.**
* Technology and Office Supplies experienced strong growth.
* Furniture also showed steady growth.
* The overall trend indicates business expansion.

### Business Insights

* Increase investment in high-performing Technology products.
* Maintain sufficient inventory for growing categories.
* Develop category-specific business strategies.
* Use historical trends for future sales forecasting.

---

## 🥧 4. Sales Share by Category

### Key Findings

* **Technology contributes the largest share of sales.**
* Furniture contributes the second-largest share.
* Office Supplies has the smallest share.
* Sales are relatively distributed across categories.

### Business Insights

* Prioritize Technology products.
* Maintain a balanced product portfolio.
* Analyze lower-performing categories for improvement opportunities.
* Allocate inventory and marketing resources based on category performance.

---

## 👥 5. Sales Share by Customer Segment

### Key Findings

* **Consumer segment generates the highest sales.**
* Corporate contributes the second-highest sales.
* Home Office has the lowest contribution.

### Business Insights

* Strengthen customer retention strategies for Consumer customers.
* Create targeted promotions for Corporate customers.
* Explore opportunities to increase Home Office sales.
* Develop customized offers based on customer segments.

---

## 🚚 6. Orders by Shipping Mode

### Key Findings

* **Standard Class is the most frequently used shipping mode.**
* Second Class is the next most popular option.
* First Class has fewer orders.
* Same Day has the lowest usage.

### Business Insights

* Maintain sufficient logistics capacity for Standard Class.
* Ensure reliable delivery performance.
* Analyze opportunities to promote faster shipping options.
* Target Same Day delivery to customers willing to pay for speed.

---

## 📊 7. Sales Distribution by Category

### Key Findings

* Most transactions fall within the lower sales-value range.
* Sales distribution is **right-skewed**.
* A small number of transactions have very high sales values.
* Transaction sizes vary significantly.

### Business Insights

* Identify high-value customers and transactions.
* Use upselling and cross-selling strategies.
* Create product bundles to increase average order value.
* Use median and percentile analysis along with averages.

---

## 🏷️ 8. Discount Distribution by Category

### Key Findings

* Discounts are concentrated around commonly used levels.
* **0% and 20% discounts are frequently observed.**
* Discount levels vary across categories.
* High discounts can negatively affect profitability.

### Business Insights

* Avoid unnecessary excessive discounting.
* Use targeted discounts instead of broad discounts.
* Analyze discount impact before launching promotions.
* Develop category-specific discount strategies.

---

## 💵 9. Average Profit by Category

### Key Findings

* **Technology has the highest average profit per transaction.**
* Office Supplies generates moderate average profit.
* Furniture has the lowest average profit.

### Business Insights

* Give strategic attention to Technology products.
* Review Furniture pricing and costs.
* Promote high-margin products.
* Evaluate categories using both sales and profit.

---

## 📦 10. Category → Sub-Category Sales Analysis

### Key Findings

* **Phones are the highest-selling sub-category.**
* Chairs are another major sales contributor.
* Storage, Tables, and Binders also contribute significantly.
* Sales performance varies across sub-categories.

### Business Insights

* Maintain sufficient inventory for Phones and Chairs.
* Promote complementary products.
* Analyze weak sub-categories for improvement.
* Optimize product assortment using sales performance.

---

## 🌍 11. Region → State Sales Analysis

### Key Findings

* **West region has the highest overall sales.**
* East region is the second-highest contributor.
* Central and South have comparatively lower sales.
* **California is the strongest state by sales.**

### Business Insights

* Prioritize inventory and marketing in high-performing regions.
* Study successful strategies used in the West region.
* Create targeted campaigns for lower-performing regions.
* Focus expansion strategies on high-performing states.

---

# 🚨 Outlier Detection

Outliers were detected using the **IQR (Interquartile Range) method**.

### Features Analyzed

* Quantity
* Discount
* Profit

### Results

* Original dataset: **9,994 records**
* Dataset after outlier treatment: **7,480 records**

Outlier detection helped improve data quality and prepare the dataset for further analysis and prediction.

---

# 🔥 Correlation & Feature Relationship Analysis

A correlation heatmap was used to understand relationships between numerical variables.

### Key Findings

* Sales and Profit show a positive relationship.
* Higher sales can generally contribute to higher profit.
* Quantity has a weaker relationship with some financial variables.
* Discount can influence profitability.

### Business Value

Correlation analysis helps identify:

* Important variables for prediction.
* Relationships between financial metrics.
* Factors influencing profitability.

---

# 🗄️ SQL Business Analysis

The project also includes SQL-based business analysis.

### SQL Analysis Performed

1. Sales by Category
2. Profit by Category
3. Sub-Category Performance
4. Customer Segment Analysis
5. Regional Performance
6. State-Level Performance
7. Top 10 Products by Sales
8. Top 10 Customers
9. Monthly Sales Analysis
10. Yearly Sales Performance
11. Shipping Mode Analysis
12. Customer Purchase Frequency

---

# 📊 Key Performance Indicators (KPIs)

| KPI                             |      Value |
| ------------------------------- | ---------: |
| Total Sales                     | 758,185.52 |
| Total Profit                    | 107,065.63 |
| Original Records                |      9,994 |
| Records After Outlier Treatment |      7,480 |

---

# 🔑 Key Business Findings

* 💻 **Technology** is the strongest-performing category in sales and average profit.
* 👥 **Consumer** is the highest-contributing customer segment.
* 🚚 **Standard Class** is the most preferred shipping mode.
* 📈 Sales show a strong **seasonal pattern**.
* 🗓️ **November and December** are high-performing sales months.
* 📊 Sales distribution is **right-skewed**, with a few high-value transactions.
* 📱 **Phones and Chairs** are major sales-contributing sub-categories.
* 🌎 **West region** records the highest sales.
* 📍 **California** is one of the strongest state-level contributors.
* 🏷️ Discounts vary across categories and can affect profitability.
* 🚨 Outliers were identified in Quantity, Discount, and Profit.

---

# 💡 Business Recommendations

### 📦 Inventory Management

* Increase inventory before November and December.
* Maintain sufficient stock for Technology products and Phones.
* Use sales forecasting for better inventory planning.

### 💰 Pricing & Discount Strategy

* Avoid excessive discounts that reduce profit margins.
* Use targeted discount strategies.
* Analyze profit along with sales before planning promotions.

### 📣 Marketing Strategy

* Focus marketing efforts on high-performing products.
* Strengthen Consumer-segment retention strategies.
* Create targeted campaigns for lower-performing regions.

### 🌍 Regional Strategy

* Prioritize high-performing regions such as the West.
* Focus expansion opportunities in California.
* Improve sales in weaker regions using localized campaigns.

### 🚚 Operations

* Maintain efficient Standard Class delivery.
* Analyze opportunities for profitable faster shipping options.

---

# 🔮 Sales Prediction

Historical retail transaction data is used as the foundation for developing a **sales prediction model**.

The objective is to support:

* Future sales estimation
* Inventory planning
* Resource allocation
* Business forecasting
* Strategic decision-making

---

# 📁 Project Structure

```text
Retail-Sales-Intelligence/
│
├── 📄 Retail sales.csv
├── 📓 Retail_Sales_Intelligence_&_Business_Performance_Analytics.ipynb
├── 📄 README.md
│
└── 📁 images/
    └── Visualizations
```

---

# 📈 Skills Demonstrated

* Data Cleaning
* Data Preprocessing
* Exploratory Data Analysis (EDA)
* Data Visualization
* Statistical Analysis
* Outlier Detection
* Feature Engineering
* KPI Analysis
* Correlation Analysis
* SQL Business Analysis
* Sales Forecasting
* Business Intelligence
* Data-Driven Decision Making

---

# 🏁 Conclusion

This project demonstrates an **end-to-end retail data analytics workflow**, transforming raw transaction data into meaningful business insights.

Through data cleaning, EDA, visualization, outlier detection, feature engineering, KPI analysis, and SQL business analysis, the project identified important patterns in:

* Sales and profitability
* Product categories
* Customer segments
* Regional performance
* Shipping preferences
* Discounts
* Seasonal trends

The analysis highlights how data can support better **inventory planning, pricing strategies, marketing decisions, customer targeting, profitability improvement, and future sales forecasting**.
