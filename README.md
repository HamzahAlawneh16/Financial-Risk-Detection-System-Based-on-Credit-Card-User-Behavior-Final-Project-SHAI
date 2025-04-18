# Final-Project-SHAI

# Project Summary
In today's rapidly evolving financial environment, credit cards are an essential tool for many individuals. However, with their widespread use comes the significant challenge of credit risk. One of the major concerns for banks is determining which customers are likely to default on their payments, as this affects financial stability and risk management strategies.

This project explores how machine learning techniques can be applied to predict default risk among credit card users. The dataset used originates from Taiwan and includes real data on 30,000 clients collected between April and September 2005. It contains detailed information on users’ demographics, payment history, bill statements, and previous payments.

The goal of the project is to build a predictive model that helps banks identify customers who are likely to default on their payments the following month. The project also seeks to uncover the most influential features in predicting default risk, thereby providing valuable business insights for better decision-making.


# Tools & Technologies Used
Programming Language: Python (via Google Colab / Jupyter Notebook)

Data Manipulation & Analysis: Pandas, NumPy

Data Visualization: Seaborn, Matplotlib, Plotly

Machine Learning Algorithms:

Logistic Regression

Decision Trees

Random Forest Classifier

XGBoost Classifier

ML Libraries: Scikit-learn, XGBoost



# Problem Statement
 The primary aim of this project is to develop an accurate model to predict whether a customer will default on their credit card payment next month. From a risk management standpoint, predicting the likelihood of default is more valuable than simply labeling a customer as "good" or "bad." The banking sector needs efficient tools that can analyze large datasets and provide quick, reliable predictions to support strategic decision-making.



# Dataset Overview
The dataset used is publicly available on Kaggle under the title:

[kaggle dataset ](https://https://www.kaggle.com/uciml/default-of-credit-card-clients-dataset)




# Dataset Details:
Observations (Rows): 30,000

Features (Columns): 25

Target Variable: default.payment.next.month (1 = Default, 0 = No Default)

#  Features include:
Demographics: ID, Age, Gender, Marital Status, Education

Credit Info: Credit Limit, Payment History (last 6 months), Amount of Bill Statements, and Past Payments

Payment Behavior: PAY_0 to PAY_6 (Status for each month), BILL_AMT1 to BILL_AMT6, PAY_AMT1 to PAY_AMT6

 The dataset is clean, with no missing values.

#**ProjectWorkflow**
1.Data Wrangling & Cleaning:



Ensuring the dataset is ready for modeling by encoding categorical variables, scaling numerical features, and correcting data types.

2.Exploratory Data Analysis (EDA):

* Univariate Analysis: Understanding distributions of single variables.

* Bivariate & Multivariate Analysis: Exploring relationships between features and the target variable.

* At least 15 visualizations will be created using Seaborn, Matplotlib, and Plotly, with proper business insights explained for each.

3.Model Building:
* Applying different machine learning algorithms including Logistic Regression, Random Forest, Decision Tree, and XGBoost.

4.Model Evaluation:
* Using Confusion Matrix, Precision, Recall, F1 Score, ROC-AUC Curve, and Cross-Validation to compare model performance.

5.Hyperparameter Tuning:
* Applying GridSearchCV or RandomizedSearchCV to improve the performance of the models.

6.Final Business Insights:

* Key features influencing default prediction

* Business impact of accurate classification

* Risk-reduction strategies based on model predictions





# **Expected Outcome**
By the end of this project, a well-performing predictive model will be available that helps financial institutions to:

* Identify high-risk customers before approving credit.

* Reduce losses from non-performing loans.

* Improve profitability and risk management policies.

This project not only enhances understanding of data science applications in finance, but also strengthens hands-on experience with machine learning, EDA, and model evaluation.

