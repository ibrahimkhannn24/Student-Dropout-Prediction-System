# Student Dropout Prediction System
This project explores predicting student dropout rates in higher education using a real-world dataset of 4,424 records from a Portuguese institution. The dataset includes academic, financial, demographic, and socioeconomic features. Key components of the project include:

- Data Preprocessing: Addressed class imbalance using SMOTE, handled outliers with IQR-based capping, and engineered features such as semester approval rates and grade gaps to enhance predictive power.

- Exploratory Analysis: Analyzed key factors influencing dropout, including academic performance, tuition fee status, marital status, and attendance patterns. Found that second-semester approval rates and financial stability were the strongest predictors of dropout.

- Modeling: Developed and evaluated five classification models (Random Forest, Gradient Boosting, Logistic Regression, SVM, Decision Tree) using cross-validation and metrics like accuracy, recall, and AUC.
  - Random Forest: Best performance with 90.08% accuracy and 0.9636 AUC.
  - Gradient Boosting: Competitive results with 89.01% accuracy and 0.9514 AUC.
  - Logistic Regression: Moderate performance with 87.3% accuracy but weaker recall for dropout predictions.

- Findings:
  - Strongest predictors of dropout include second-semester approval rates, tuition fee status, and scholarship holding.
  - Evening students and legally separated individuals face higher dropout risks.
  - Academic performance after enrollment outweighs pre-enrollment factors in predicting attrition.
    
This repository demonstrates end-to-end dropout prediction, from preprocessing to model evaluation, using Python, Jupyter Notebook, and libraries like scikit-learn, pandas, matplotlib, and seaborn.
