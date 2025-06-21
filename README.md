# Paisabazaar-EDA
Credit Score Classification using EDA for Internship Submission
## Project Summary

**Title**: Credit Score Classification using EDA  
**Objective**: To explore customer data from Paisabazaar and classify individuals into `Good`, `Standard`, or `Poor` credit score categories. This helps in automating credit decisions and detecting potential fraud.

### Dataset
- 100,000 rows, 28 features
- Target variable: `Credit_Score`
- Features: Income, EMI, Payment Behavior, Credit Mix, Inquiries, etc.

### Methods Used
- Data Cleaning (no missing values)
- Label Encoding for categorical variables
- Visualization: Histograms, Boxplots, Correlation Matrix
- Analysis: Univariate, Bivariate, Multivariate

### Insights
- High income & low EMI → Good score
- Many credit inquiries & late payments → Poor score
- Features like Credit Mix & Outstanding Debt were predictive

STEP 1: Business Objective
Goal:
Paisabazaar, one of India’s largest financial platforms, aims to classify customers based on their credit scores into three categories:

Good
Standard
Poor
1. Detect Fraud Risks
Early detection of risky customers helps reduce default and fraud losses.

2. Automate Loan Approvals
Credit score-based filtering allows faster, real-time loan approvals and disbursals.

3. Evaluate Creditworthiness
Analyze financial behavior to assess loan repayment capacity and offer personalized products.

Business Impact:
This model helps Paisabazaar minimize financial risks, automate credit decisions, and improve user trust.

STEP 2: Dataset Overview
Dataset Summary:
Records: 100,000 customer entries
Columns: 28 features, including both numerical and categorical data
Target Variable:
Credit_Score — This is the classification label with values:
Good
Standard
Poor
Key Features:
Column Name Age Annual_Income Monthly_Inhand_Salary Num_Credit_Card
Outstanding_Debt Total_EMI_per_month Num_Credit_Inquiries Credit_Mix Payment_Behaviour Payment_of_Min_Amount

The dataset contains detailed financial, behavioral, and demographic data for customers across multiple months — ideal for credit risk assessment.

### Business Impact
- Faster loan approvals
- Early fraud detection
- Better credit risk evaluation

