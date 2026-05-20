# Customer Churn Analysis & Prediction

## Project Overview

Customer churn is one of the biggest challenges for subscription-based businesses such as telecom, banking, insurance, and SaaS companies. This project focuses on analyzing customer behavior, identifying churn patterns, and building a machine learning model to predict customers who are likely to leave.

The project combines:

* Data Analysis using Python
* Machine Learning for churn prediction
* Interactive Power BI Dashboard for visualization
* Business insights and recommendations

---

# Objectives

* Analyze customer behavior and churn trends
* Identify key factors influencing customer churn
* Build a predictive machine learning model
* Generate business insights for customer retention
* Create an interactive dashboard for decision-making

---

# Tech Stack

## Programming & Analysis

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn

## Visualization

* Power BI

## Development Environment

* Jupyter Notebook
* VS Code

---

# Dataset Information

The dataset contains customer-related information such as:

* Customer demographics
* Subscription details
* Payment behavior
* Support interactions
* Contract information
* Churn status

### Key Features

| Feature         | Description                       |
| --------------- | --------------------------------- |
| Age             | Customer age                      |
| Gender          | Male/Female                       |
| Tenure          | Duration of customer relationship |
| Monthly Charges | Monthly subscription cost         |
| Contract Type   | Monthly/Yearly subscription       |
| Support Calls   | Number of support interactions    |
| Payment Delay   | Delay in bill payment             |
| Churn           | Whether customer left or stayed   |

---

# Project Workflow

## 1. Data Cleaning

* Removed missing values
* Handled duplicate records
* Checked data types
* Prepared data for analysis

## 2. Exploratory Data Analysis (EDA)

Performed detailed analysis to understand:

* Customer churn distribution
* Relationship between churn and tenure
* Impact of contract type on churn
* Payment behavior patterns
* Customer support trends

### Visualizations Used

* Bar Charts
* Count Plots
* Heatmaps
* Pie Charts
* Correlation Analysis

---

# Machine Learning Model

## Model Used

* Logistic Regression

## Steps Performed

* Feature selection
* Train-test split
* Model training
* Prediction
* Performance evaluation

## Evaluation Metrics

* Accuracy
* Precision
* Recall
* F1-Score
* ROC-AUC Score

---

# Power BI Dashboard

The Power BI dashboard provides an interactive overview of:

* Total Customers
* Churn Rate
* Customer Segmentation
* Monthly Charges Analysis
* Churn by Contract Type
* Payment Delay Trends
* Customer Support Analysis

### Dashboard Features

* KPI Cards
* Interactive Filters
* Dynamic Charts
* Business Insights

---

# Key Insights

* Customers with month-to-month contracts are more likely to churn.
* Higher payment delays increase churn probability.
* Customers with frequent support calls show higher churn rates.
* Long-term customers are less likely to leave.
* Monthly charges significantly influence customer retention.

---

# Business Recommendations

* Offer discounts for long-term contracts.
* Improve customer support quality.
* Create retention campaigns for high-risk customers.
* Monitor customers with repeated payment delays.
* Introduce loyalty programs for long-term users.

---

# Project Structure

```bash
customer-churn-analysis/
│
├── Customer_Churn_Analysis.ipynb
├── Customer_Churn_Analysis.pbix
├── customer_churn_dataset_training_master.csv
├── images/
│   └── dashboard.png
├── README.md
└── requirements.txt
```

---

# Installation & Setup

## Clone Repository

```bash
git clone https://github.com/Shreya883986/customer-churn-analysis.git
```

## Navigate to Project Folder

```bash
cd customer-churn-analysis
```

## Install Required Libraries

```bash
pip install -r requirements.txt
```

---

# Requirements

Create a `requirements.txt` file with:

```txt
pandas
numpy
matplotlib
seaborn
scikit-learn
jupyter
```

---

# How to Run the Project

## Run Jupyter Notebook

```bash
jupyter notebook
```

Open:

```bash
Customer_Churn_Analysis.ipynb
```

## Open Power BI Dashboard

Open:

```bash
Customer_Churn_Analysis.pbix
```

using Power BI Desktop.

---

# Future Improvements

* Add multiple machine learning models
* Deploy model using Streamlit
* Add SHAP feature importance analysis
* Integrate SQL database
* Build real-time prediction system

---

# Learning Outcomes

Through this project, I learned:

* Data preprocessing techniques
* Exploratory Data Analysis
* Machine learning workflow
* Dashboard creation using Power BI
* Business problem solving using data

---

# Screenshots

## Power BI Dashboard



---

# Author

## Shreya

Aspiring Data Analyst 

GitHub: [https://github.com/Shreya883986](https://github.com/Shreya883986)

---

# Conclusion

This project demonstrates how data analysis and machine learning can help businesses reduce customer churn and improve retention strategies. By combining Python analytics, predictive modeling, and Power BI dashboards, the project provides both technical implementation and business-driven insights.
