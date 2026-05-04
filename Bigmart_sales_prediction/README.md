# 🛒 BigMart Sales Prediction

Ever wondered how stores predict how much a product will sell?

In this project, I built a Machine Learning model to predict product sales for BigMart stores using real-world data. The goal was simple — understand the data, clean it properly, and build a model that can make accurate predictions.

---

## 📌 What this project is about

This is an end-to-end beginner-friendly ML project where I:

- Explored and understood the dataset
- Cleaned missing and messy data
- Performed visual analysis (EDA)
- Converted categorical data into numerical form
- Trained a Machine Learning model
- Evaluated how well the model performs

---

## 📂 About the Dataset

The dataset contains information about products and stores, such as:

- Product weight, type, and price (MRP)
- Store size and location
- Visibility of items
- Sales of each product (target variable)

🎯 **Goal:** Predict `Item_Outlet_Sales`

---

## 🔍 What I actually did (step-by-step)

### 🧹 Data Cleaning
- Filled missing values:
  - `Item_Weight` → mean value
  - `Outlet_Size` → most frequent value

---

### 📊 Exploratory Data Analysis (EDA)
- Used **Seaborn & Matplotlib**
- Checked:
  - Distribution of numerical features
  - Count of categorical features
- Understood patterns in data

---

### 🔄 Feature Engineering
- Fixed inconsistent categorical values
- Applied **Label Encoding** to convert text into numbers

---

### 🤖 Model Building
- Used **XGBoost Regressor** (powerful ML model)
- Trained the model on processed data

---

### 📈 Model Evaluation
- Used **R² Score** to measure performance

---

## 🚀 How to run this project

You don’t need any complex setup 😄

1. Open the notebook in **Google Colab** or Jupyter
2. Upload the `Train.csv` file
3. Run all cells step by step

---

## 🛠️ Tech Stack

- Python 🐍
- Pandas & NumPy (data handling)
- Matplotlib & Seaborn (visualization)
- Scikit-learn (ML tools)
- XGBoost (model)

---

## ⚠️ Small Fix (Important)

If you run the notebook and get an error, make sure you added:

```python
from sklearn.preprocessing import LabelEncoder
