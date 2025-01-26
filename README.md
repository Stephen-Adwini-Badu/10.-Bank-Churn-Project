# Bank Churn Prediction Project

## Project Objective
This project aims to predict customer churn in a banking environment using machine learning models. The goal is to identify patterns in customer behavior that lead to churn and use predictive analytics to classify customers as churners or non-churners.

## Dataset Description
Two datasets are utilized:
- **Training Dataset:** Contains labeled data for model training.
- **Testing Dataset:** Unlabeled data for evaluating model performance.

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
- Evaluation metrics include:
  - Accuracy
  - Precision, Recall, F1-Score
  - ROC-AUC Score
  - Confusion Matrix Visualization

## Machine Learning Models
- **Random Forest Classifier:** Ensemble method that builds multiple decision trees.
- **Gradient Boosting Classifier:** Boosting technique for sequential model improvement.
- **XGBoost Classifier:** Optimized gradient boosting implementation.

## Results and Metrics
- **Model Performance:** Metrics for evaluating the effectiveness of predictions.
<table align="center">
 <tr>
   <th>MODEL</th>
   <th>ACCURACY</th>
   <th>PRECISION</th>
   <th>RECALL</th>
   <th>F1 SCORE</th>
   <th>ROC-AUC</th>
 </tr>
 <tr>
   <td>Random Forest Classifier</td>
   <td align="center">86.0%</td>
   <td align="center">73.0%</td>
   <td align="center">53.0%</td>
   <td align="center">61.0%</td>
   <td align="center">74.0%</td>
 </tr>
 <tr>
   <td>Gradient Boosting Classifier</td>
   <td align="center">86.0%</td>
   <td align="center">75.0%</td>
   <td align="center">53.0%</td>
   <td align="center">62.0%</td>
   <td align="center">74.0%</td>
 </tr>
 <tr>
   <td>X Gradient Boosting Classifier</td>
   <td align="center">86.0%</td>
   <td align="center">74.0%</td>
   <td align="center">56.0%</td>
   <td align="center">64.0%</td>
   <td align="center">75.0%</td>
 </tr>
</table>

- Including Confusion Matrices

![10 1](https://github.com/user-attachments/assets/5e8eb47b-d4f5-4960-a0fc-971819c66062)


- And ROC-AUC and Calibration Curves

![10 2](https://github.com/user-attachments/assets/b279708a-6a7a-45f9-af80-3c6f467df1e4)

<br>

- **Insights:** Identification of key factors contributing to customer churn.
  - Key Factors:
  - **Age**
  - **Active Membership**
  - and **Number of Products**

  ![Image](https://github.com/user-attachments/assets/9506dfc1-3f45-4770-b3f1-169628f452bf)
  
