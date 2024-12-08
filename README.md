# Home Credit Default Risk

## Project Overview
This project addresses the challenge of financial inclusion by predicting the repayment abilities of loan applicants using alternative data sources. The predictive models aim to reduce default rates while increasing approval rates for creditworthy individuals.

## Business Problem
Many individuals in developing markets lack traditional credit histories, making it difficult to assess creditworthiness. Home Credit aims to provide loans to these individuals by leveraging alternative data sources to predict repayment potential.

## Approach
1. **Exploratory Data Analysis (EDA)**:
   - Identified key patterns and relationships between features and the target variable.
   - Addressed data quality issues, including missing values and outliers.
   
2. **Modeling**:
   - Trained and evaluated multiple models, including Logistic Regression and Random Forest.
   - Selected Random Forest as the best-performing model based on its AUC and feature importance analysis.

3. **Results**:
   - Random Forest achieved an AUC score of X.XX, highlighting its ability to distinguish defaulters from non-defaulters.
   - Key predictors included external credit scores, demographic factors, and employment details.

## Key Insights
- Alternative data sources, such as `EXT_SOURCE_2`, significantly contribute to accurate credit scoring.
- Predictive models can enable Home Credit to approve loans for underserved individuals while minimizing risk.

## Challenges
- Addressing class imbalance between defaulters (8%) and non-defaulters (92%).
- Identifying the most relevant features from a large dataset with over 120 variables.

## Lessons Learned
- The importance of data preprocessing and feature engineering in improving model performance.
- How alternative data sources can address traditional gaps in credit scoring.

- ## Contact
For any inquiries, feel free to reach out:
- **Name**: Andy Pan
- **Email**: andypan0825@gmail.com
- **LinkedIn**: https://www.linkedin.com/in/yuchipan/
