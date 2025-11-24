📊 Telco Customer Churn Analysis

Predicting customer churn using Exploratory Data Analysis, Feature Engineering, and Machine Learning

🚀 Project Overview

This project analyzes telecommunication customer churn to understand why customers leave and how the company can reduce churn.
Using Python, the project includes data cleaning, EDA, feature engineering, model training, and insights.

The goal is to identify key drivers of churn and build a model that can help the business take proactive action.

🔧 Tools & Technologies

Python

Pandas, NumPy

Matplotlib, Seaborn

Scikit-learn

Jupyter Notebook

Power BI (optional for visualization)

🧹 Data Cleaning & Preprocessing

The following steps were applied to clean the dataset:

✔ Handling missing values
✔ Converting categorical features
✔ Standardizing numerical features
✔ Dropping irrelevant columns
✔ Creating new meaningful variables
✔ Encoding target label (Churn)

📈 Exploratory Data Analysis (EDA)

Key questions answered:

Which types of customers churn the most?

How does contract type affect churn?

Does monthly charges influence churn?

Do tenure, services, and payment methods matter?

The EDA includes:

📌 Correlation heatmap
📌 Churn distribution
📌 Tenure analysis
📌 Service usage patterns
📌 Revenue patterns by churn label

🤖 Machine Learning Models

Multiple models were tested:

Logistic Regression

Random Forest

XGBoost

Decision Tree

KNN

After tuning, the best model achieved:

⭐ Best Accuracy:

(Add your final accuracy here)

⭐ Most Important Features:

MonthlyCharges

Tenure

Contract type

Internet service

Payment method

📌 Key Business Insights

📍 Customers with month-to-month contracts churn far more.
📍 Customers using electronic check are more likely to churn.
📍 Higher MonthlyCharges increase churn probability.
📍 Longer-tenure customers stay loyal.
📍 Fiber optic users churn more than DSL users.

📑 Future Improvements

Add hyperparameter tuning with GridSearchCV

Build a Power BI interactive churn dashboard

Deploy model with Streamlit

Add automated pipelines
