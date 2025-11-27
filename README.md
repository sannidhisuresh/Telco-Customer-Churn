**Telco-Customer-Churn**

![Python](https://img.shields.io/badge/Python-3.10-blue?logo=python) ![Jupyter Notebook](https://img.shields.io/badge/Jupyter-Notebook-orange?logo=jupyter) ![Scikit-learn](https://img.shields.io/badge/Scikit--learn-0.24-lightgrey?logo=scikit-learn) ![Status](https://img.shields.io/badge/Status-Completed-success)

This project analyzes customer churn for a telecom company and predicts which customers are likely to leave (churn). The goal is to identify key factors influencing churn and build a machine learning model for prediction.

**Overview**

This end-to-end project includes:

* Data Cleaning & Preprocessing
* Exploratory Data Analysis (EDA) with insights
* Machine Learning model building and evaluation

The objective is to predict whether a customer will churn or stay, helping the company improve customer retention.

**Dataset**

The dataset contains:

* Customer demographics
* Subscribed services
* Contract type
* Tenure
* Monthly & total charges
* Churn status

**Dataset file:** [Churn_Predicted.csv](https://github.com/sannidhisuresh/Telco-Customer-Churn/blob/main/Churn_Predicted.csv)

**Key Insights from EDA**

* Churn is higher among month-to-month contract customers.
* Customers with higher monthly charges are more likely to churn.
* Longer-tenured customers have lower churn rates.

**Visual Summary:**

**Churn Distribution**
![Churn Distribution](./images/churn_distribution.png)

**Contract vs Churn**
![Contract vs Churn](./images/contract_vs_churn.png)

**Machine Learning Model**

The project uses:

* Logistic Regression
* Random Forest Classifier

**Evaluation Metrics:**

* Train–Test Split
* Confusion Matrix
* Classification Report

The model predicts whether a customer will churn or stay with reasonable accuracy.

**Tools & Technologies**

* Python
* Pandas, NumPy
* Matplotlib, Seaborn
* Scikit-learn
* Jupyter Notebook

**Notebook:** [TelcoCustomerChurn_Analysis.ipynb](https://github.com/sannidhisuresh/Telco-Customer-Churn/blob/main/TelcoCustomerChurn_Analysis.ipynb)

**How to Run the Project**

* Clone the repository
git clone https://github.com/sannidhisuresh/Telco-Customer-Churn.git

* Navigate to project directory
cd Telco-Customer-Churn

* Install dependencies
pip install -r requirements.txt

* Open the notebook
jupyter notebook TelcoCustomerChurn_Analysis.ipynb

**Author**

**Sannidhi H S**

GitHub: [https://github.com/sannidhisuresh](https://github.com/sannidhisuresh)

LinkedIn: [https://www.linkedin.com/in/sannidhisuresh5106](https://www.linkedin.com/in/sannidhisuresh5106)
