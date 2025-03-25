# bank-marketing-campaign-analysis
Bank Marketing Campaign Analysis: Predicting Long-Term Deposit Subscriptions
Overview
This project applies classification algorithms to analyze the effectiveness of bank marketing campaigns in driving long-term deposit subscriptions. By leveraging machine learning, the study identifies key factors influencing customer engagement and optimizes campaign strategies for financial institutions.

Problem Statement
Banks invest heavily in marketing campaigns, yet conversion rates remain low. Understanding which factors drive customer engagement can improve targeting and optimize marketing efforts, leading to better resource allocation and higher deposit subscriptions.

Dataset
Source: UCI Machine Learning Repository

Number of Records: 45,000+ customer interactions

Key Features:

Age, Job Type, Marital Status, Education

Contact Method, Campaign Duration, Previous Campaign Response

Loan & Credit History, Balance, Default Status

Outcome: Subscribed (Yes/No)

Methodology
✔ Data Preprocessing: Categorical encoding, handling missing values, normalizing numerical features.
✔ Exploratory Data Analysis (EDA): Identified high-impact variables influencing subscription rates.
✔ Feature Selection: Optimized model efficiency by reducing irrelevant features.
✔ Model Development: Applied Logistic Regression, Decision Trees, Random Forest, and AdaBoost classifiers.
✔ Model Evaluation: Assessed performance using Precision, Recall, F1-Score, ROC Curves.

Key Findings
✔ The AdaBoost model outperformed others, achieving F1-score of 0.57.
✔ Customers with higher balance & previous campaign engagement were more likely to subscribe.
✔ Cold calls & longer campaign durations negatively impacted customer response rates.

Real-World Applications
✔ Banks can refine customer targeting for better campaign effectiveness.
✔ Optimized marketing strategies can reduce costs and improve ROI.

Technologies Used
✔ Python (Pandas, NumPy, Scikit-Learn, Matplotlib, Seaborn)
✔ Machine Learning Models: Logistic Regression, Decision Trees, Random Forest, AdaBoost
✔ Evaluation Metrics: Precision, Recall, F1-Score, AUC-ROC
