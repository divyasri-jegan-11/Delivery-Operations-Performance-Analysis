# 🍽️ Delivery Operations & Performance Analysis
### End-to-End SQL Analytics Case Study for a Food Delivery Platform

> An end-to-end business analytics project that investigates operational inefficiencies, customer experience, and revenue leakage within a food delivery platform using SQL, Python, and Power BI.

---

## Executive Summary

Food delivery platforms operate in a highly competitive environment where operational efficiency directly influences customer satisfaction, customer retention, and revenue growth.

This project analyzes **149,166 food delivery orders** to evaluate operational performance across multiple cities. Using **SQL for business analysis**, **Python for data exploration**, and **Power BI for executive reporting**, the project identifies key operational bottlenecks affecting delivery performance and quantifies their business impact.

The analysis connects **delivery operations → customer experience → financial performance**, demonstrating how data-driven decision-making can improve operational efficiency and business outcomes.

---

## Business Context

As the platform expanded across multiple metropolitan cities, increasing order volumes exposed several operational challenges, including:

- High order cancellation rates
- Frequent delivery delays
- SLA breaches
- Declining customer ratings
- Revenue leakage due to failed deliveries

Rather than a lack of customer demand, the primary business challenge lies in operational inefficiencies that reduce customer satisfaction and negatively impact profitability.

---

# Business Problem

The platform requires an analytical assessment to answer the following questions:

- Where are operational inefficiencies occurring?
- Which cities contribute the most revenue?
- How efficiently are deliveries being completed?
- How do delivery delays affect customer satisfaction?
- How much revenue is lost through cancelled orders?
- Which operational improvements should be prioritized?

The objective is to transform operational data into actionable business insights that support strategic decision-making.

---

# Business Objectives

The project aims to:

- Analyze platform performance across multiple cities.
- Evaluate restaurant and delivery partner distribution.
- Measure Average Order Value (AOV) across locations.
- Quantify delivery performance using SLA metrics.
- Identify operational drivers behind order cancellations.
- Assess the relationship between delivery performance and customer ratings.
- Estimate revenue loss caused by cancelled orders.
- Recommend business actions to improve operational efficiency.

---

# Stakeholders

This analysis supports decision-making for multiple business teams.

| Stakeholder | Business Need |
|-------------|---------------|
| Operations Team | Improve delivery efficiency |
| Regional Managers | Compare city performance |
| Finance Team | Measure revenue leakage |
| Customer Experience Team | Improve customer satisfaction |
| Executive Leadership | Support operational strategy |

---

# Business Questions

The analysis answers the following business questions:

### Platform Operations

- Which cities have the highest operational capacity?
- Is the delivery partner network sufficient relative to restaurant growth?

### Revenue Performance

- Which cities generate the highest revenue?
- Which cities have the highest Average Order Value?
- Which cuisines contribute most to platform revenue?

### Operational Efficiency

- What is the cancellation rate?
- How frequently are SLA commitments breached?
- Which cities experience the highest operational delays?

### Customer Experience

- Does delivery time influence customer ratings?
- How do operational failures affect customer satisfaction?

### Financial Impact

- How much revenue is lost because of cancelled orders?

---

# Dataset Overview

The project uses a relational data model consisting of **Fact** and **Dimension** tables.

### Dimension Tables

- Customer
- Restaurant
- Delivery Partner
- Menu Item

### Fact Tables

- Orders
- Order Items
- Delivery Performance
- Customer Ratings

The star-schema design enables scalable SQL analysis and business reporting.

---

# Data Model

The analytical model is built around **fact_orders**, supported by operational fact tables and business dimensions.

```
Customers
        │
Restaurants ── Orders ── Delivery Performance
        │
 Menu Items
        │
 Ratings
```

> *(Insert ER Diagram here)*

---

# Analytical Framework

The analysis follows four business-focused analytical modules.

## 1. Platform Supply & Presence

Evaluate platform coverage by analyzing:

- Restaurant distribution
- Delivery partner availability
- City-level operational capacity

---

## 2. Revenue & Pricing Analysis

Measure platform monetization through:

- Revenue
- Orders
- Average Order Value
- City comparisons

---

## 3. Operational Performance

Evaluate service quality using:

- Cancellation Rate
- Delivery Time
- SLA Breach Rate

---

