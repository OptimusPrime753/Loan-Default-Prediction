# 🏦 Loan Default Prediction System
The Loan Default Prediction System is a machine learning project designed to predict whether a customer is likely to default on a loan based on historical loan and borrower information. This project aims to assist financial institutions in risk assessment, credit decision-making, and minimising loan defaults.
Multiple machine learning models were trained and evaluated to compare performance and interpretability

# 🎯 Objectives

- Perform Exploratory Data Analysis (EDA) on loan data
- Handle categorical and numerical features
- Build and evaluate multiple ML models
- Compare model performance using evaluation metrics
- Identify important features influencing loan default
- Create a robust and reproducible ML pipeline

# Dataset

The dataset contains historical loan application records
Includes borrower demographics, loan characteristics, credit history, and loan status
Target variable:
loan_status
0 → Non-default
1 → Default

The dataset used in the notebook is loaded as loan.

# 🔍 Exploratory Data Analysis (EDA)

### Key EDA steps performed:
Distribution analysis of numerical features
Analysis of categorical variables
Loan approval vs default trends
Correlation analysis
Handling missing values
Encoding categorical features

A heatmap was created after proper encoding to visualise correlations between features.

# ⚙️ Models Implemented
- Logistic regression
- Decision Tree
- Random forest

# 📊 Model Evaluation

Models were evaluated using:
- Accuracy
- Confusion Matrix
- Classification Report (Precision, Recall, F1-score)

Random Forest showed better generalisation performance compared to individual models.

# 🔑 Feature Selection

Feature importance from the Random Forest model was used to:
- Identify top contributing features
- Retrain models using selected features
- Improve model efficiency and interpretability

# 📈 Results & Insights

- Past loan defaults strongly influence current loan approval
- Credit-related variables are key predictors
- Ensemble models perform better in identifying risky borrowers
- Feature selection improves performance stability

# How to Run the Project
- Open the notebook
  jupyter notebook Loan_default_prediction.ipynb


## 👤 Author

### Suraj Nirgun
Aspiring Data Analyst.
