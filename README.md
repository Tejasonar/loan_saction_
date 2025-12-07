# Loan Approval Prediction Project

This project predicts whether a loan application should be approved based on applicant financial and personal data. 
It includes Exploratory Data Analysis (EDA), data preprocessing, multiple Machine Learning models, and model evaluation.

---

Objectives

* Understand patterns in loan approvals.
* Identify factors that influence loan decisions.
* Build ML models to automate loan approval prediction.
* Compare model performance and choose the best one.

---

Dataset Description

The dataset includes features such as:

* Applicant Income
* Co-applicant Income
* Loan Amount
* Loan Term
* Credit History
* Property Area
* Education
* Marital Status
* Employment details
* Loan Status (Target Variable)

---

 Steps Performed

 Data Cleaning

* Checked dataset structure and shape.
* Removed or imputed missing values.
* Handled outliers.
* Encoded categorical variables.
* Scaled numerical features.

 Exploratory Data Analysis (EDA)

* Visualized loan approval distribution.
* Studied the effect of income, loan amount, and credit history.
* Identified strong relationships:
  * Applicants with **credit history = 1** have much higher approval chances.
  * Loan amount has moderate impact.
  * Income alone is not a strong predictor.
 
    
---

 Model Building

Implemented ML models:

* Logistic Regression
* Decision Tree
* Random Forest
* KNN
* SVM

---

Model Evaluation

Evaluated using:

* Accuracy Score
* Confusion Matrix
* Precision
* Recall
* F1 Score

 ---
 
Best Model

Random Forest Classifier
Chosen because:

* High accuracy
* Works well with mixed-type data
* Handles outliers and non-linear patterns
* Less overfitting than a single Decision Tree
  
---

Tech Stack

* Python
* Pandas
* NumPy
* Matplotlib / Seaborn
* Scikit-Learn
* Jupyter Notebook

---

 Future Improvements

* Hyperparameter tuning with GridSearchCV.
* Add missing value imputation using ML algorithms.
* Deploy model using Streamlit or Flask.
* Add explainability using SHAP or LIME.


