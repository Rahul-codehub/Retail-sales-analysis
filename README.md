# 📊 Retail Sales Data Analysis & Business Insights

> An end-to-end retail data analytics project that analyzes sales, profit, customers, products, regions, categories, discounts, and time-based trends to generate actionable business insights using Python, Pandas, Matplotlib, and Jupyter Notebook.

---

## 📌 Table of Contents

- [Project Overview](#-project-overview)
- [Business Problem](#-business-problem)
- [Project Objectives](#-project-objectives)
- [Project Workflow](#-project-workflow)
- [Dataset Information](#-dataset-information)
- [Dataset Columns](#-dataset-columns)
- [1. Data Loading & Understanding](#1-data-loading--understanding)
- [2. Data Cleaning](#2-data-cleaning)
- [3. Feature Engineering](#3-feature-engineering)
- [4. Exploratory Data Analysis](#4-exploratory-data-analysis)
- [5. Data Visualization](#5-data-visualization)
- [6. Business Insights](#6-business-insights)
- [Business Recommendations](#-business-recommendations)
- [Key Performance Indicators](#-key-performance-indicators)
- [Technologies Used](#-technologies-used)
- [Project Structure](#-project-structure)
- [Installation](#-installation)
- [How to Run the Project](#-how-to-run-the-project)
- [Running the Notebook](#-running-the-notebook)
- [Expected Outputs](#-expected-outputs)
- [Project Deliverables](#-project-deliverables)
- [Skills Demonstrated](#-skills-demonstrated)
- [Project Limitations](#-project-limitations)
- [Future Improvements](#-future-improvements)
- [Conclusion](#-conclusion)
- [Author](#-author)

---

# 📌 Project Overview

The **Retail Sales Data Analysis & Business Insights** project is an end-to-end data analytics project developed as part of a data science and machine learning capstone.

The purpose of this project is to transform raw retail transaction data into meaningful business insights.

The analysis focuses on understanding:

- Overall sales performance
- Overall profitability
- Product category performance
- Product subcategory performance
- Regional performance
- Customer segment performance
- Yearly sales trends
- Monthly sales trends
- Discount behavior
- Profitability patterns
- Loss-making products
- High-performing products
- Business opportunities
- Areas requiring management attention

The project follows a complete analytics workflow starting from **raw data loading**, followed by **data cleaning**, **feature engineering**, **exploratory data analysis**, **visualization**, and finally **business recommendations**.

---

# 💼 Business Problem

Retail businesses generate large amounts of transactional data every day.

However, raw transaction records alone do not provide enough information for management to make effective decisions.

A business needs to understand questions such as:

- Which product categories generate the most sales?
- Which categories generate the most profit?
- Which regions are performing well?
- Which customer segments contribute the most revenue?
- How are sales changing over time?
- Which months have the highest sales?
- Which products are generating losses?
- Is discounting affecting profitability?
- Which subcategories should receive more attention?
- Where should management focus improvement efforts?
- How can the company increase profit without unnecessarily increasing discounts?

This project addresses these questions by analyzing historical retail sales data and converting the results into practical business recommendations.

---

# 🎯 Project Objectives

The main objectives of this project are:

### 1. Understand the Dataset

Inspect the structure, size, columns, data types, and statistical characteristics of the retail dataset.

### 2. Improve Data Quality

Identify and handle:

- Missing values
- Duplicate records
- Incorrect data types
- Invalid dates
- Invalid numeric values
- Negative sales
- Negative quantities
- Invalid discounts

### 3. Create Useful Features

Generate additional analytical features such as:

- Shipping days
- Order year
- Order month
- Order day
- Profit status
- Sales per unit

### 4. Analyze Business Performance

Calculate important business KPIs such as:

- Total Sales
- Total Profit
- Total Quantity
- Category performance
- Regional performance
- Segment performance

### 5. Identify Trends

Analyze how sales and profit change:

- Across years
- Across months
- Across categories
- Across regions
- Across customer segments

### 6. Identify Business Opportunities

Find:

- High-performing categories
- High-profit subcategories
- Loss-making subcategories
- Strong-performing regions
- Important customer segments
- Potential pricing and discount issues

### 7. Provide Business Recommendations

Convert analytical findings into actionable recommendations for improving sales and profitability.

---

# 🔄 Project Workflow

The project follows the following end-to-end workflow:

```text
Raw Retail Dataset
        ↓
Data Loading
        ↓
Data Understanding
        ↓
Data Quality Checks
        ↓
Data Cleaning
        ↓
Feature Engineering
        ↓
Exploratory Data Analysis
        ↓
Data Visualization
        ↓
Business Insights
        ↓
Business Recommendations
        ↓
Final Report