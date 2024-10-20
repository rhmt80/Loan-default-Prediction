
# Loan Default Prediction for Retail Banks
Developed a classification model to predict clients likely to default on loans. Despite working with a limited dataset, successfully built and hyper-tuned a Random Forest model, achieving an 80% recall score. Conducted extensive EDA and feature analysis, identifying key predictors and providing actionable business recommendations for improved loan approval processes.


## Context
A significant portion of retail bank profits comes from interest on home loans, particularly from regular income and high-earning customers. However, banks face considerable risks from loan defaulters, as non-performing assets (NPA) can severely impact profitability. To mitigate this risk, banks must be judicious in loan approvals, carefully identifying potential defaulters.
## Objective
The project aimed to:

1. Conduct Exploratory Data Analysis (EDA) and feature analysis to provide key recommendations on factors that banks should consider when approving loans.

2. Develop a classification model to predict customers likely to default on loans, focusing on maximizing recall to minimize false negatives (i.e., missing potential defaulters) while also maintaining a strong F1-Score to balance overall accuracy and minimize false positives, which could lead to lost interest profits.
## Challenges
This project involved working with a suboptimal dataset, characterized by missing values and outliers. Instead of seeking additional data, the goal was to treat this as a real-world problem, optimizing the model with the available limited dataset while still aligning with business objectives.
## Results
1. Extensive data cleaning was performed to handle missing values and outliers.
2. Developed and optimized a Hyper Tuned Random Forest model, achieving an 80% recall score while maximizing recall to prioritize identifying potential defaulters.
3. Identified DEBTINC (Debt-to-Income Ratio) as the most influential predictor of loan defaults, alongside other key features: CLAGE (Age of Credit Line), VALUE (Property Value), NINQ (Number of Inquiries), and Loan Amount.
4. Provided four high-impact business recommendations based on the model and EDA findings to improve future loan approval processes.