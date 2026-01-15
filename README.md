# 👥 Customer Churn Prediction – Data Preprocessing & Feature Engineering

## 📌 Project Overview
This project focuses on **data preprocessing and feature engineering** for a customer churn prediction problem.  
The objective is to transform raw customer data into a **machine-learning-ready dataset** by applying industry-standard preprocessing techniques and creating meaningful engineered features.

This project is part of **Week 10: Data Preprocessing & Feature Engineering** and is suitable for **academic submission, internships, and portfolio showcase**.

---

## 🎯 Project Objectives
- Understand and preprocess customer churn data
- Convert categorical variables into numerical format
- Scale numerical features using different techniques
- Detect and handle outliers
- Engineer new features with business relevance
- Select important features for modeling
- Build a complete preprocessing pipeline

---

## 📂 Dataset
**File:** `customer_churn.csv`  
**Rows:** 500  
**Target Variable:** `Churn`

### Key Columns
- Customer demographics
- Contract and billing information
- Monthly charges and tenure

---

## 🛠️ Tools & Technologies
- Python
- Google Colab
- Pandas & NumPy
- Matplotlib & Seaborn
- Scikit-learn

---

## 📁 Project Structure
customer-churn-preprocessing/
│
├── churn_prediction_pipeline.ipynb
├── customer_churn.csv
├── preprocessing_report.pdf
├── feature_engineering_documentation.pdf
├── requirements.txt
└── README.md


---

## 🔍 Preprocessing Steps Performed

### 1️⃣ Data Cleaning
- Checked for missing values
- Removed inconsistent records
- Validated data types

### 2️⃣ Handling Categorical Data (3 Methods)
- **Label Encoding** – binary categories
- **One-Hot Encoding** – nominal categories
- **Binary Encoding** – target variable (Churn)

### 3️⃣ Feature Scaling (2 Techniques)
- **Min-Max Scaling**
- **Standard Scaling**

### 4️⃣ Outlier Detection
- **Interquartile Range (IQR) method**
- **Z-score method**

---

## 🧠 Feature Engineering (5+ Features)
- Customer Lifetime Value (CLV)
- Average Monthly Spend
- High-Value Customer Indicator
- Long-Term Customer Flag
- Payment Efficiency

Each feature was created with **business context and predictive relevance**.

---

## 🎯 Feature Selection
- Correlation analysis
- Statistical feature selection (ANOVA F-test)
- Selection of most impactful features for churn prediction

---

## 🔄 Preprocessing Pipeline
A complete preprocessing pipeline was built using:
- `ColumnTransformer`
- `Pipeline`

This ensures:
- Reproducibility
- No data leakage
- Easy integration with machine learning models

---

## 📄 Documentation
- **preprocessing_report.pdf** – Detailed explanation of all preprocessing steps
- **feature_engineering_documentation.pdf** – In-depth explanation of engineered features and business impact

---

## ▶️ How to Run the Project
1. Clone the repository
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
