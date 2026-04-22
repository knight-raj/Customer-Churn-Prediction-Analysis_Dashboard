# 📊 Customer Churn Prediction & Analysis Dashboard

## 🧠 Project Overview

Customer churn is a critical problem in industries like Telecom, SaaS, and Banking, where losing customers directly impacts revenue.

This project aims to:

* **Predict customer churn** using Machine Learning
* **Identify key factors** driving churn
* **Provide actionable insights** through an interactive Power BI dashboard

---

## 🎯 Objective

The main objectives of this project are:

* Predict which customers are likely to churn
* Understand **why customers churn**
* Help businesses take **proactive retention actions**
* Build an end-to-end **data analytics + machine learning pipeline**

---

## 📁 Dataset

* Dataset: **IBM Telco Customer Churn**
* Records: ~7000 customers
* Features include:

  * Customer demographics
  * Service details
  * Billing information
  * Contract type
  * Churn status (Target variable)

---

## 🛠️ Tools & Technologies

* **Python** → Data Cleaning, EDA, Machine Learning
* **Pandas, NumPy** → Data manipulation
* **Seaborn, Matplotlib** → Data visualization
* **Scikit-learn** → Model building
* **Power BI** → Dashboard & business insights

---

# 🔄 Project Workflow

## 1️⃣ Data Cleaning (Python)

### ✔ Key Steps:

* Converted `TotalCharges` from string to numeric
* Handled missing values using `dropna()`
* Verified data types using `df.info()`

### 💡 Why?

Clean data ensures:

* Accurate analysis
* Better model performance

---

## 2️⃣ Exploratory Data Analysis (EDA)

### 📊 Visualizations:

* Churn Distribution
* Churn vs Contract
* Churn vs Monthly Charges
* Churn vs Tenure
* Churn vs Internet Service

### 🔍 Key Insights:

* Customers with **month-to-month contracts** churn more
* **High monthly charges** increase churn probability
* Customers with **low tenure** are more likely to leave
* Fiber optic users show higher churn

### 💡 Why?

EDA helps understand:

* Patterns in data
* Relationships between variables
* Business behavior of customers

---

## 3️⃣ Data Preprocessing

### ✔ Steps:

* Converted `Churn` (Yes/No → 1/0)
* Applied **One-Hot Encoding** using `pd.get_dummies()`
* Split data into **features (X) and target (y)**
* Performed **train-test split (80/20)**

### 💡 Why?

Machine Learning models require:

* Numerical input
* Proper training & testing separation

---

## 4️⃣ Model Building

### 🤖 Models Used:

* Logistic Regression
* Random Forest Classifier

---

## 📊 Model Evaluation

### Logistic Regression:

* Accuracy: ~79%
* Recall (Churn): ~52%

### Random Forest:

* Similar accuracy
* Slightly lower recall for churn

### ✅ Final Decision:

* Logistic Regression selected due to **better churn detection (recall)**

### 💡 Why Recall Matters?

In churn problems:

> Missing a churn customer = Revenue loss

---

## 🔍 Feature Importance

Top factors influencing churn:

* **Total Charges**
* **Monthly Charges**
* **Tenure**
* Contract type
* Internet service

### 💡 Insight:

Customers with:

* High charges
* Short tenure
* Flexible contracts

👉 Are more likely to churn

---

# 📊 Power BI Dashboard

## 🎯 Purpose

To present insights in a **business-friendly and interactive format**

---

## 📌 Key Metrics (KPIs)

* Total Customers
* Churn Customers
* Churn Rate (%)
* Average Monthly Charges

---

## 📊 Visualizations

* Churn by Contract
* Churn by Internet Service
* Churn by Monthly Charges
* Churn by Tenure

---

## 🎛️ Interactive Features

* Filters (Slicers):

  * Contract
  * Gender
  * Internet Service

---

## 💡 Business Insights

* Month-to-month customers have highest churn
* High-paying customers are more likely to leave
* New customers are at higher risk
* Service-related issues impact churn

---

# 🧠 Business Impact

This project helps companies:

* Identify high-risk customers
* Improve customer retention strategies
* Reduce revenue loss
* Make data-driven decisions

---

# 🚀 Conclusion

This project demonstrates:

✔ End-to-end Data Analytics workflow
✔ Machine Learning model building
✔ Business problem solving
✔ Dashboard storytelling

---

# 📌 Future Improvements

* Hyperparameter tuning
* Use advanced models (XGBoost)
* Deploy model using Flask/Streamlit
* Real-time dashboard integration

---

# 👤 Author

**Ankit Raj**
Aspiring Data Analyst

---

# ⭐ If you like this project

Give it a ⭐ on GitHub and connect with me!
