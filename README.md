
# Customer Sales & Market Performance Analytics

# Project Description

This project analyzes **customer sales growth** and **market performance** using Excel.  
It covers net sales trends, target achievement, and profitability (COGS, Gross Margin) across years and markets.

# Table Of Contents

- [Project Name](#1-project-name)  
- [Project Description](#2-project-description)  
- [Table of Contents](#3-table-of-contents)  
- [Overview](#4-overview)  
- [Business Problem](#5-business-problem)   
- [Tools & Technologies](#7-tools--technologies)  
- [Data Cleaning & Preparation](#8-data-cleaning--preparation)  
- [Project Structure](#9-project-structure)  
- [Key Findings](#10-key-findings)  
- [Report Highlights](#11-report-highlights)  
- [How to Use / Run This Project](#12-how-to-use--run-this-project)  
- [Final Recommendations](#13-final-recommendations)  
- [Author & Contact](#14-author--contact) 

# Overview

The reports provide insights into:  
- Customer-wise sales growth from 2019 to 2021  
- Market performance vs. sales targets for 2021  
- Profitability analysis (Net Sales, COGS, GM, GM%) by market  
- Yearly and quarterly sales and margin trends 
- Top 10 Products 2021 vs 2020

# Business Problem 

This Project aims to:  
- Track **customer-level sales growth** and identify top contributors  
- Compare **market sales vs. targets** to find performance gaps  
- Evaluate **profitability differences across markets**  
- Identify **fastest-growing products** to guide future strategy 

# Tools & Technologies

Microsoft Excel (Advanced BI Features)

- **Power Query** – for importing, cleaning, and transforming raw data.

- **Power Pivot** – for creating a data model and managing large datasets.

- **Pivot Tables** – for summarizing customer, market, and product performance.

- **DAX Measures** – built KPIs such as:

 - Net Sales

 - Gross Margin %

 - YoY Growth %

 - Target Achievement %

- **Data Modelling** – created relationships between tables (Customer, Market, Product, fact_sales_monthly, Date).

- **Date Table** – extracted Year, Quarter, Month from order dates for trend analysis.

# Data Cleaning & Preparation

- **Power Query:**

- Removed duplicates and invalid records.

- Standardized data formats (e.g., Date, Currency, Percentage).

- Created a Date Table and extracted:

- Year, Quarter, Month

- **Power Pivot & Data Modelling:**

- Established relationships between tables: Customer ↔ Sales, Market ↔ Sales, Product ↔ Sales, Date ↔ Sales.
- Built a star schema model for flexible reporting.

[Data model Screenshot](Data%20Model%20Screenshot.png)

- **DAX Measures:**

- Net Sales , Target % , COGS , GM, GM%, 21 vs 20

# Project Structure 

Customer-Sales-Market-Performance/
│
├─ Reports/

│ ├─ Customer_Net_Sales_Performance.pdf

│ ├─ Market Performance vs Target.pdf

│ ├─ P & L For Markets.pdf

│ ├─ P & L by Fiscal Year 1.pdf

│ └─ Top 10 Products.pdf

   └─ Data modelling screenshot

└─ README.md

# Key Findings 

- **Customer Growth:** Major customers like *AtliQ estore, Acclaimed Store, Amazon, AtliQ Exclusive, Flipkart, and BestBuy* showed strong growth from 2019–2021.  
- **Market Targets:** Many markets missed their 2021 sales targets, leading to an overall gap of ~9%.  
- **Profitability:** Markets like *Japan (46.5% GM)* and *New Zealand (48.2% GM)* delivered high margins, while *Germany (26.2% GM)* underperformed.  
- **Sales Trend:** Net Sales grew rapidly from **$87.5M (2019) → $196.7M (2020) → $598.9M (2021)**.  
- **Top 10 Products (2021 vs 2020):**  
  - *AQ Mx NB* (+5723%), *AQ Smash 2* (+2589%), and *AQ LION x series* (1700%+) showed exceptional growth.  
  - Overall Top 10 products grew by **808% YoY**, contributing heavily to 2021 revenue.  

# Report Highlights 

 **Customer Net Sales Report (2019–2021)** – Customer-wise sales and growth  
- **Market Performance vs Target (2021)** – Actual vs. Target gap analysis  
- **P&L by Market** – Net Sales, COGS, Gross Margin %  
- **P&L by Fiscal Year** – Yearly and quarterly sales trend (2019–2021)  
- **Top 10 Products (2021 vs 2020)** – Fastest-growing products with YoY %  

# How to Use/Run this Project

- Open the **Reports** folder  
- Read the PDFs in this order:  
   - *Customer_Net_Sales_Performance.pdf* → Customer growth  
   - *Market Performance vs Target.pdf* → Market gap analysis  
   - *P & L For Markets.pdf* → Market profitability  
   - *P & L by Fiscal Year 1.pdf* → Yearly and quarterly trends  
   - *Top 10 Products.pdf* → Product-level YoY growth  

# Final Recommendations

- Strengthen focus on **top-growing customers** like Amazon and AtliQ Exclusive.  
- Investigate **reasons for missed targets** in large markets (USA, India, Canada).  
- **Replicate strategies** from high-margin markets (Japan, New Zealand).  
- Improve **low-margin markets** such as Germany and Norway.  
- Invest in **top-performing products** like AQ Mx NB, Smash 2, and LION series to sustain growth.  
- Monitor customer, market, and product trends **quarterly** for better decision-making. 

# Author & Contact

**Author:** Rita Nayak  

📧 **Email:** ritanayak6087@gmail.com 

🌐 **LinkedIn:** https://www.linkedin.com/in/rita-nayak-74a055378/











