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

#STEP 1: Business Objective
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

#STEP 2: Dataset Overview
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

#STEP 7: Business Milestone
Objective:
After performing EDA, we now understand the key drivers behind a customer's credit score. The next business goal is to use this knowledge for actionable decisions.

1. Build Machine Learning Models
Now that the data is clean and important features are identified, Paisabazaar can:

Use supervised learning algorithms like Logistic Regression, Random Forest, or Decision Trees
Train these models on historical data to predict future credit scores
2. Predict Credit Risk Categories
The target variable Credit_Score has 3 classes:

Good
Standard
Poor
Using the patterns uncovered (e.g., high EMI or low in-hand salary), models can predict:

Who is likely to default
Who qualifies as low-risk
Who needs manual verification
3. Detect Fraud in Early Stages
Patterns like:

High number of credit inquiries
Irregular payment behavior
Extreme credit utilization
...can be flagged as fraud risk indicators. This helps:

Reduce financial loss
Prevent issuing loans to default-prone applicants
Outcome:
Paisabazaar can integrate this model into their system to:

Speed up approval processes
Offer personalized products
Improve financial safety and regulatory compliance
#STEP 8: Final Summary
Data Readiness
The dataset is clean, with no missing values or incorrect types.
Categorical variables were successfully encoded.
Numerical variables were analyzed and visualized for outliers and distributions.
Key Insights from EDA:
High Annual Income and Low EMI Payments are strongly associated with Good Credit Scores.
Poor Credit Scores often correlate with:
High Number of Credit Inquiries
Late or Minimum Payments
High Credit Utilization Ratio
Business Readiness for ML Modeling:
The dataset is now prepared for training supervised machine learning models such as:

Logistic Regression
Decision Tree Classifier
Random Forest Classifier
Features like Outstanding_Debt, Total_EMI_per_month, and Payment_Behaviour are good predictors for credit scoring.

Business Value:
These insights help automate credit approvals,
Improve fraud detection,
And personalize credit products offered to users based on risk level.
Conclusion: The project has met its goal of understanding credit score patterns and preparing the ground for accurate, automated credit scoring using machine learning.
