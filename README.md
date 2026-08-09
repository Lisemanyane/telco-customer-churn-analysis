# Customer Churn Analysis — Telco Customer Churn Dataset

Data Analytics Internship Project — **AnalystLab Africa**

## Overview

This project analyzes customer churn for a telecommunications company using the Telco Customer Churn
dataset (7,043 customers, 21 features). The goal is to identify which customer segments are most likely
to churn and translate those findings into actionable business recommendations.

**Overall churn rate: 26.5%** — more than 1 in 4 customers in this dataset have left the company.

## Key Findings

- **Contract type is the strongest churn driver.** Month-to-month customers churn at 42.7%, compared to
  11.3% for one-year contracts and just 2.8% for two-year contracts.
- **Fibre-optic customers churn the most of any internet service tier** (41.9%), despite being the
  premium product — more than double the DSL churn rate (19.0%).
- **Payment method matters.** Electronic check users churn at 45.3%, roughly 3x the rate of customers on
  automatic payment methods.
- **Tenure and churn are strongly inversely related** — the first year of the customer relationship is
  the highest-risk period for losing a customer.
- **Senior citizens churn at nearly double the rate of non-seniors** (41.7% vs. 23.6%).

## Repository Structure

```
├── data/
│   └── WA_Fn-UseC_-Telco-Customer-Churn.csv     # Raw dataset
├── notebook/
│   └── Customer_Churn_Analysis.ipynb            # Full analysis: cleaning, EDA, visualizations
├── reports/
│   ├── Business_Analytics_Report.docx           # Business understanding, analysis, insights, recommendations
│   └── Dataset_Inspection_Report.docx           # Detailed data inspection findings
├── presentation/
│   └── Business_Presentation.pptx               # Summary slide deck
└── README.md
```

## Methodology

1. **Business Understanding** — defined the business problem, key questions, and stakeholders.
2. **Data Inspection** — checked rows, columns, data types, missing values, and duplicates. Found that
   `TotalCharges` was stored as text and concealed 11 hidden blank entries (all zero-tenure customers)
   that a standard null-check missed.
3. **Exploratory Analysis** — built 10 visualizations (bar charts, pie charts, histograms, a box plot,
   and a correlation heatmap) to explore churn from multiple angles.
4. **Insights & Recommendations** — translated the visual findings into 5 key insights, 3 business
   risks, 3 opportunities, and 6 actionable recommendations for reducing churn.

## Tools Used

Microsoft Excel — PivotTables, PivotCharts, CORREL(), and formula-based data inspection
Microsoft Word — Business Analytics Report and Dataset Inspection Report
Microsoft PowerPoint — Business Presentation

## Recommendations Summary

1. Launch a contract upgrade campaign targeting month-to-month customers
2. Investigate fibre-optic service quality and pricing
3. Promote automatic payment enrolment over electronic check
4. Strengthen new-customer onboarding in the first 90 days
5. Build a senior-citizen retention track with simplified plans
6. Deploy a churn-risk scoring model for proactive retention

## Author

Lisemanyane Paul Mporoane
Data Analytics Intern, AnalystLab Africa

---
*This project was completed as part of the AnalystLab Africa Data Analytics Internship Programme.*
