# Swiggy Instamart – Detailed Dashboard Explanation

## 📌 Purpose of This Document

This document provides a detailed explanation of each dashboard page, including KPIs, visualizations, business logic, and insights derived from the analysis.

The objective is to demonstrate both technical implementation (DAX & Power BI modeling) and business understanding.

## 🗂 Dashboard Structure Overview

The dashboard consists of the following pages:

1. Home page

2. Executive Dashboard Overview

3. Customer Analytics

4. Product Analysis

5. Geographic Analysis

Each page is designed to answer specific business questions and support data-driven decision-making.

# 1️⃣ Home page

<img width="870" height="485" alt="Screenshot 2026-02-20 214721" src="https://github.com/user-attachments/assets/bf6ef400-d1be-4a94-9674-ed70527b7a31" />

## 🎯 Objective

This page acts as the entry screen of the dashboard, providing branding context and smooth navigation to the main analytical pages.

### 🧩 Key Elements

Tagline: “Never wait for groceries again”

Navigation button to access main dashboard

Clean visual design for professional presentation

### 💼 Business Purpose

Improves user experience

Creates structured navigation flow

Makes the dashboard presentation-ready for stakeholders

# 2️⃣ Executive Dashboard Overview

<img width="877" height="491" alt="Screenshot 2026-02-13 214412" src="https://github.com/user-attachments/assets/2bbd151f-0b8a-4dee-9806-d2e0a6cc0f36" />

## 🎯 Objective

Provide a high-level summary of overall business performance.

### Key KPIs:

Total Orders: 0.84K

Total Revenue: 8.40M

Quantity Sold: 4.61K

Average Order Value: 9.99K

### Highlights:

Most Ordered Product: Fresh Vegetables

Top Supplier: HUL Distributors

Top Delivery Partner: Amit Singh

### Insight:

Fresh produce drives the highest demand, indicating strong customer preference for daily essentials.

Revenue is concentrated among key product categories.

Strong AOV indicates healthy customer purchasing behavior.

# 3️⃣ Customer Analytics

<img width="876" height="491" alt="Screenshot 2026-02-13 214650" src="https://github.com/user-attachments/assets/a59e9cc1-63f3-4bf9-9455-e2f90b30920c" />

## 🎯 Objective

Analyze customer purchasing patterns and revenue contribution.

### Customer Metrics:

Revenue per Customer: 108.26K

Orders per Customer: 11.72

Top 20 Customers

Revenue by Customer Segment

### Revenue by Segment:

High Value Customers: 38% contribution

Frequent Shoppers: 28%

New Users: 21%

Lapsed Customers: 12%

### Insight:

High-value customers contribute the largest share of revenue.

Revenue per customer shows strong monetization potential.

Identifying top customers supports retention strategies.

# 4️⃣ Product Analysis

<img width="878" height="492" alt="Screenshot 2026-02-13 214756" src="https://github.com/user-attachments/assets/f093726d-16a2-480e-98db-37e34619ae73" />

## 🎯Objective

To evaluate product performance, monitor growth trends, and assess the impact of pricing adjustments on revenue and profit.

### Key KPIs:

1️⃣ Monthly Performance vs Target

Monthly Orders vs Target

Monthly Revenue vs Target

Monthly Profit vs Target

Logic Used:
Targets are dynamically set at 10% higher than previous month performance using DAX time intelligence functions.

2️⃣ Time-Based Trend Analysis

Weekly Revenue Trend

Quarterly Revenue Trend

Adjusted Profit vs Actual Profit

This helps detect:

Seasonal demand patterns, Revenue spikes, Performance fluctuations

3️⃣ Category & Product Filtering

Select Category slicer

Select Product dropdown

Matrix KPI selection

Allows dynamic analysis of:

Total Orders,Total Revenue,Quantity Sold,Average Order Value,Total Profit

 4️⃣ Price Adjustment Scenario

What-If parameter for price adjustment percentage

Adjusted Revenue & Adjusted Profit calculation

Supports simulation of pricing strategy impact.

### Insight:

Top categories contribute majority of revenue.

Monthly tracking ensures growth monitoring.

Price adjustment simulation supports profit optimization.

Seasonal spikes suggest promotional opportunities.

# 5️⃣ Geographic Analysis (Map View)

<img width="876" height="490" alt="Screenshot 2026-02-13 214838" src="https://github.com/user-attachments/assets/77fe286b-2578-456f-9ca8-33b41fee9cc9" />

## 🎯 Objective

Visualize state-wise sales performance.

### Metrics Displayed

State-wise Revenue

Total Orders by Region

Customer Count by State

### Insights:

Revenue concentration observed in specific high-performing states.

Supports regional marketing and expansion decisions.

Identifies underperforming regions for growth opportunity.

## 🎯 Overall Business Impact

This dashboard:

Enables performance tracking against monthly growth targets

Identifies high-revenue customer segments

Highlights top-performing product categories

Supports pricing and scenario analysis

Provides regional insights for strategic expansion





