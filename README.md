# 📊 Telecom Customer Churn Analysis & Prediction

> An end-to-end Data Analytics and Machine Learning project that analyzes customer churn patterns and predicts customer attrition using the IBM Telco Customer Churn dataset.

---

## 📖 Project Overview

Customer churn is one of the biggest challenges faced by subscription-based businesses, especially in the telecommunications industry. Losing existing customers directly impacts revenue and increases customer acquisition costs.

This project explores customer behavior using the **IBM Telco Customer Churn Dataset** and develops predictive machine learning models to identify customers who are likely to leave the service.

The project follows a complete analytics workflow, including:

- Data Understanding
- Data Cleaning & Preprocessing
- Feature Engineering
- Exploratory Data Analysis (EDA)
- Machine Learning
- Model Evaluation
- Business Recommendations

---

## 🎯 Project Objectives

- Understand customer demographics, services, and billing behavior.
- Identify the major factors influencing customer churn.
- Build predictive models to classify customers as likely to churn or not.
- Compare multiple machine learning algorithms.
- Generate actionable business recommendations to improve customer retention.

---

## 📂 Dataset Information

| Attribute | Value |
|-----------|-------|
| Dataset | IBM Telco Customer Churn |
| Records | 7,043 Customers |
| Features | 21 Original Features |
| Engineered Features | 5 |
| Target Variable | Churn (Yes / No) |

---

## 🛠️ Technologies Used

- Python
- Google Colab
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- Git & GitHub

---

## 🔄 Project Workflow

```text
Raw Dataset
      │
      ▼
Data Understanding
      │
      ▼
Data Cleaning
      │
      ▼
Feature Engineering
      │
      ▼
Exploratory Data Analysis
      │
      ▼
Business Insights
      │
      ▼
Data Preprocessing
      │
      ▼
Machine Learning
      │
      ▼
Model Evaluation
      │
      ▼
Business Recommendations
```

---

## 🧹 Data Cleaning

The dataset was cleaned by:

- Handling missing values
- Converting incorrect data types
- Removing inconsistencies
- Verifying duplicate records
- Preparing data for analysis

---

## ⚙️ Feature Engineering

Created meaningful business features including:

- Tenure Category
- Monthly Charge Category
- Total Charge Category
- Family Status
- Senior Citizen Label

These engineered features improve interpretability during exploratory analysis.

---

## 📊 Exploratory Data Analysis

The following business questions were explored:

- What is the overall churn distribution?
- Does gender influence customer churn?
- Do senior citizens churn more frequently?
- Which contract type has the highest churn?
- How does payment method affect churn?
- Does tenure impact customer retention?
- Are customers with higher monthly charges more likely to churn?
- What relationship exists between Monthly Charges and Total Charges?

---

## 🤖 Machine Learning Models

Three classification models were trained and evaluated.

| Model | Purpose |
|--------|---------|
| Logistic Regression | Baseline Linear Classifier |
| Decision Tree | Rule-Based Classification |
| Random Forest | Ensemble Learning |

---

## 📈 Model Evaluation Metrics

The models were evaluated using:

- Accuracy
- Precision
- Recall
- F1 Score
- ROC-AUC Score
- Confusion Matrix

### 🏆 Best Performing Model

**Logistic Regression** achieved the best overall performance on this dataset based on the evaluation metrics.

---

## 💡 Key Business Insights

- Customers with **Month-to-Month contracts** have the highest churn.
- **Long-tenure customers** are significantly more likely to stay.
- Customers with **higher monthly charges** tend to churn more frequently.
- **Fiber Optic** users exhibit relatively higher churn.
- **Electronic Check** customers show a higher churn rate.
- Gender has minimal influence on customer churn.

---

## 📌 Business Recommendations

- Encourage customers to migrate to long-term contracts.
- Implement retention campaigns targeting new customers.
- Review pricing strategies for high monthly charge customers.
- Improve customer experience for Fiber Optic subscribers.
- Use predictive models to proactively identify high-risk customers.

---

## 📁 Repository Structure

```
telecom-customer-churn-analysis/
│
├── data/
│   ├── Customer-Churn-raw.csv
│   ├── Customer-Churn-cleaned.csv
│   └── customer-churn-model-data.csv
│
├── Telecom_Customer_Churn_Analysis.ipynb
├── README.md
├── requirements.txt
├── LICENSE
└── .gitignore
```

---

## 🚀 Getting Started

### Clone the Repository

```bash
git clone https://github.com/arvindd333/telecom-customer-churn-analysis.git
```

### Install Dependencies

```bash
pip install -r requirements.txt
```

### Run the Notebook

Open the notebook using **Google Colab** or **Jupyter Notebook** and execute all cells sequentially.

---

## 📈 Future Improvements

- Hyperparameter Tuning
- Cross Validation
- XGBoost Implementation
- Model Explainability (SHAP)
- Interactive Dashboard using Power BI or Streamlit

---

## 👨‍💻 Author

**Arvind Anand Dyavanapelli**

- GitHub: https://github.com/arvindd333

---

## ⭐ If you found this project helpful, consider giving the repository a star.
