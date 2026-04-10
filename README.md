# 📊 Sales Performance Intelligence Dashboard (Power BI)

## Overview

This project presents a business-focused Power BI dashboard built on the AdventureWorks dataset, designed to deliver clear, actionable insights across sales, customers, and product performance.

The goal is not just visualization, but structuring data in a way that supports real decision-making. Each component is designed to answer a specific business question.

---

## Objective

- Understand overall business performance quickly  
- Identify revenue and profit drivers  
- Analyze customer value distribution  
- Detect product-level inefficiencies (e.g., high returns)  

---

## Key Insights

### 📌 Executive Snapshot
- Revenue  
- Profit  
- Orders  
- Return Rate  

Provides an immediate view of overall business health.

---

### 📈 Revenue & Profit Trends
- Weekly and monthly revenue tracking  
- Profit vs adjusted profit comparison  
- Trend analysis to identify growth and fluctuations  

---

### 👥 Customer Intelligence
- Total customers  
- Revenue per customer  
- Top 100 customers by revenue  
- Highlight of highest-value customer  

---

### 📦 Product & Category Performance
- Orders by category (Bikes, Accessories, Clothing)  
- Product-level metrics:
  - Orders  
  - Revenue  
  - Return %  

- Identification of:
  - Most ordered subcategories  
  - Most returned subcategories  

---

### 🔁 Returns Analysis
- Return rate trends over time  
- Product-level return insights  

---

## Features

- Interactive filters (date, customer, product)  
- Drill-through capability  
- Dynamic metric selection  
- Scenario testing using price adjustment  
- Clean, minimal, and user-friendly UI  

---

## Data Model

The dashboard is built using a relational data model.

**Core Tables:**
- Sales Data  
- Returns Data  
- Customer Lookup  
- Product Lookup  
- Calendar Lookup  
- Territory Lookup  

---

## Technical Approach

- Business logic implemented using DAX measures  
- Time intelligence handled via calendar table  
- Focus on clarity, reusability, and maintainability  
- Avoided unnecessary complexity in visuals  

---

## Design Philosophy

- Simplicity over complexity  
- Focus on business usability  
- Clear visual hierarchy  
- Fast and intuitive exploration  

---

## How to Use

1. Open the `.pbix` file in Power BI Desktop  
2. Use slicers and filters to explore data  
3. Hover over visuals for detailed insights  
4. Drill into customer and product-level data  

---

## Limitations & Future Improvements

- Add revenue forecasting  
- Implement customer segmentation (RFM analysis)  
- Expand drill-through capabilities  
- Optimize performance for large datasets  

---

## Closing Note

This project demonstrates a practical approach to analytics — balancing technical implementation with usability.

The focus is on building dashboards that are not just visually appealing, but actually useful for decision-making.
