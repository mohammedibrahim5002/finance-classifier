# 💳 ML Finance Transaction Classifier

A machine learning project that automatically classifies financial transactions into categories such as **Food, Travel, Bills, Grocery, and Entertainment** using transaction metadata.

This project demonstrates a **complete ML workflow** including data preprocessing, model training, evaluation, and model deployment readiness.

---

## 📌 Problem Statement

Personal finance apps often require transactions to be categorized manually.
This project builds a machine learning model that **automatically classifies financial transactions** based on attributes like amount, merchant type, payment method, and device used.

Automating this task improves:

* expense tracking
* budgeting insights
* financial analytics

---

## 🧠 Machine Learning Approach

The model was trained using a **Gradient Boosting Classifier** to predict the category of a transaction.

### Features Used

* `Amount`
* `PaymentMethod`
* `AccountType`
* `DeviceUsed`
* `MerchantType`

### Target Variable

* `Category`
  (Transaction label such as Food, Travel, Bills, etc.)

---

## ⚙️ Model Performance

| Metric            | Score    |
| ----------------- | -------- |
| Accuracy          | **82%**  |
| Average Precision | **~84%** |
| Average Recall    | **~81%** |
| Weighted F1 Score | **~80%** |

The model performs well across multiple transaction categories while maintaining balanced performance.

---

## 🗂 Project Structure

```
ml-finance-classifier/
│
├── data/
│   └── transactions.csv
│
├── models/
│   └── finance_classifier.pkl
│
├── notebooks/
│   └── finance_classifier.ipynb
│
├── requirements.txt
├── README.md
└── .gitignore
```

---

## 📊 Workflow

1. **Data Preprocessing**

   * Handling categorical features
   * Encoding transaction attributes

2. **Model Training**

   * Gradient Boosting Classifier
   * Hyperparameter tuning

3. **Model Evaluation**

   * Accuracy
   * Precision
   * Recall
   * Classification Report

4. **Model Export**

   * Model saved as `.pkl` file for deployment

---

## 🚀 How to Run the Project

### 1️⃣ Clone the repository


### 2️⃣ Install dependencies

```bash
pip install -r requirements.txt
```

### 3️⃣ Train the model


### 4️⃣ Make predictions

---

## 🔮 Future Improvements

* Deploy the model using **FastAPI or Flask**
* Add **real-time transaction prediction API**
* Build a **Streamlit dashboard**
* Improve performance with additional transaction features

---

## 🛠 Technologies Used

* Python
* Pandas
* NumPy
* Scikit-learn
* Joblib

---
"# finance-classifier" 
"# finance-classifier" 
"# finance-classifier" 
