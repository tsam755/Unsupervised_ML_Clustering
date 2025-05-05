# Clustering Analysis of Customer Data

## 📊 Overview
This analysis performs clustering on a transactional dataset containing 54,785 customer records, aiming to segment the customer base into distinct groups. The segmentation allows for tailored marketing strategies to cross-sell and deep-sell financial products. The analysis identifies six customer segments based on product ownership, income, and transaction behavior. Strategic recommendations are provided for each segment to enhance customer engagement and financial inclusion.

## 📈 Data Description
- **Dataset Size**: 54,785 records
- **Variables**: 7 binomial variables (e.g., Churn, Loan, Credit Card, etc.) and 3 metric variables (e.g., Age, Income, Number of Transactions)
- **Data Cleaning**: 
  - Age categories adjusted to exclude customers aged 80 or above due to limited movement in product ownership.
  - Income outliers removed (customers with income over $10,000/month were excluded).
  - Churned customers were removed to focus on active customers.

## 🧑‍💼 Segmentation Strategy
The data was analyzed using a **two-step cluster analysis** (suitable for larger datasets with both continuous and categorical variables). This method produced six unique segments with high variability and significance:
1. **Low Income – No Product Owners**: 59.0% of customers
2. **Moderate Income – Savers**: 21.0% of customers
3. **High Income – Credit Heavy Savers**: 8.6% of customers
4. **High Income – Investors**: 4.7% of customers
5. **High Income – Debtors**: 4.2% of customers
6. **High Income – Homeowners**: 2.5% of customers

## 💡 Key Findings
- **Cluster 1**: The largest group, with low income and no financial product ownership. Recommended strategy: Introduce credit cards with incentives like cashback and interest rate promotions.
- **Cluster 5**: Moderate-income savers, primarily focused on savings accounts. Recommended strategy: Promote low-risk investment funds and auto loans with favorable terms.
- **Cluster 2**: High-income customers with a heavy reliance on credit cards. Strategy: Target with exclusive banking services and mortgages.
- **Cluster 3**: High-income investors with a preference for investment products. Strategy: Introduce rewards programs and encourage cross-selling of credit cards and loans.
  
## 🔧 Tools & Techniques
- **Software**: SPSS
- **Methods**: Two-step cluster analysis, Pearson correlation, ANOVA, Chi-square test, and silhouette score evaluation.
- **Statistical Tests**: Two-tailed Pearson correlation, One-way ANOVA, Chi-square test for non-metric variables.

## 📊 Evaluation and Results
The clustering analysis produced six distinct segments with high silhouette scores, indicating good separation between clusters. Evaluation was done using the **Silhouette Score**, **ANOVA**, and **Chi-Square Tests**.

## 📋 Strategies & Recommendations
Each segment was analyzed to suggest targeted marketing strategies:
- **Low Income – No Product Owners**: Offer entry-level credit products with no fees for the first year.
- **Moderate Income – Savers**: Encourage investment with low-risk funds and personal loans.
- **High Income – Credit Heavy Savers**: Provide personalized credit card upgrades and home loans.
  
## 💬 Acknowledgements
- **Acknowledgement**: This project utilizes AI tools like OpenAI’s ChatGPT for drafting and refining parts of the report, providing valuable insights and support for analysis.

## 📄 References
- **Stats NZ (2023)**: Life Expectancy Data.
- **Hair et al. (2019)**: Multivariate Data Analysis.
- **Verhoef et al. (2003)**: Customer Retention and Marketing.
- **Keiningham et al. (2007)**: The Value of Customer Satisfaction Metrics.

## ❗️Disclaimer
This project was developed as part of academic coursework and is shared here for educational and profolio purpose. Unauthorised use, reproduction or distribution is not permitted and may violate academic integrity policies. 