## 4. Customer Experience & Revenue Impact

Analyze how operational performance influences:

- Customer Ratings
- Revenue Loss
- Customer Experience

---

# KPI Framework

| KPI | Business Purpose |
|------|------------------|
| Total Orders | Demand |
| Revenue | Financial Performance |
| Average Order Value | Customer Spending |
| Cancellation Rate | Operational Efficiency |
| SLA Breach % | Delivery Reliability |
| Average Delivery Time | Service Performance |
| Customer Rating | Customer Experience |
| Estimated Revenue Loss | Financial Impact |

---

# Key Findings

## Revenue Performance

- Bengaluru generated the highest revenue and order volume across the platform.
- Mumbai and Delhi emerged as the next strongest markets.
- Tier-2 cities demonstrated lower monetization despite healthy demand, indicating untapped revenue opportunities.

---

## Customer Spending Behaviour

- Average Order Value remained relatively consistent across cities.
- Revenue growth is primarily driven by higher order volumes rather than larger basket sizes.
- Pricing behaviour suggests customers are highly price-sensitive.

---

## Operational Performance

- Order cancellation rate reached **7.45%**.
- **63.84%** of deliveries breached the expected SLA.
- High-demand cities experienced the greatest absolute operational losses.

---

## Customer Experience

Customer satisfaction declines significantly as delivery time increases.

| Delivery Time | Average Rating |
|--------------|---------------|
| 0–30 mins | ⭐ 4.50 |
| 31–45 mins | ⭐ 4.36 |
| 46–60 mins | ⭐ 3.88 |
| 60+ mins | ⭐ 2.49 |

Delivery delays have a direct negative impact on customer satisfaction.

---

## Revenue Impact

Cancelled orders resulted in an estimated revenue loss of approximately **₹3.9 Million**, demonstrating the financial cost of operational inefficiencies.

---

# Business Recommendations

### Improve Delivery Partner Allocation

Increase delivery partner availability during peak demand periods to reduce SLA breaches.

**Expected Impact**

- Faster deliveries
- Improved customer ratings
- Lower cancellation rates

---

### Optimize Restaurant Operations

Collaborate with restaurants experiencing consistently high preparation delays.

**Expected Impact**

- Reduced delivery delays
- Better operational efficiency

---

### Increase Basket Value

Introduce city-specific promotions and bundled offers to improve Average Order Value without relying solely on increased demand.

---

### Prioritize High-Impact Cities

Focus operational improvements in Bengaluru, Mumbai, and Delhi, where the largest share of revenue and operational losses occur.

---

# Business Impact

The analysis demonstrates that operational efficiency is directly connected to customer experience and financial performance.

Reducing delivery delays and cancellations has the potential to:

- Improve customer satisfaction
- Increase customer retention
- Reduce revenue leakage
- Strengthen operational efficiency
- Support long-term business growth

---

# Dashboard

> **Power BI Executive Dashboard**

*(Insert dashboard screenshot here)*

---

# Tools & Technologies

| Category | Technologies |
|-----------|--------------|
| SQL | MySQL |
| Data Analysis | Python, Pandas |
| Visualization | Power BI |
| Documentation | Notion |
| Version Control | Git, GitHub |

---

# Repository Structure

```
Food-Delivery-Crisis-Recovery-Analytics/
│
├── data/
│   ├── raw/
│   └── schema/
│
├── sql/
│
├── notebooks/
│
├── dashboard/
│
├── images/
│
├── documentation/
│
├── README.md
│
└── requirements.txt
```

---

# Documentation

Detailed SQL queries, methodology, analysis, and business insights are available in the project documentation.

📖 **Project Documentation**

https://www.notion.so/Food-Delivery-Crisis-Recovery-Analytics-260c4eacd6ff80909253c169a6664326

---

# Skills Demonstrated

- Business Problem Solving
- SQL Analytics
- Exploratory Data Analysis (EDA)
- KPI Development
- Operational Performance Analysis
- Customer Experience Analytics
- Revenue Analysis
- Dashboard Design
- Business Storytelling
- Data-Driven Decision Making

---

## About This Project

This project was developed to demonstrate how data analytics can support business decision-making by transforming raw operational data into actionable insights.

The case study follows an end-to-end analytics workflow, beginning with business understanding and concluding with strategic recommendations backed by quantitative analysis.
