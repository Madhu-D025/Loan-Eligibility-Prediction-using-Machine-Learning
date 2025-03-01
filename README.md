# Loan-Eligibility-Prediction-using-Machine-Learning
The Loan Eligibility Prediction project uses machine learning to classify applicants as eligible or not based on financial and demographic data, automating loan approvals for banks and improving decision-making efficiency.
## Objectives
-- Develop a predictive model to classify applicants as eligible or not for a loan.
-- Perform data preprocessing by handling missing values, encoding categorical variables, and scaling numerical features.
-- Conduct exploratory data analysis (EDA) to identify key trends and correlations affecting loan approval.
-- Apply feature engineering techniques to improve model accuracy and performance.
-- Train multiple machine learning models (Logistic Regression, Random Forest, XGBoost, etc.) and compare their performance.
-- Evaluate models using performance metrics such as accuracy, precision, recall, F1-score, and ROC-AUC.
-- Optimize the best-performing model through hyperparameter tuning to enhance prediction accuracy.
## Dataset used
- <a href="https://github.com/Madhu-D025/Loan-Eligibility-Prediction-using-Machine-Learning/blob/main/loan_approval_dataset.csv">Dataset</a>
## Dataset Description
-- Applicant Income – The income of the primary loan applicant, which impacts repayment capability.
-- Coapplicant Income – The income of a co-applicant (if any), which can boost loan approval chances.
-- Loan Amount – The total loan amount requested by the applicant.
-- Loan Term – The duration (in months) for which the loan is sanctioned.
-- Credit History – A binary indicator (1 or 0) representing whether the applicant has a history of timely repayments.
-- Property Area – The location category (Urban, Semi-Urban, or Rural) of the applicant’s property.
-- Marital Status – Indicates whether the applicant is married, which may influence eligibility.
-- Education Level – Specifies whether the applicant is a graduate or not.
-- Self-Employed Status – Identifies if the applicant is self-employed or working for a company.
-- Dependents – The number of dependents financially supported by the applicant, affecting loan repayment ability.
-- Loan Status – The target variable (Yes/No), indicating whether the loan was approved
## Exploratory Data Analysis (EDA)
-- Handling missing values using imputation techniques.
-- Visualizing correlations between features and loan eligibility.
-- Detecting outliers using box plots.
-- Feature engineering for better model performance.
## Machine Learning Models Used
-- Logistic Regression
-- Decision Tree
-- K-Nearest Neighbors
-- Naive Bayes
-- SVM
## Model Evaluation Metrics
-- Accuracy Score
-- Precision, Recall, and F1-score
-- Confusion Matrix
## Conclusion
The Decision Tree model achieved the highest accuracy, making it the best-performing model for loan eligibility prediction. Other models like SVM, Naïve Bayes, and Logistic Regression performed well but with slightly lower accuracy. The K-Nearest Neighbors model had a noticeable drop in testing accuracy, indicating potential overfitting. Overall, Decision Tree is the most reliable model for this dataset. 🚀
