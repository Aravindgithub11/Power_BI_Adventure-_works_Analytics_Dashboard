# 🚲 Adventure Works: Business Intelligence & Sales Analytics

## 📌 Project Overview
This project is the capstone for the "Microsoft Power BI Desktop for Business Intelligence" course[cite: 5, 6]. It transforms raw data from Adventure Works, a global cycling equipment manufacturer, into an interactive Power BI dashboard. 

The dashboard tracks multi-year performance, revealing that the company generated **$24.9M in Revenue** and **$10.5M in Profit** across 25.2K total orders. The goal of this project was to provide executive stakeholders with actionable insights regarding regional performance, product return rates, and customer demographics.

## 🛠️ Tools & Techniques Used
- **Power BI Desktop:** Full-scale dashboard design and interactive report creation.
- **Power Query:** Extracted, transformed, and loaded (ETL) raw data.
- **Data Modeling:** Designed a robust Star Schema with 1-to-many relationships.
- **DAX:** Wrote complex measures for time intelligence, rolling averages, and what-if parameters.

## 📊 Dashboard Features & Navigation

**1. Executive Summary**
Provides a high-level overview of core KPIs, including a global return rate of 2.2%. It includes a revenue trending line chart and a breakdown of orders by category, showing exactly which items drive the most volume.

**2. Customer Insights**
Analyzes a base of 17.4K unique customers, calculating an average revenue of $1,431 per customer. It includes donut charts segmenting orders by income level and occupation, alongside a leaderboard of the top 100 customers.

**3. Product Detail & Forecasting**
Allows users to drill through to specific products (like the Water Bottle - 30 oz.) to view performance against monthly targets using gauge visuals. This page also features a "Price Adjustment (%)" What-If parameter to simulate how price changes impact projected profits.

**4. Geographical Map**
An interactive map detailing the sales footprint across three major territories: Europe, North America, and the Pacific. 

## 📈 Key Business Insights Discovered
Based on the data modeled in this project, several key insights were identified:

1. **Category Volume vs. Revenue:** While "Bikes" generate the majority of the revenue, the "Accessories" category drives the highest volume of traffic with 17.0K orders. "Tires and Tubes" represent the most ordered product type overall.
2. **Product Returns:** The "Shorts" product type suffers from the highest return volume. Additionally, specific high-ticket items like the Sport-100 Helmet (Red and Blue) have elevated return rates exceeding 3.3%.
3. **Top Product Performance:** The "Water Bottle - 30 oz." is a massive driver of accessory sales, generating 3,983 individual orders and $39,755 in revenue.
4. **Customer Demographics:** The largest segment of orders comes from customers in the "Average" income level and those working in "Professional" occupations. 
5. **VIP Customers:** Mr. Maurice Shan is identified as the top customer by revenue, having spent $12.4K across just 6 orders.
