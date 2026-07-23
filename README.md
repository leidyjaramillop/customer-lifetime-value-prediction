# Customer Lifetime Value Prediction using BG/NBD and Gamma-Gamma Models

## Project Overview

Customer Lifetime Value (CLV) is one of the most valuable metrics for understanding the long-term profitability of customers.

In this project, I applied probabilistic models to predict future customer purchasing behavior, estimate Customer Lifetime Value (CLV), identify customers at risk of churn, and generate actionable business recommendations.

The analysis was performed using the **Online Retail** dataset and the **Lifetimes** Python library.

---

## Business Problem

Not all customers contribute equally to a company's future revenue.

This project aims to answer questions such as:

- Which customers are expected to generate the highest future value?
- Which customers are at risk of churning?
- How should customers be prioritized for marketing and retention campaigns?

---

## Dataset

**Online Retail Dataset**

- 541,909 transactions
- 4,372 unique customers
- UK-based online retail company
- Observation period: December 2010 – December 2011

---

## Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Lifetimes

---

## Project Workflow

- Data Cleaning
- Exploratory Data Analysis (EDA)
- RFM Feature Engineering
- BG/NBD Model
- Gamma-Gamma Model
- Customer Lifetime Value Prediction
- Customer Segmentation
- Business Recommendations

---

## Main Results

The project successfully:

- Predicted the expected number of future purchases for each customer.
- Estimated the probability that each customer remains active.
- Calculated Customer Lifetime Value (CLV) over a 6-month horizon.
- Segmented customers into business-oriented groups.
- Identified high-value customers at risk of churn.

---

## Business Insights

Key findings include:

- Most customers generate relatively low lifetime value.
- A small group of VIP customers contributes a disproportionately large share of future revenue.
- Most customers have a high probability of remaining active.
- High-value customers at risk of churn should be prioritized through personalized retention strategies.

---

## Repository Structure

```
customer-lifetime-value-prediction/
│
├── data/
│   └── Online Retail.xlsx
│
├── notebooks/
│   └── Customer_Lifetime_Value_Prediction.ipynb
│
├── images/
│
├── README.md
├── requirements.txt
└── .gitignore
```

---

## Future Improvements

Possible extensions of this project include:

- Building an interactive Power BI dashboard.
- Deploying the model using Streamlit.
- Automating monthly CLV predictions.
- Comparing probabilistic models with Machine Learning approaches.

---

## Author

**Leidy Jaramillo**

Data Analyst | Python | SQL | Power BI | Data Science

LinkedIn: *https://www.linkedin.com/in/leidy-viviana-jaramillo-parra-1987a0153/*
