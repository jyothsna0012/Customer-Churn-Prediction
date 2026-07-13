INTERN ID :CITS6379

# 📊 Customer Churn Prediction using SQL, Python & Machine Learning

## 📌 Project Overview

Customer churn prediction is an important business analytics problem where companies identify customers who are likely to stop using their products or services.

This project analyzes telecom customer data to understand churn patterns, perform business analysis, build a machine learning model, and create a dashboard-style visualization to identify customers at risk of leaving.

The project follows an end-to-end analytics workflow:

**Data Cleaning → SQL Analysis → Exploratory Data Analysis → Machine Learning → Dashboard Visualization → Business Insights**

DATASET LINK:https://www.kaggle.com/datasets/blastchar/telco-customer-churn?utm_source=chatgpt.com

---

# 🎯 Project Objectives

* Analyze customer behavior and identify churn patterns.
* Clean and preprocess customer data.
* Perform business analysis using SQL queries.
* Explore customer trends using Python visualization.
* Build a machine learning model to predict churn.
* Evaluate model performance.
* Create a dashboard to present important KPIs and insights.
* Provide recommendations to improve customer retention.

---

# 🛠️ Tools & Technologies Used

## Programming Languages

* Python
* SQL

## Tools

* MySQL Workbench
* Google Colab
* GitHub

## Python Libraries

* Pandas → Data cleaning and manipulation
* NumPy → Numerical operations
* Matplotlib → Data visualization
* Scikit-learn → Machine learning

---

# 📂 Dataset Information

Dataset:

**Telco Customer Churn Dataset**

Source:

Kaggle

Dataset Details:

* Original Records: 7043 customers
* Cleaned Records: 7032 customers
* Features: 21 columns

Target Variable:

`Churn`

Values:

* Yes → Customer left the company
* No → Customer stayed

---

# 📋 Features Used

## Customer Information

* customerID
* gender
* SeniorCitizen
* Partner
* Dependents

## Service Information

* PhoneService
* MultipleLines
* InternetService
* OnlineSecurity
* OnlineBackup
* DeviceProtection
* TechSupport
* StreamingTV
* StreamingMovies

## Account Information

* Contract
* PaperlessBilling
* PaymentMethod
* MonthlyCharges
* TotalCharges

## Target

* Churn

---

# 🔄 Project Workflow

## 1. Data Cleaning

Performed:

* Loaded raw dataset
* Checked missing values
* Removed incomplete records
* Converted TotalCharges into numerical format
* Checked duplicate records
* Prepared clean dataset for analysis

---

# 2. SQL Analysis (MySQL)

Created database:

```
churn_db
```

Created table:

```
customer_churn
```

Performed analysis:

* Total customer count
* Churn customer count
* Churn rate calculation
* Customer segmentation
* Churn by contract type
* Churn by payment method
* Churn by internet service
* Churn by senior citizen category
* Churn by technical support
* Churn by online security
* Average tenure analysis
* Revenue analysis

---

# 3. Exploratory Data Analysis (EDA)

Performed using Python.

Analysis included:

* Dataset overview
* Missing value analysis
* Duplicate checking
* Statistical summary
* Churn distribution
* Gender analysis
* Contract analysis
* Internet service analysis
* Payment method analysis
* Monthly charges analysis
* Customer tenure analysis

---

# 4. Machine Learning Model

## Problem Type

Binary Classification

The model predicts:

```
Churn = Yes / No
```

---

## Data Preprocessing

Steps:

* Removed customerID
* Converted categorical features into numerical values using Label Encoding
* Split data into training and testing datasets

Training Data:

80%

Testing Data:

20%

---

## Algorithm Used

### Logistic Regression

Reasons:

* Suitable for binary classification
* Easy to interpret
* Provides probability-based predictions

---

# 📈 Model Evaluation

The model was evaluated using:

## Accuracy Score

Measures overall correct predictions.

## Confusion Matrix

Evaluates:

* True Positive
* True Negative
* False Positive
* False Negative

## Classification Report

Includes:

* Precision
* Recall
* F1-score

---

# 📊 Dashboard Visualization

A dashboard-style visualization was created using Python.

Dashboard contains:

## KPI Metrics

* Total Customers
* Churn Customers
* Churn Rate
* Total Revenue

## Charts

* Customer Churn Distribution
* Churn by Contract Type
* Churn by Internet Service
* Monthly Charges Analysis
* Customer Tenure Analysis

---

# 🔍 Key Insights

* Month-to-month contract customers have higher churn probability.
* Customers with shorter tenure are more likely to leave.
* Customers without additional services like Tech Support have higher churn.
* Higher monthly charges influence customer retention.
* Long-term customers contribute more revenue.

---

# 💡 Business Recommendations

* Encourage customers to choose long-term contracts.
* Provide loyalty offers for existing customers.
* Improve customer support services.
* Target high-risk customers with retention campaigns.
* Use predictive analytics to identify potential churn customers.

---

# 📁 Project Structure

```
Customer-Churn-Prediction/

│
├── Dataset/
│   └── Cleaned_Telco_Customer_Churn.csv
│
├── SQL/
│   └── churn_analysis.sql
│
├── Notebook/
│   └── Customer_Churn_Prediction.ipynb
│
├── Dashboard/
│   └── churn_dashboard.png
│
├── README.md
```

---

# 🚀 Project Outcomes

Successfully completed:

✅ Data Cleaning
✅ SQL Business Analysis
✅ Exploratory Data Analysis
✅ Machine Learning Classification Model
✅ Model Evaluation
✅ Customer Churn Prediction
✅ Dashboard Visualization
✅ Business Recommendations

---

# 📌 Future Improvements

* Try advanced ML models:

  * Random Forest
  * XGBoost
  * Gradient Boosting

* Deploy the model using:

  * Streamlit
  * Flask API

* Add real-time churn prediction system.

---

# 👩‍💻 Author

**Jyothsna Sree**

Data Analytics | Python | SQL | Machine Learning

---

⭐ If you found this project useful, feel free to star this repository!
