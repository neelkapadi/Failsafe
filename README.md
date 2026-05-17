# FAILSAFE

AI-powered student risk prediction and intervention system.

## Problem Statement

In educational institutions, student failure often goes undetected until final semester results. Faculty lack proactive tools to identify at-risk students early.

FAILSAFE predicts student academic risk using machine learning and provides explainable AI-based intervention recommendations.

---

# Features

- Student risk prediction
- Random Forest + SMOTE model
- SHAP explainability
- Personalized intervention recommendations
- FastAPI backend
- React frontend
- Dynamic student inference using student index

---

# Tech Stack

## Machine Learning
- Python
- scikit-learn
- Random Forest
- SMOTE
- SHAP
- Pandas
- NumPy

## Backend
- FastAPI
- Uvicorn

## Frontend
- React.js
- Axios
- Vite

---

# Dataset

Student Performance Dataset (UCI/Kaggle)

---

# Project Architecture

Frontend (React)
↓
FastAPI Backend
↓
Random Forest + SMOTE Model
↓
Prediction + Recommendations
↓
Frontend Dashboard

---

# Model Pipeline

1. Data preprocessing
2. Label encoding
3. Train-test split
4. SMOTE balancing
5. Random Forest training
6. SHAP explainability

---

# Installation

## Clone Repository

```bash
git clone https://github.com/neelkapadi/Failsafe.git
```

## Install Dependencies

```bash
pip install -r requirements.txt
```

---

# Run Backend

```bash
cd backend
uvicorn main:app --reload
```

---

# Run Frontend

```bash
cd frontend
npm install
npm run dev
```

---

# Future Improvements

- SHAP visualization in frontend
- CSV upload for bulk prediction
- Faculty dashboard
- Authentication system
- Cloud deployment

---

# Authors

Neel M. Kapadi
