# Customer Marketing EDA — AI Lab 99 ML Internship 2026 (Module 4)

Exploratory Data Analysis on a customer marketing dataset to understand
customer demographics, spending behavior, purchasing channels, website
engagement, campaign performance, and complaint patterns — producing a
rule-based customer segmentation and a set of business recommendations.

**Program:** AI Lab 99 Internship Program 2026 — Machine Learning Track
**Module:** Module 4 — Exploratory Data Analysis (`ML-M04`)
**Intern:** Usman Khan

## Dataset

`data/marketing_campaign.csv` — 2,240 customer records x 29 features
(the widely-used "Customer Personality Analysis" marketing dataset),
covering demographics, product spending, purchase channels, campaign
responses, and website engagement.

## Project Structure

```
├── data/
│   └── marketing_campaign.csv         # Raw dataset (tab-separated)
├── notebooks/
│   └── EDA_Customer_Marketing.ipynb   # Full EDA notebook (Tasks 1–11)
├── src/
│   ├── data_loader.py                 # Loading + cleaning utilities
│   ├── eda_utils.py                   # Analysis + plotting functions
│   └── eda_full_analysis.py           # Notebook exported as a plain script
├── visuals/                           # All generated charts (.png)
├── reports/
│   ├── EDA_Report.pdf                 # Technical EDA report
│   └── Business_Insights_Report.pdf   # Business insights + recommendations
├── requirements.txt
└── README.md
```

## Tasks Covered

1. Dataset overview (shape, dtypes, duplicates, missing values, statistics)
2. Customer demographic analysis (age, income, education, marital status, household)
3. Customer spending analysis (by category: Wine, Fruits, Meat, Fish, Sweets, Gold)
4. Purchasing behavior analysis (store, web, catalog, deals)
5. Website engagement analysis (visits, conversion)
6. Customer recency analysis (active vs. inactive)
7. Marketing campaign analysis (5 historical campaigns + latest response)
8. Customer complaint analysis
9. Correlation analysis (Pearson correlation heatmap)
