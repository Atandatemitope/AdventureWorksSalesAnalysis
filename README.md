# Adventure Works Sales Analysis

![](Introduction.png)
***

## Introduction


Embarking on an enlightening exploration guided by a comprehensive roadmap, this project involves a detailed analysis of the Adventure Works sales dataset extracted from Microsoft's SQL Server Adventureworks sample database. The necessary tables were thoughtfully extracted for further examination and analysis.

The dataset comprises six pivotal tables, meticulously curated for analysis: 
- FactInternetSales, 
- DimProduct, 
- DimDate, 
- DimSalesTerritory, 
- DimCustomer, 
- DimGeography.

## Problem Statement


##Problem Statement ❓:
Armed with a rich repository of four years' worth of transactional data from the AdventureWorks sample database, our primary objective is to uncover profound insights and trends 📈. The focus of this exploration is a holistic assessment of overall performance, with a keen emphasis on a detailed analysis of product profitability, customer locations (countries), and temporal trends⏳.

## Project Objectives 🎯:

**Comprehensive KPI Analysis 📊:**
- Conduct an in-depth comparison of COGS, Revenue, Quantity, Profit, Profit Margin, and Transactions for the current year against the previous year.

**Identify Above Average Years 🌟:**
- Uncover insights into total revenue, profit, and transactions, focusing on years that surpass average performance benchmarks.

**Monthly Profit Trend Analysis 📅:**
- Analyze monthly profit trends, distilling patterns, and fluctuations over the four-year period.

**Dynamics of Profit by Week Type 🗓️:**
Assess profit dynamics based on different week types to understand variations and trends.

**Quarterly Profit Performance Evaluation 📅:**
- Evaluate profit performance on a quarterly basis, identifying trends and variations throughout the year.

**Examine Profit by Weekday 📆:**
- Explore profit trends specific to weekdays, uncovering potential patterns.

**Top 5 Profitable Products Identification 💰:**
- Identify the top five profitable products and understand their percentage contribution to total profits, gaining insights into the remaining products.

**Showcase Top 5 Profitable Customers 🤝:**
- Highlight the top five high-profit customers, spotlighting their percentage share of overall profits, along with detailed contributions from other customers.

**Gender-Based Profit Analysis:**
- Display a breakdown of profits by gender, facilitating the identification of gender-based profit trends within the customer base.

**Profit Analysis by Product Color 🎨:**
- Analyze profits associated with product colors, accentuating the optimization of best-selling colors.

**Examine Profit Variations by Pricing Types 💵:**
- Investigate profit variations based on pricing types, providing insights into the effectiveness of different pricing strategies.

**Country-wise Profit Distribution with Custom Map 🗺️:**
- Utilize a custom map to visually represent profit distribution by country, enabling targeted geographic strategies based on sales performance.

**Age Group Segmentation for Profit Analysis 👶👦👨👴:**
- Segment profits into age groups to comprehend the demographic contributions to profitability, identifying which age groups contribute the most.

### Tool Used: Microsoft Excel

### Analysis Process 

To accomplish my goals, I thoroughly examined the six tables at my disposal and conducted an Exploratory Data Analysis (EDA). To enhance the data integration process, I opted for an advanced approach in Excel. Instead of relying solely on Vlook up or Index-Match functionsto merge the tables together based on the relationship keys, I chose to leverage the power of Excel Power Query Editor by loading the data into a modeling environment.

During the data cleaning phase, I identified and removed unnecessary columns from the six tables, focusing on retaining the most relevant data for my analysis. To further refine the data and meet the project objectives, I employed DAX functions within the Excel Power Query Editor and most of the Dax was done through power pivot on Excel environment. 

One significant aspect of the data transformation involved the creation of a **Conditional column** to categorize _**Week Types**_ as either Weekday or Weekend. Using the Day Name parameter, I defined the logic as follows: 

_If the Day Name is Saturday or Sunday, then categorize it as Weekend; otherwise, label it as Weekday._

Additionally, I implemented metrics for classifying products into Expensive and Less Expensive categories. The criteria were set as follows: If the product price is less than or equal to $150, categorize it as Less Expensive; otherwise, label it as Expensive. This classification enabled me to compare the percentage rates of Less Expensive products to Expensive products based on their prices.

### Now, Let’s talk about the KPI.
I created some Dax to achieve my KPIs using functions like 

- Distinct count function
- Sum function
- Divide function.
- Average function
- CountRows function
 
 _**And some other Excel functions for the insights such as**_
 
- Large function 
- Max function
- Index- Match function
- IF and IFs function






