# 📊 Customer Churn Analysis & Retention Insights

## 📌 Overview

Customer churn is one of the most critical challenges for businesses, directly impacting revenue, customer lifetime value, and growth.

This project focuses on analyzing customer behavior to:

* Identify **key drivers of churn**
* Segment customers based on **risk and value**
* Provide **actionable insights** to improve retention strategies

The project combines:

* **Python** for data cleaning, exploratory analysis, and feature engineering
* **Power BI** for building an interactive dashboard and communicating insights

## 🎯 Business Problem

Businesses often struggle to understand:

* Why customers leave
* Which customers are most at risk
* What actions can reduce churn

This project answers those questions by transforming raw customer data into **decision-ready insights**.


## 🧰 Tools & Technologies

* **Python** (Pandas, NumPy, Seaborn, Matplotlib)
* **Jupyter Notebook**
* **Power BI**
* **DAX (Data Analysis Expressions)**


## 📂 Dataset

The dataset contains customer-level information such as:

* Demographics (e.g., Gender)
* Transaction behavior (e.g., OrderCount, CashbackAmount)
* Engagement metrics (e.g., Tenure, DaysSinceLastOrder)
* Customer experience (e.g., Complaints)
* Target variable: **Churn (0 = Active, 1 = Churned)**

## 🧹 Data Cleaning & Preparation

* Handled missing values using:

  * Median (numerical features)
  * Mode (categorical features)
* Removed irrelevant columns (e.g., CustomerID)
* Ensured correct data types for analysis


## 🔍 Exploratory Data Analysis (EDA)

Key analyses performed:

* Churn distribution
* Comparison of churn vs non-churn customers
* Impact of behavioral and transactional variables
* Complaint analysis

## 💡 Key Insights

### 🔥 1. Tenure is the strongest driver of churn

Customers with low tenure are significantly more likely to churn.

### ⚠️ 2. Complaints increase churn risk dramatically

Customers who raise complaints are **~3x more likely to churn**.

### 💰 3. Customer value influences retention

Low-value customers exhibit higher churn behavior, while high-value customers are relatively more stable.


### 📉 4. Transaction frequency has limited impact

Order count shows minimal difference between churned and retained customers.


## 🧠 Feature Engineering

To enhance analysis and business relevance, the following features were created:

### 🔹 Risk Category

Customers were classified into:

* High Risk
* Medium Risk
* Low Risk

Based on tenure and complaint behavior.


### 🔹 Customer Value

Customers were segmented into:

* Low Value
* Medium Value
* High Value

Using cashback-based quantiles.


## 📊 Dashboard (Power BI)

An interactive dashboard was built to communicate insights effectively.

### Key Components:

* KPI Cards:

  * Total Customers
  * Churn Rate
  * Average Tenure
  * Average Cashback

* Visualizations:

  * Churn vs Tenure
  * Complaint Impact on Churn
  * Customer Value vs Churn Rate
  * Risk Category Distribution
  * Scatter Plot (Tenure vs Cashback by Risk)

* Filters:

  * Gender
  * Payment Method


## 🧾 Key Business Recommendations

Based on the analysis:

* 🎯 Focus retention efforts on **new customers (low tenure)**
* ⚠️ Improve **complaint resolution processes** to reduce churn
* 💰 Prioritize retention strategies for **high-value customers**
* 📈 Use risk segmentation to **proactively target at-risk customers**


## 🚀 Project Structure

```id="lquw2b"
├── data/
│   └── ecommerce_churn_final.csv
├── notebooks/
│   └── churn_analysis.ipynb
├── dashboard/
│   └── churn_dashboard.pbix
├── README.md


## 🤝 Contribution

Contributions, suggestions, and feedback are welcome.


## 📬 Contact

If you’d like to collaborate or discuss this project, feel free to connect.


# ⭐ Final Note

This project demonstrates how data can move beyond reporting to provide **actionable business insights** that support better decision-making and customer retention strategies.
