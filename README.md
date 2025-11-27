# 📊 Telco-Customer-Churn

This project analyzes customer churn for a telecom company and predicts which customers are likely to leave (churn).  
The goal is to identify key factors influencing churn and build a machine learning model for prediction.

---

## 📁 Dataset
The dataset contains information about:
- Customer demographics  
- Subscription details  
- Contract type & tenure  
- Monthly & total charges  
- Churn status  

**Main file:** `Churn_Predicted.csv`

---

## 🚀 Project Workflow

### **1️⃣ Data Cleaning & Preprocessing**
- Handling missing values  
- Encoding categorical variables  
- Scaling numerical features  

### **2️⃣ Exploratory Data Analysis (EDA)**
- Distribution of churn  
- Relationship between churn & contract  
- Tenure impact  
- Service subscription patterns  

### **3️⃣ Visualization**
Below are some key visualizations used in the analysis:

#### 📌 Churn Count  
![Churn Count](churn_count.png)

#### 📌 Churn Distribution  
![Churn Distribution](churn_distribution.png)

#### 📌 Contract vs Churn  
![Contract vs Churn](contract_vs_churn.png)

#### 📌 Tenure vs Churn  
![Tenure vs Churn](tenure_vs_churn.png)

#### 📌 Predicted Churn (Model Output)  
![Predicted Churn](predicted_churn.png)

---

## 🤖 Machine Learning  
A churn prediction model was built using:
- Logistic Regression / Random Forest (based on your notebook)
- Train–test split  
- Evaluation metrics (Accuracy, Confusion Matrix)

---

## 🛠️ Tools & Technologies
- Python  
- Pandas, NumPy  
- Matplotlib, Seaborn  
- Scikit-learn  
- Jupyter Notebook  

---

## 📘 Notebook
👉 **Click here to view full analysis:**  
[`TelcoCustomerChurn_Analysis.ipynb`](TelcoCustomerChurn_Analysis.ipynb)

---

## 📂 Project Structure

```
Telco-Customer-Churn/
│
├── Churn_Predicted.csv
├── TelcoCustomerChurn_Analysis.ipynb
├── README.md
│
└── images/
    ├── churn_count.png
    ├── churn_distribution.png
    ├── contract_vs_churn.png
    ├── predicted_churn.png
    └── tenure_vs_churn.png
```

---

## ▶️ How to Use / Run This Project

1. Clone the repository:
   ```
   git clone https://github.com/yourusername/your-repo-name.git
   cd your-repo-name
   ```

2. Install required dependencies:
   ```
   pip install -r requirements.txt
   ```

3. Open the notebook:
   ```
   jupyter notebook TelcoCustomerChurn_Analysis.ipynb
   ```

4. Run all cells to:
   - Clean data  
   - View visualizations  
   - Train prediction model  

---

## 🎯 Summary
This project provides a full churn analysis pipeline from data cleaning → EDA → visualization → model building → predictions.  
Helps telecom companies understand churn patterns and take proactive actions.

---

 

Just tell me!
