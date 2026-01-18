# 📉 Customer Churn Prediction (Machine Learning)

## 📌 Overview
This project focuses on predicting customer churn using supervised machine learning techniques. The objective is to identify customers who are likely to discontinue a service, enabling proactive retention strategies. The project demonstrates end-to-end data preprocessing, model training, evaluation, and comparison.

## 📂 Dataset
- **Source:** IBM Telco Customer Churn Dataset (Kaggle)
- **Target Variable:** Churn (Yes / No)
- **Key Features:** Tenure, MonthlyCharges, TotalCharges, Contract Type, Payment Method, Internet Services

## 🛠 Tech Stack
- Python  
- Pandas, NumPy  
- Matplotlib, Seaborn  
- Scikit-learn  

## 🔍 Methodology
- Data cleaning and preprocessing (missing values, encoding)
- Exploratory Data Analysis (EDA) to understand churn patterns
- Built a Logistic Regression model as a baseline
- Trained a Random Forest model for comparison
- Evaluated models using Accuracy, Precision, Recall, F1-score, and Confusion Matrix

## 📈 Results
- Logistic Regression achieved higher accuracy (~81%) and better generalization
- Random Forest produced comparable results but did not outperform the baseline
- Logistic Regression was selected as the final model due to performance and interpretability

## 🧠 Key Insights
- Customers with month-to-month contracts showed higher churn rates
- Short tenure and higher monthly charges increased churn probability
- Simpler models can outperform complex models depending on data patterns

## 🚀 Future Scope
- Improve churn recall using class balancing techniques
- Add ROC-AUC analysis
- Deploy the model as an interactive web application using Streamlit
- Experiment with advanced ensemble models

## 📁 Project StructCustomer-Churn-Prediction/
├── churn_analysis.ipynb
├── app.py
├── customer.csv
└── README.mdure


## 👤 Author
Adithiyha.R  
B.Tech – Data Science

