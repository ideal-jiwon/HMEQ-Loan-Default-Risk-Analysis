# Home Equity Loan Default Analysis

## 📊 Dataset Overview

The dataset consists of **5,960 observations** with **28 variables** covering:

- **Loan characteristics**
- **Borrower's financial history**
- **Loan outcomes** (default or no default)

The dataset was thoroughly **cleaned and preprocessed** before proceeding to the modeling phase.

---

## 🛠️ Tools and Libraries Used

The analysis was conducted using the **R programming language**, leveraging the following libraries:

- **Data Processing & Visualization:**  
  - `rpart`, `rpart.plot`, `MASS`
- **Modeling:**  
  - `randomForest`, `gbm`
- **Evaluation:**  
  - `ROCR`

---

## 🚀 Methodology

The analysis followed a structured pipeline, including the following key steps:

### 1. **Data Preprocessing**
- Cleaning and handling missing values
- Feature engineering to enhance model performance

### 2. **Exploratory Data Analysis (EDA)**
- Descriptive statistics to understand variable distributions
- Visualizations to identify trends and relationships

### 3. **Model Building**
- **Logistic Regression:**  
  - Estimation of the probability of loan default.
- **Decision Trees & Random Forest:**  
  - Classification models and feature importance analysis.
- **Gradient Boosting:**  
  - Enhanced accuracy through ensemble learning.

### 4. **Model Evaluation**
- Performance metrics used for evaluation:
  - **AUC-ROC curves**
  - **Accuracy, Precision, Recall, and F1-score**

### 5. **Results and Discussion**
- Interpretation of key variables affecting loan default
- Model comparison and performance analysis

---

## 📈 Key Findings

- Several borrower and loan characteristics significantly influence the likelihood of default.
- The **Random Forest model** achieved the highest predictive accuracy among all tested models.

---

## 🏁 Conclusion

This analysis provides valuable insights into the factors influencing home equity loan defaults.  
The findings can aid financial institutions in enhancing their **risk assessment frameworks**, enabling better loan approval decisions.

---

## 📂 File Structure

The project consists of the following files:

- **`HMEQ_Scrubbed.csv`** – The cleaned dataset used for analysis.
- **`HMEQ_Analysis.R`** – R script containing:
  - Data preprocessing
  - Model building
  - Model evaluation

