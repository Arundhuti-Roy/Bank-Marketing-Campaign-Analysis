# Bank Marketing Campaign Performance & Customer Subscription Analysis

## Overview

An end-to-end data analytics project exploring bank marketing campaign performance and customer term-deposit subscription behavior using Excel and Power BI.

The project analyzes customer characteristics, campaign contact frequency, previous campaign outcomes, and monthly campaign performance to identify subscription patterns and derive actionable business recommendations.

## Business Problem

Bank marketing campaigns involve contacting customers to promote term deposit subscriptions, but not all customers respond positively. Understanding which customer segments show higher subscription rates and how campaign interactions relate to outcomes can help improve marketing targeting and campaign planning.

## Objectives

- Analyze customer characteristics associated with term deposit subscriptions.
- Evaluate the relationship between campaign contact frequency and subscription rates.
- Examine previous campaign outcomes and their relationship with current subscriptions.
- Identify customer segments with higher subscription rates.
- Develop data-driven insights and recommendations for campaign optimization.

## Dataset

| Attribute | Details |
|---|---|
| Source | UCI Machine Learning Repository – Bank Marketing |
| Dataset | `bank-full.csv` |
| Total Records | 45,211 |
| Input Features | 16 |
| Target Variable | `y` |
| Target Values | Yes / No |

**Dataset Source:** [UCI Bank Marketing Dataset](https://doi.org/10.24432/C5K306)

## Tools & Technologies

- **Microsoft Excel** — Data inspection, cleaning, exploratory analysis, KPI calculations, charts, dashboard
- **Power BI** — Interactive dashboard, KPI visualization, slicers, campaign performance analysis
- **Data Analytics** — Data cleaning, exploratory data analysis, segmentation, interpretation, and business recommendations

## Dashboard Preview

### Excel Dashboard

![Excel Dashboard](Excel_Dashboard.png)

### Power BI Dashboard

![Power BI Dashboard](PowerBI_Dashboard.png)

## Key Metrics

- **Total Customers:** 45,211
- **Total Subscriptions:** 5,289
- **Overall Subscription Rate:** 11.70%
- **Non-Subscriptions:** 39,922

## Key Findings

- The overall term-deposit subscription rate was **11.70%**.
- Customers with a successful previous campaign outcome exhibited a substantially higher subscription rate.
- Subscription rates generally decreased as the number of contacts during the current campaign increased.
- Subscription behavior varied considerably across campaign months.
- Customer attributes, loan status, account balance, and previous campaign interactions showed differences in subscription rates across segments.

## Business Recommendations

- Prioritize customer segments with stronger historical subscription responses.
- Avoid excessive repeated contacts and evaluate campaign contact frequency.
- Use historical campaign outcomes to inform customer targeting.
- Consider campaign timing when planning future marketing activities.
- Monitor segment-level subscription rates to refine marketing strategies.

## Repository Contents

- `bank-full.csv` — Dataset used for analysis
- Excel workbook — Data inspection, EDA, analysis, and dashboard
- Power BI report — Interactive campaign analysis dashboard
- Documentation — Business problem statement, dataset information, data dictionary, cleaning log, and EDA findings
- Dashboard screenshots — Visual previews of the completed dashboards

## Disclaimer

This project explores patterns and associations within historical marketing data. The findings do not establish causation. Campaign call duration is a post-contact variable and should not be treated as a pre-campaign targeting feature.

---

*Created as a data analytics portfolio project.*
