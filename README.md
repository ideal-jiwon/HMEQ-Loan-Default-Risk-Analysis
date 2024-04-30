HMEQ Loan Default Risk Analysis

Overview

This report conducts an in-depth analysis of the Home Equity Loan Default dataset (HMEQ) to predict the likelihood of default using linear and logistic regression models. The study employs various statistical methods and machine learning algorithms to explore factors influencing loan default risks.

Dataset

The dataset contains 5,960 observations with 28 variables related to loan characteristics, borrower's financial history, and the outcome of the loan (default or no default). The dataset was cleaned and preprocessed before modeling.

Tools and Libraries Used

R Language: Main programming language used for analysis.
Libraries: rpart, rpart.plot, ROCR, MASS, randomForest, gbm.
Methods and Models

Data Preprocessing: Data cleaning, handling missing values, and feature engineering.
Exploratory Data Analysis: Descriptive statistics and visualization to understand the distribution and relationships among variables.
Model Building:
Logistic Regression: To estimate the probability of default.
Decision Trees and Random Forest: For classification and understanding feature importance.
Gradient Boosting: To improve prediction accuracy.
Model Evaluation: Using AUC-ROC curves, accuracy, precision, recall, and F1-score to evaluate model performance.
Results and Discussion: Interpretation of model outputs, feature importance, and model comparisons.
Key Findings

Models indicate various borrower characteristics and loan features that significantly impact the likelihood of default.
The Random Forest model showed the highest predictive accuracy among the tested models.
Conclusion

The analysis provides insights into factors that contribute to home equity loan defaults, which can assist financial institutions in improving their risk assessment frameworks.

Files Structure

HMEQ_Scrubbed.csv: The cleaned dataset used for the analysis.
HMEQ_Analysis.R: R scripts containing all the analyses, including data cleaning, model building, and evaluation.
