# Bank-Credit-Card-Default-Project


A machine learning project to predict whether a customer will default on their credit card payment. Built using Python with end-to-end workflow including data cleaning, EDA, model building, and performance evaluation.

## Performance Highlights

- **Accuracy:** 99.96%  
- **Precision:** 99.98%  
- **Recall:** 99.97%  
- **F1-Score:** 99.98%  

## Features

- **Data Preprocessing:**  
  - Cleaned missing and inconsistent values  
  - Applied feature engineering and encoding for categorical variables  

- **Exploratory Data Analysis (EDA):**  
  - Visualized trends, correlations, and class imbalances using `seaborn` and `matplotlib`  
  - Insights into feature importance and target class behavior  

- **Modeling:**  
  - Compared multiple ML algorithms:
    - Logistic Regression  
    - Decision Tree  
    - Random Forest  
    - Support Vector Machines (SVM)  
  - Built reusable **ML pipelines** for automated preprocessing and modeling  
  - Addressed **class imbalance** using techniques like **SMOTE**

- **Evaluation:**  
  - Generated confusion matrix, ROC curves, and classification reports  
  - Focused on precision and recall due to real-world cost of misclassification  

- **Result:**  
  - The best model is Logistic regression without SMOTE(99.96% Accuracy)
