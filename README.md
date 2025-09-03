Project Overview

**Purpose:** Analyzes 20 sales transactions (Jan-Jun 2024) to identify trends, customer behavior, and growth strategies.
**Data:** Includes Transaction_ID, Date, Customer_ID, Product, Category, Quantity, Price, Total_Amount, Payment_Method, Region.
**Ethics: **Uses anonymized Customer_IDs, ensuring GDPR compliance with no sensitive data.

**1. Cleaned Dataset**

Inspection: 20 rows, 10 columns; one missing Total_Amount (ID 1001) imputed as 800 (Quantity * Price).
Duplicates: None detected.
Normalization: Dates standardized to YYYY-MM-DD; numeric columns verified.
Export: Saved as cleanedsalesdata.csv.

**2. Exploratory Data Analysis Summary**

Overview: Total sales 7,930; mean Total_Amount 396.50, Quantity 1.60, Price 298.75.
Trends: Electronics dominate (94.5%), peaks in Jan (2,100)/Apr (1,740), dips in Mar (325)/May (1,025).
Correlations: Price-Total_Amount (0.89 positive), Quantity-Price (-0.42 negative).
Customer Behavior: South region leads (3,225, cash preferred); only 2 repeat customers (C001, C002).

**3. Three Data Visualizations**

Monthly Sales Trends (Line Graph): Shows peaks in Jan/Apr, dip in Mar, highlighting seasonality.
Sales by Product Category (Bar Chart): Electronics lead (7,500) vs. Books (180)/Clothing (250).
Correlation Heatmap: Displays Price-Total_Amount (0.89) and Quantity-Price (-0.42) relationships.

**4. Final Data Insights Report**

Narrative: Electronics (94.6% revenue) drive sales; seasonal peaks suggest promotion timing.
Insights: High-price items boost revenue, bulk buys on cheaper goods; weak customer loyalty.
Recommendations: Stock Electronics in peak months, cross-promote in off-seasons, add ad tracking.

**5. Bonus Challenge: Increase Sales in Worst Months (March nad May)**

Strategy 1: Offer 10-20% discounts on Clothing/Books with Electronics to boost transactions.
Strategy 2: Send mid-month South region emails for new Electronics to drive repeat business.
