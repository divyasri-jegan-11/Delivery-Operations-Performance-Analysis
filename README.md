#  Delivery Operations & Performance Analysis

### End-to-End Business Analytics Case Study for a Food Delivery Platform

An end-to-end analytics project that investigates operational performance, customer experience, and revenue leakage for a food delivery platform using **SQL, Python, and Power BI**.

---

## Business Problem

The platform operates across multiple cities with high order volumes but faces operational challenges that impact customer satisfaction and profitability, including:

* High order cancellations
* Delivery delays and SLA breaches
* Declining customer ratings
* Revenue loss from failed deliveries

This project analyzes operational data to identify performance bottlenecks, measure their business impact, and provide data-driven recommendations.

---

## Project Objectives

* Analyze platform performance across cities.
* Evaluate Average Order Value (AOV) and revenue trends.
* Measure delivery efficiency using SLA metrics.
* Identify drivers of order cancellations.
* Assess the relationship between delivery performance and customer ratings.
* Estimate revenue loss caused by operational inefficiencies.

---

## Dataset Overview

The analysis is based on a relational dataset modeled using a **star schema**.

**Dimension Tables**

* Customers
* Restaurants
* Delivery Partners
* Menu Items

**Fact Tables**

* Orders
* Order Items
* Delivery Performance
* Customer Ratings

> **ER Diagram:** (<img width="2342" height="2029" alt="image" src="https://github.com/user-attachments/assets/ea249cff-4706-488b-9e2b-4c9f55bb1e6a" />)

---

## Key Metrics

| Metric                 |     Value |
| ---------------------- | --------: |
| Orders Analyzed        |   149,166 |
| Cancellation Rate      |     7.45% |
| SLA Breach Rate        |    63.84% |
| Estimated Revenue Loss |     ₹3.9M |
| Highest Revenue City   | Bengaluru |

---

## Key Insights

* Bengaluru generated the highest revenue and order volume, followed by Mumbai and Delhi.
* Tier-2 cities showed lower revenue despite healthy demand, indicating growth opportunities.
* Order cancellations accounted for an estimated **₹3.9M** in revenue loss.
* Nearly **64%** of deliveries exceeded the defined SLA.
* Customer ratings declined significantly as delivery times increased, highlighting the impact of operational efficiency on customer experience.

---

## Business Recommendations

* Improve delivery partner allocation during peak demand.
* Optimize restaurant preparation times to reduce delays.
* Prioritize operational improvements in high-volume cities.
* Increase Average Order Value through targeted pricing and promotional strategies.

---

## Dashboard

> **Power BI Executive Dashboard**

(<img width="965" height="549" alt="image" src="https://github.com/user-attachments/assets/bf9ce0fd-a24f-4460-acb7-52fb31ff5bcf" />)

---

## Technology Stack

| Category        | Tools          |
| --------------- | -------------- |
| Database        | MySQL          |
| Query Language  | SQL            |
| Data Analysis   | Python, Pandas |
| Visualization   | Power BI       |
| Documentation   | Notion         |
| Version Control | Git, GitHub    |

---

## Repository Structure

```text
├── data/
├── sql/
├── notebooks/
├── dashboard/
├── images/
├── documentation/
└── README.md
```

---

## Documentation

Detailed SQL queries, methodology, dashboard, and business analysis are available in the project documentation.

**📖 Full Case Study:**
https://www.notion.so/Food-Delivery-Crisis-Recovery-Analytics-260c4eacd6ff80909253c169a6664326

---

