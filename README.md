# E-Commerce Order & Delivery Performance Analysis

## Overview
This project analyzes e-commerce order and delivery performance using SQL (MySQL) and Tableau. The goal was to understand how order value and operational factors impact delivery efficiency and identify fulfillment risks.

The analysis is based on ~99,000 orders and focuses on delivery performance, revenue trends, and operational efficiency.

---

## Tools Used
- SQL (MySQL)
- Tableau

---

## Key KPIs
- Total Orders  
- Total Revenue  
- Average Delivery Time  
- % Delayed Orders  

---

## Dashboard
![Dashboard](tableau/dashboard.png)

---

## Key Insights
- ~30% of orders experience delivery delays beyond two weeks  
- Delivery inefficiencies are concentrated in a subset of orders rather than system-wide  
- Higher-value orders show greater variability in delivery time  
- High-value slow orders represent a key operational risk  

---

## Business Impact
This analysis shows that delivery inefficiencies are concentrated within specific segments rather than across the entire system. 

Improving fulfillment processes for delayed and high-value orders could significantly enhance customer satisfaction and protect revenue.

---

## Project Structure
- `sql/` → SQL queries and data preparation  
- `tableau/` → dashboard visualization  
- `insights/` → key findings  
- `data/` → dataset description  
