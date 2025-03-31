# Global Superstore Data Analysis

## Table of Contents
1. [Project Overview](#project-overview)
2. [Data Source](#data-source)
3. [Tools Used](#tools-used)
4. [Data Cleaning and Preparation](#data-cleaning-and-preparation)
5. [Exploratory Data Analysis](#exploratory-data-analysis)
6. [Data Analysis](#data-analysis)
7. [Results and Findings](#results-and-findings)
8. [Recommendations](#recommendations)
9. [Limitations](#limitations)
10. [References](#references)

---

## Project Overview
This project analyzes the Global Superstore dataset to gain insights into sales, profits, and customer trends across different regions. The goal is to identify the most profitable product categories and subcategories, countries, and regions while also understanding factors contributing to low profitability.

## Data Source
The dataset used for this analysis is the **Global Superstore Dataset**, which contains transactional data covering sales, profits, shipping costs, and customer information across various countries.

## Tools Used
- **Power BI** for data visualization and dashboard creation
- **Power Query** for initial data cleaning and exploratory analysis
- **DAX (Data Analysis Expressions)** for calculated measures in Power BI

## Data Cleaning and Preparation
- Removed duplicates and null values
- Converted data types (e.g., dates, numeric values)
- Standardized country names and region classifications
- Filtered out erroneous records
- Converted first rows of columns to headers

## Exploratory Data Analysis
EDA involved exploring the sales data to provide insights by answering the following questions;
1. a) What are the three countries that generated the highest total profit for Global Superstore in 2014? 
   b) For each of these three countries, find the three products with the highest total profit. Specifically, 
   what are the products’ names and the total profit for each product? 
2. Identify the 3 subcategories with the highest average shipping cost in the United States.  
3. a) Assess Nigeria’s profitability (i.e., total profit) for 2014. How does it compare to other African 
   countries?  
   b) What factors might be responsible for Nigeria’s poor performance? You might want to investigate 
   shipping costs and the average discount as potential root causes.    
4. Identify the product subcategory that is the least profitable in Southeast Asia.  
   For this question, Southeast Asia was assumed to comprise of Cambodia, Indonesia, Malaysia, Myanmar 
   (Burma), the Philippines, Singapore, Thailand, and Vietnam.  
   b) Is there a specific country i n Southeast Asia where Global Superstore should stop offering the 
   subcategory identified in 4a?  
5. Which city is the least profitable (in terms of average profit) in the United States? For this analysis, cities with less than 10 Orders were discarded. 
   b) Why is this city’s average profit so low?  
6. Which product subcategory has the highest average profit in Australia?  
7. Who are the most valuable customers and what do they purchase?  

## Data Analysis
- Identified the most profitable and least profitable countries
- Analyzed product profitability in top-performing regions
- Examined average profit by city while filtering for cities with at least 10 orders
- Created DAX measures for total profit, average discount, and number of orders
- Used **Power BI visuals** such as clustered bar charts, maps, and slicers for insights

## Results/Findings
### 1. **Top 3 Most Profitable Countries**
   - The top three countries by total profit are **United States, Canada, and Germany**.

### 2. **Least Profitable City in the United States**
   - The city with the lowest **average profit**, while excluding those with fewer than 10 orders, is **Jacksonville, FL**.

### 3. **Top 3 Products in the Most Profitable Countries**
   - In the United States, the top three products by profit are **Product A, Product B, and Product C**.
   - In Canada, the most profitable products are **Product D, Product E, and Product F**.
   - In Germany, the leading products in profitability are **Product G, Product H, and Product I**.

### 4. **Factors Responsible for Low Profitability in Certain Cities**
   - High shipping costs significantly impact profitability.
   - High discounts lead to reduced margins.
   - Certain product categories generate consistently low profits.

### 5. **Impact of High Sales and Shipping Costs on Profitability**
   - In cities with low profitability but high sales, shipping costs and discounts play a major role in reducing profit margins.
   - Even though sales volume is high, the overall profit remains low due to higher operational expenses.

![Global superstore screenshot p1](https://github.com/user-attachments/assets/5f2804a4-f43e-4e7f-9627-6c12cfecd418)

![Global Superstore screenshot p2](https://github.com/user-attachments/assets/3f2f2da1-4484-4b6c-8d59-cc17fc217969)

##Recommendations
- Reduce high discount rates on underperforming products.
- Optimize shipping costs by selecting cost-effective delivery methods.
- Focus marketing efforts on top-performing products in each region.
- Identify and replace low-profit items with higher-margin alternatives.
- Implement targeted marketing campaigns in low-profit countries to boost sales

## Limitations
- Incomplete or missing values were removed to mitigate errors and incorrect calculations
- External factors such as economic conditions and customer preferences were not analyzed


## References
- Global Superstore Dataset
- Power BI Documentation for Data Visualization & DAX
- Business Intelligence best practices
