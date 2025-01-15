# Bank Churn Prediction Project

## Project Objective
This project aims to predict customer churn in a banking environment using machine learning models. The goal is to identify patterns in customer behavior that lead to churn and use predictive analytics to classify customers as churners or non-churners.

## Dataset Description
Two datasets are utilized:
- **Training Dataset:** Contains labeled data for model training.
- **Testing Dataset:** Unlabeled data for evaluating model performance.

Key features include:
- **CustomerID:** Unique customer identifier
- **CreditScore:** Customer’s credit score
- **Geography:** Customer location
- **Gender:** Male/Female
- **Age:** Customer age
- **Tenure:** Number of years as a customer
- **Balance:** Customer’s account balance
- **NumOfProducts:** Number of bank products used
- **IsActiveMember:** Customer’s activity status
- **EstimatedSalary:** Estimated annual salary
- **Exited:** Target variable indicating churn status (1 for churn, 0 for no churn)

## Methodology
### 1. Data Exploration and Preprocessing
- **Data Loading:** Importing datasets for analysis.
- **Data Cleaning:** Handling missing values and duplicate records.
- **Feature Transformation:** Encoding categorical features for machine learning.

### 2. Exploratory Data Analysis (EDA)
- **Statistical Analysis:** Summary statistics to understand feature distributions.
- **Visualizations:** Using Seaborn and Matplotlib to explore trends and relationships in the data.

### 3. Feature Engineering
- Selection of relevant features to improve model accuracy.
- Transformation of categorical variables using encoding techniques.

### 4. Model Training and Evaluation
- Splitting data into training and validation subsets.
- Training various models, including:
  - Random Forest Classifier
  - Gradient Boosting Classifier
  - XGBoost Classifier
  - Voting Classifier for ensemble learning
- Evaluation metrics include:
  - Accuracy
  - Precision, Recall, F1-Score
  - ROC-AUC Score
  - Confusion Matrix Visualization

## Machine Learning Models
- **Random Forest Classifier:** Ensemble method that builds multiple decision trees.
- **Gradient Boosting Classifier:** Boosting technique for sequential model improvement.
- **XGBoost Classifier:** Optimized gradient boosting implementation.
- **Voting Classifier:** Combines multiple model predictions for robust classification.

## Results and Metrics
- **Model Performance:** Metrics for evaluating the effectiveness of predictions, including confusion matrices.
- **Insights:** Identification of key factors contributing to customer churn.