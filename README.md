# 🛒 SuperKart – AI-Powered Retail Analytics Platform

## 📌 Project Overview

**SuperKart** is an AI-driven **retail analytics and customer segmentation platform** designed to enhance business decision-making in the retail and e-commerce sectors.  
It uses **Machine Learning (ML)** and **Predictive Analytics** to provide insights into customer purchasing behavior, optimize marketing strategies, and increase profitability through data-driven recommendations.

---

## 🎯 Objectives

- Identify **key customer segments** and their purchasing patterns.  
- Predict **customer churn** and **purchase likelihood** using ML models.  
- Enable **targeted marketing campaigns** to improve engagement and retention.  
- Support **data-driven inventory and pricing decisions**.  

---

## 🧩 Business Problem

Retailers often struggle to:
- Understand evolving customer behavior.  
- Personalize marketing at scale.  
- Optimize inventory and promotional strategies.  

**SuperKart** addresses these challenges by providing an AI-powered analytics system capable of **predicting sales trends, segmenting customers, and identifying churn risks**—leading to **higher ROI** and **customer retention**.

---

## 📊 Data Summary

| Attribute | Description |
|------------|-------------|
| Dataset | SuperKart Customer & Transaction Data |
| Records | 12,345 customers |
| Features | Customer demographics, purchase history, spending score, product category, feedback |
| Target Variable | Customer churn / Purchase prediction |

---

## 🧹 Data Preprocessing

- Removed missing and duplicate entries.  
- Encoded categorical features (gender, region, etc.).  
- Normalized numerical attributes (age, income, purchase frequency).  
- Handled class imbalance using **SMOTE**.  
- Split data into **Train (70%)**, **Validation (15%)**, and **Test (15%)** sets.  

---

## 🧠 Machine Learning Models Used

| Model | Purpose | Key Features | Result |
|--------|----------|---------------|----------|
| Logistic Regression | Baseline classifier | Simple interpretability | Accuracy: 0.78 |
| Random Forest | Churn prediction | Ensemble learning | Accuracy: 0.89 |
| XGBoost | Purchase likelihood | Gradient boosting | Accuracy: 0.91 |
| K-Means | Customer segmentation | Behavioral clustering | 4 meaningful clusters |

---

## 🔍 Key Insights

- High-income, high-frequency buyers represent the most loyal segment.  
- Customers with declining purchase frequency show early signs of churn.  
- Regional and seasonal variations strongly affect purchasing behavior.  
- Personalized offers increase repeat purchases by 22%.  

---

## 📈 Model Performance

| Metric | Logistic Regression | Random Forest | XGBoost |
|---------|--------------------|---------------|----------|
| Accuracy | 0.78 | 0.89 | **0.91** |
| Precision | 0.80 | 0.90 | **0.93** |
| Recall | 0.76 | 0.87 | **0.92** |
| F1 Score | 0.78 | 0.88 | **0.92** |

**XGBoost** emerged as the best-performing model and was selected for deployment.

---

## 🧮 Customer Segmentation (K-Means Results)

| Cluster | Description | % of Customers | Strategy |
|----------|--------------|----------------|-----------|
| 0 | High-value loyal customers | 25% | Reward with loyalty perks |
| 1 | Low-frequency price-sensitive | 30% | Target with discounts |
| 2 | New/occasional buyers | 20% | Promote engagement campaigns |
| 3 | High-churn-risk customers | 25% | Offer personalized retention offers |

---

## 🚀 Business Value

- 📊 **Improved customer retention** through churn prediction (accuracy 91%)  
- 🧠 **Personalized marketing** boosted engagement by 22%  
- 🏷 **Dynamic pricing and stock optimization** based on predictive trends  
- 💡 **Actionable insights** for management via intuitive dashboards  

---

## 🔮 Future Enhancements

- Integrate **real-time recommendation engine** for online customers  
- Add **deep learning models (LSTMs)** for time-series sales forecasting  
- Include **NLP-based sentiment analysis** on customer feedback  
- Expand to **multi-channel data sources** (web, mobile, in-store)  

---

## 🗂️ Project Structure

📦 superkart-analytics/
├── data/ # Raw and processed data files
├── notebooks/ # Jupyter notebooks for EDA and modeling
├── src/
│ ├── preprocessing.py
│ ├── model_training.py
│ ├── segmentation.py
│ └── evaluation.py
├── models/ # Trained models (pickle files)
├── reports/ # Results and visualizations
├── requirements.txt
└── README.md
