# 🏦 Bank Marketing Campaign Performance Dashboard

An interactive Excel-based Business Intelligence dashboard built to analyze **45,212+** bank telemarketing transactions and transform raw retail banking data into actionable customer insights using advanced Excel analytics techniques.

---

# 📌 Project Overview

This project focuses on building a dynamic and interactive campaign analytics dashboard in Microsoft Excel using:

- Power Query (ETL & Data Cleaning)
- Pivot Tables
- Pivot Charts
- Slicers
- KPI Cards
- Dashboard UI/UX Principles

The dashboard enables business users to dynamically filter and analyze campaign conversion success across:

- Job Roles
- Marital Status
- Education Levels
- Communication Channels
- Housing & Personal Loans

---

# 🎯 Business Objective

The goal of this project was to simulate a real-world financial analytics environment where marketing executives and sales teams can:

- Monitor overall campaign conversion rates
- Analyze customer profession responsiveness
- Evaluate communication channel effectiveness (Cellular vs. Telephone)
- Track account balances and financial risk indicators
- Identify top-performing client segments for term deposits
- Generate data-driven telemarketing recommendations

---

# 📊 Dashboard Features

## ✅ Dynamic KPI Cards
- Total Campaigns (`45,212`)
- Overall Conversion Rate (`~11.7%`)
- Average Account Balance (`€1,362`)

All KPIs dynamically update based on user selections.

---

## ✅ Interactive Slicers
Implemented universally connected slicers for:

- Marital Status
- Education Level

All slicers are fully synchronized across every underlying Pivot Table and chart.

---

## ✅ Visual Analytics
### Included Charts:
- Campaign Conversion Rate by Job Role (100% Stacked Bar Chart)
- Telemarketing Channel Effectiveness & Call Duration (Clustered Column Chart)

---

# 🧠 Key Business Insight

Using dashboard segmentation, I discovered:

> While **Management** and **Technician** job categories generate the highest total volume of campaign interactions, specific student and professional sub-segments show unique conversion spikes when engaged via targeted cellular communication channels.

This demonstrates how interactive filtering can uncover hidden conversion patterns and optimize marketing resource allocation.

---

# 🏗️ Analytics Architecture

## 🔹 Data Engineering & ETL
- Extracted and structured raw transactional bank marketing dataset
- Cleaned and uppercased column headers
- Handled and re-mapped missing/unknown attributes professionally
- Standardized numerical indicators and call metrics

---

## 🔹 Data Modeling
- Built backend analytical aggregation engine using Pivot Tables
- Connected multiple dimensional layers (Demographics vs. Campaign Outcomes)
- Processed multi-variable metrics for subscription success (`y = Yes/No`)

---

## 🔹 Dashboard UI/UX
- Designed a clean, gridless executive dashboard canvas
- Built interactive slicer-driven navigation
- Applied visual hierarchy principles and professional color styling
- Optimized layout for executive decision-making readability

---

## 🔹 Business Intelligence
- Converted 45,000+ raw records into strategic acquisition insights
- Enabled segment-level behavioral analysis
- Created a robust reporting and decision-support analytics system

---

# 🛠️ Tools & Technologies Used

| Tool | Purpose |
|------|---------|
| Microsoft Excel | Dashboard UI & Development |
| Power Query | Data Transformation & ETL |
| Pivot Tables | Data Aggregation & Modeling |
| Pivot Charts | Advanced Visualizations |
| Slicers | Interactive Filtering Engine |
| Excel Formulas | Data Formatting & Metrics |

---

# 📂 Project Structure

```bash
Bank-Marketing-Dashboard/
│
├──  bank_marketing.csv
│   
│
├── dashboard_screenshot.png
│   
│
├── Bank_Marketing_Analysis.xlsx
│
└── README.md
