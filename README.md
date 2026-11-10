# 🪔 Diwali Sales Analysis | Python, Pandas & Exploratory Data Analysis

## 📌 Project Overview

This project focuses on analyzing Diwali sales data using Python to understand customer purchasing behavior, sales trends, and product performance.

The objective is to explore customer demographics, geographical distribution, occupations, marital status, and product categories to identify meaningful business insights that can support better business and marketing decisions.

The analysis is performed using Python libraries such as Pandas, NumPy, Matplotlib, and Seaborn.

---

## 🎯 Project Objectives

* Analyze customer purchasing behavior based on gender and age groups.
* Identify sales contributions across different states and geographical regions.
* Understand purchasing patterns based on marital status.
* Analyze customer distribution across different occupations.
* Identify top-performing product categories.
* Explore the most frequently ordered products.
* Generate meaningful business insights through Exploratory Data Analysis (EDA).

---

## 🛠️ Tools & Technologies

* **Python** – Data analysis and processing
* **Pandas** – Data manipulation and analysis
* **NumPy** – Numerical operations
* **Matplotlib** – Data visualization
* **Seaborn** – Statistical data visualization
* **Jupyter Notebook** – Interactive development environment

---

## 📂 Dataset Overview

The project uses a Diwali Sales dataset containing customer and transaction-related information.

**Dataset Details:**

* Initial Records: 11,251
* Initial Columns: 15
* Remaining Records after cleaning: 11,239
* Columns after cleaning: 13

### Key Dataset Attributes

| Column           | Description                |
| ---------------- | -------------------------- |
| User_ID          | Unique customer identifier |
| Cust_name        | Customer name              |
| Product_ID       | Product identifier         |
| Gender           | Customer gender            |
| Age Group        | Customer age category      |
| Age              | Customer age               |
| Marital_Status   | Marital status indicator   |
| State            | Customer's state           |
| Zone             | Geographical zone          |
| Occupation       | Customer occupation        |
| Product_Category | Product category           |
| Orders           | Number of orders           |
| Amount           | Purchase amount            |

---

## 🔄 Data Cleaning & Preparation

Before performing Exploratory Data Analysis, the dataset was inspected and cleaned using Pandas.

### Data Cleaning Steps

* Imported the CSV dataset using Pandas.
* Examined dataset dimensions using `shape`.
* Inspected dataset structure and data types using `info()`.
* Identified missing values using `isnull().sum()`.
* Removed unnecessary and completely blank columns (`Status` and `unnamed1`).
* Removed rows containing missing values using `dropna()`.
* Converted the `Amount` column from float to integer.
* Inspected dataset columns and performed descriptive statistical analysis using `describe()`.

---

## 📊 Exploratory Data Analysis (EDA)

The project explores different customer and sales dimensions to understand purchasing patterns.

### 1. Gender Analysis

* Analyzed customer distribution by gender.
* Compared total purchase amounts between male and female customers.
* Identified differences in purchasing contributions.

### 2. Age Group Analysis

* Analyzed customer distribution across different age groups.
* Compared age-group contributions by gender.
* Identified the customer age group contributing the highest sales.

### 3. State-wise Sales Analysis

* Analyzed total orders across different states.
* Identified the top 10 states based on order volume.
* Compared total sales amounts across the top-performing states.

### 4. Marital Status Analysis

* Examined customer distribution based on marital status.
* Compared purchase amounts by gender and marital status.
* Identified customer segments contributing significantly to sales.

### 5. Occupation Analysis

* Analyzed customer distribution across occupations.
* Compared total purchase amounts by occupation.
* Identified occupations with higher sales contributions.

### 6. Product Category Analysis

* Examined product distribution across categories.
* Compared category-wise purchase amounts.
* Identified the highest-contributing product categories.

### 7. Product Performance Analysis

* Grouped products using Product_ID.
* Analyzed total orders for individual products.
* Identified the top 10 most frequently ordered products.

---

## 💡 Key Business Insights

Based on the exploratory analysis performed in the notebook, the following observations were identified:

1. **Gender:** Female customers contribute a higher purchase amount compared with male customers.

2. **Age Group:** Customers in the 26–35 age group represent a major customer segment, with female customers contributing significantly.

3. **Geographical Performance:** Uttar Pradesh, Maharashtra, and Karnataka are among the leading states in both order volume and sales amount.

4. **Marital Status:** Married customers, particularly women, show a significant contribution to overall purchases.

5. **Occupation:** Customers associated with IT, Healthcare, and Aviation occupations represent important purchasing segments.

6. **Product Categories:** Food, Clothing, and Electronics are among the major product categories contributing to sales.

7. **Product Performance:** The analysis identifies the top 10 products based on the number of orders.

---

## 📈 Visualizations

The project uses different visualization techniques to understand customer behavior and sales performance.

* Bar Charts
* Count Plots
* Gender-wise Sales Comparison
* Age Group Distribution
* State-wise Sales Analysis
* Occupation-wise Sales Analysis
* Category-wise Sales Analysis
* Top 10 Product Analysis

---

## 📌 Skills Demonstrated

* Python Programming
* Data Cleaning & Preprocessing
* Data Manipulation using Pandas
* Exploratory Data Analysis (EDA)
* Data Aggregation using GroupBy
* Descriptive Statistical Analysis
* Handling Missing Values
* Data Visualization
* Business Insights Generation
* Customer Segmentation
* Sales Analysis

---

## 🔮 Future Improvements

* Perform deeper customer segmentation.
* Analyze average purchase amount across customer groups.
* Calculate category-wise sales contribution percentages.
* Add additional statistical analysis.
* Explore relationships between customer demographics and purchasing behavior.
* Build an interactive sales dashboard using Power BI.

---

## 👨‍💻 Author

**Deepak Chauhan**

Aspiring Data Analyst | Python | SQL | Excel | Power BI

**GitHub:** https://github.com/deepak200422

---

⭐ If you find this project useful, feel free to explore the repository and share your feedback.

