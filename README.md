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
- ### Model Performance:  
  Overall, while all three models have similar accuracy, **X Gradient Boosting** appears to have a slight edge in terms of F1 score and ROC AUC  

   - **Similar Accuracy:**  
   All three models have the **same accuracy of 86.0%**, indicating that they are equally good at predicting the correct class.  

   - **XGB outperforms others in F1 score:**  
   X Gradient Boosting has the **highest F1 score (64.0%)** among the three models, indicating that it has a better balance between precision and recall.  

   - **Gradient Boosting has slightly better Precision:**  
   Gradient Boosting has a **slightly higher precision (75.0%)** compared to Random Forest **(73.0%)** and X Gradient Boosting **(74.0%)**.  

   - **XGB has slightly better ROC AUC:**  
   X Gradient Boosting has a **slightly higher ROC AUC (75.0%)** compared to the other two models **(74.0%)**.  
   
   - **Recall is relatively low:**  
   The recall values for all three models are relatively low **(53.0% or 56.0%)**, indicating that they may be missing some true positives.

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

- ### Confusion Matrices
   - **All three models (Random Forest, Gradient Boosting, and X Gradient Boosting)** have **similar performance**, with a consistent **75% classification accuracy** for the exited class.

   - **Slight differences** exist in **false predictions** between the **Gradient Boosting and X Gradient Boosting** models, though these **differences are marginal**.

 ![10 1](https://github.com/user-attachments/assets/5e8eb47b-d4f5-4960-a0fc-971819c66062)


- ### ROC-AUC and Calibration Curves
   - **All three models (RFC, GBC, XGB)** have **comparable performance** in terms of distinguishing between classes, as indicated by similar AUC values.This suggests that **none of the models consistently outperforms the others** in terms of classification accuracy.
   
   - The **predicted probabilities** are **well-calibrated** for all models, meaning they accurately reflect the true likelihood of the positive class
   
 ![10 1](https://github.com/user-attachments/assets/6901a4bd-1ac2-4e90-b047-686e813e50ee)

- ### Feature Importance: 
    - With regards to feature importance the most consistently influencial feature was **Age and Number Of Products**  
    - Other notables features were;  
      - **Estimated Salary**  
      - **Active Membership**
   
![Image](https://github.com/user-attachments/assets/9506dfc1-3f45-4770-b3f1-169628f452bf)
  
