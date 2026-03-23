# 📊 End-to-End Customer Churn Prediction System

A production-style Machine Learning project that predicts customer churn using real-world telecom data.

This project demonstrates a complete ML lifecycle:

- Data Analysis
- Feature Engineering
- Model Training & Tuning
- Experiment Tracking (MLflow)
- API Deployment (FastAPI)
- Frontend UI (Streamlit)
- Cloud Deployment

---

# 🚀 Live Demo

### 🌐 Streamlit Frontend
https://churn-ml-frontend.streamlit.app/

### ⚡ FastAPI Backend
https://churn-ml-backend.onrender.com/docs

---

# 🎯 Problem Statement

Customer churn is a major problem in telecom businesses.  
Acquiring new customers costs more than retaining existing ones.

Goal:
> Predict whether a customer is likely to churn so the company can take proactive retention actions.

---

# 📁 Dataset

**Telco Customer Churn Dataset**

Contains:
- Customer demographics
- Account information
- Services subscribed
- Billing details
- Churn label

Target variable:


Churn (0 = Stay, 1 = Churn)


---

# 🔍 Exploratory Data Analysis

Performed:

✅ Missing value treatment  
✅ Duplicate removal  
✅ Outlier checks  
✅ Correlation analysis  
✅ Multicollinearity check using VIF  
✅ Class imbalance analysis  

Key Insight:
- Churners ≈ 27%
- Recall/F1 more important than accuracy

---

# 🧠 Feature Engineering

- One-hot encoding
- Binary mapping
- Service usage indicators
- Contract & payment encoding
- Multicollinearity reduction

---

# 🤖 Modeling

Models Tested:

- Logistic Regression
- Random Forest
- XGBoost (Best)

Evaluation Metrics:

- Accuracy
- Precision
- Recall
- F1 Score (Primary)

---

# 🏆 Best Model

**XGBoost Classifier**

Why chosen:
- Best F1-score
- Handles imbalance well
- Strong performance on tabular data

---

# 📈 Experiment Tracking

Used **MLflow** to:

- Track experiments
- Compare models
- Log parameters & metrics
- Register best model versions

---

# ⚙️ Backend (FastAPI)

FastAPI serves predictions via REST API.

Endpoint:



POST /predict


Input:
JSON with 22 features

Output:


{
"churn_prediction": 0 or 1
}


---

# 🎨 Frontend (Streamlit)

User-friendly UI for:

- Entering customer details
- Real-time predictions
- Clean dashboard interface

---

# ☁️ Deployment

### Backend
Deployed on Render

### Frontend
Deployed on Streamlit Cloud

Architecture:



User → Streamlit UI → FastAPI API → ML Model


---

# 🛠️ Tech Stack

Python  
Pandas, NumPy  
Scikit-learn  
XGBoost  
MLflow  
FastAPI  
Streamlit  
Render  
Git & GitHub

---

# 💼 Business Value

This system helps businesses:

- Identify at-risk customers
- Reduce churn
- Optimize retention campaigns
- Save revenue

---

# 📌 Key Learnings

- Importance of F1-score in imbalanced data
- Handling multicollinearity
- Experiment tracking with MLflow
- API-based ML deployment
- Frontend-backend separation
- Real-world MLOps workflow

---

# 🔮 Future Improvements

- SHAP explainability dashboard
- CI/CD automation
- Model monitoring
- Auto-retraining pipeline
- Authentication & security

---

# 👤 Author

**Balasubramanya C K**

# ⭐ If You Like This Project

Give it a star ⭐ on GitHub!
