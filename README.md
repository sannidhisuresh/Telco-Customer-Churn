Telco-Customer-Churn

This project analyzes customer churn for a telecom company and predicts which customers are likely to leave (churn). The goal is to identify key factors influencing churn and build a machine learning model for prediction.

Overview

Customer churn is a major challenge in the telecom industry. This project performs end-to-end analysis including:

Data cleaning and preprocessing

Exploratory Data Analysis (EDA)

Visualization of important trends

Machine learning model for churn prediction

Model evaluation and insights

Dataset

The dataset contains information such as:

Demographics

Services subscribed

Contract type

Tenure

Monthly/Total charges

Payment method

Churn status

Dataset file: Churn_Predicted.csv

Project Workflow
1. Data Cleaning & Preprocessing

Handled missing values

Encoded categorical columns

Scaled numerical features

Identified correlations

2. Exploratory Data Analysis (EDA)

Churn percentage

Contract type vs churn

Tenure behavior

Monthly charges analysis

Service usage patterns

Visualizations
Churn Count

Churn Distribution

Contract vs Churn

Tenure vs Churn

Predicted Churn (Model Output)

Machine Learning Model

A churn prediction model was built using:

Logistic Regression

Random Forest Classifier

Train–test split

Classification report

Confusion matrix

The model outputs a predicted churn label for each customer.

Tools & Technologies

Python

Pandas, NumPy

Matplotlib, Seaborn

Scikit-learn

Jupyter Notebook

Notebook

Full analysis and model code is available in the notebook:

TelcoCustomerChurn_Analysis.ipynb

How to Run
1. Clone the repository
git clone https://github.com/sannidhisuresh/Telco-Customer-Churn.git

2. Navigate to the project directory
cd Telco-Customer-Churn

3. Install dependencies
pip install -r requirements.txt

4. Run the notebook
jupyter notebook TelcoCustomerChurn_Analysis.ipynb

Author

Sannidhi H S
GitHub: https://github.com/sannidhisuresh

LinkedIn: https://www.linkedin.com/in/sannidhisuresh5106
