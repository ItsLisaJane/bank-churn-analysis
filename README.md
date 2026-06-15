# Retail Bank Customer Churn Analysis

## Live Dashboard

**View the interactive Tableau dashboard here:**

👉 [Customer Churn Analysis Dashboard](https://public.tableau.com/app/profile/lisa.bentman/viz/Customer_Churn_Analysis_17812629692820/CustomerChurnAnalysis)


## Project Overview

Analysed 5,000 retail banking customers and 12 months of behavioural activity data to identify the key drivers of customer churn and develop targeted retention recommendations.

## Business Problem

Customer attrition reduces revenue, increases acquisition costs and weakens long-term profitability.

This project investigates which customer segments are most likely to churn and identifies actionable opportunities to improve retention.

## Dataset

The analysis combines:

- 5,000 retail banking customers
- 12 months of activity data
- Customer demographics
- Product holdings
- Complaint history
- Mobile engagement metrics
- Transaction activity
  
## Tools Used

- Python
- Pandas
- SQL
- Tableau
- Jupyter Notebook
- Git/GitHub

## Methodology

1. Data Quality Assessment
2. Data Cleaning & Standardisation
3. Customer-Level Dataset Construction
4. Exploratory Data Analysis
5. Churn Driver Identification
   
## Key Findings

**1. Early Customer Attrition Represents The Largest Retention Opportunity**
- New customers experienced the highest churn rates.
- Customers with zero tenure churned at 14.6%.
- Younger customer churn appears strongly linked to tenure.</br>
</br>
<img width="499" height="277" alt="churn_by_age" src="https://github.com/user-attachments/assets/2e56ec71-183d-4493-bda1-3476937f79da" />
 
**2. Complaint Volume Is Strongly Associated With Customer Churn**
- Customers with multiple complaints were significantly more likely to leave the bank.</br>
</br>
<img width="488" height="182" alt="complaints_vs_churn" src="https://github.com/user-attachments/assets/b7d10c69-e8fc-4163-95da-baf567757d10" />

**3. Deeper Customer Relationships Improve Retention**
- Single-product customers exhibited the highest churn rates.
- Multi-product customers showed stronger retention.</br>
</br>
<img width="971" height="217" alt="product_count_vs_churn" src="https://github.com/user-attachments/assets/7813db68-5506-4533-b8c7-18020c680072" />

**4. Low Digital Engagement Is The Strongest Predictor Of Churn**
- Low-engagement customers were approximately six times more likely to churn.</br>
</br>
<img width="1368" height="291" alt="engagement_vs_churn" src="https://github.com/user-attachments/assets/103f2944-e298-423a-b591-b0d100073a08" />

## Business Recommendations

- Improve onboarding journeys.
- Prioritise complaint resolution and service recovery.
- Cross-sell relevant products to eligible customers.
- Increase mobile app engagement through targeted campaigns.

## Deliverables

### Visualisations

- [Tableau Public Dashboard](https://public.tableau.com/app/profile/lisa.bentman/viz/Customer_Churn_Analysis_17812629692820/CustomerChurnAnalysis)

### Analysis

- [Data Preparation Notebook](notebooks/01_data_preparation.ipynb)
- [Exploratory Analysis Notebook](notebooks/02_eda_and_insights.ipynb)

### Presentation

- [Executive Summary Deck](slides/Customer_Churn_Analysis.pdf)</br>
</br>
<img width="1071" height="649" alt="tableau_dashboard" src="https://github.com/user-attachments/assets/cf3be14d-b7d6-4db8-a7eb-1a0840316fef" />

## Disclaimer

This project was completed for portfolio and learning purposes using a simulated retail banking dataset.
