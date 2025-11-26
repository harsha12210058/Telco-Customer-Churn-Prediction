# Telco Customer Churn Prediction
This project analyzes telecom customer data and builds machine learning models to predict customer churn. The objective is to help telecom companies identify customers likely to discontinue services.

Project Overview:

Data cleaning and preprocessing

Exploratory data analysis (EDA)

Feature encoding and transformation

Training multiple machine learning models

Model evaluation and comparison

Exporting predictions for business use

Technologies Used:

Python

Pandas

NumPy

Matplotlib

Seaborn

Scikit-Learn

Data Preprocessing:

Handled missing values

Converted TotalCharges to numeric

Removed the customerID column

Encoded categorical variables using OrdinalEncoding

Encoded the churn column using LabelEncoding

Exploratory Data Analysis (EDA):

Visualized churn distribution

Analyzed tenure and monthly charges

Created a correlation heatmap

Explored categorical features with boxplots and countplots

Key Insights:

Short tenure customers churn more frequently

Higher monthly charges increase churn probability

Lack of security and tech support services is linked with churn

Machine Learning Models:

Logistic Regression

Decision Tree Classifier

Random Forest Classifier

Gradient Boosting Classifier

Model Accuracy:

Logistic Regression: 80.55%
Decision Tree: 73.31%
Random Forest: 79.34%
Gradient Boosting: 80.06%

Best Model: Logistic Regression (highest accuracy and good generalization)

Model Evaluation:

Confusion matrices

Classification reports

Accuracy comparison

Exported predictions to CSV

Key Takeaways:

Identified major factors driving customer churn

Built accurate predictive models

Demonstrated end-to-end data science workflow

Files Included:

notebook.ipynb – Full code
WA_Fn-UseC_-Telco-Customer-Churn – Real data

churn_predictions.csv – Model output

README.md – Documentation

