# 🛍️ Customer Lifetime Value (LTV) Prediction - E-Commerce

This project aims to predict the **Customer Lifetime Value (LTV)** using historical purchase behavior from an e-commerce dataset. The model helps businesses **segment customers** and make **data-driven marketing decisions**.

---

## 📌 Objectives

- Predict **LTV** based on **recency**, **frequency**, and **order value**
- Compare and tune models like **XGBoost** and **RandomForest**
- Evaluate using MAE, RMSE, and R² Score
- Segment customers (Low, Medium, High LTV)

---

## 📁 Files Included

- `XGBoost_Model.ipynb` – Full Python Notebook
- `ltv_predictions_By_XGBoost.csv` – Final output with predicted LTV and customer segments
- `RandomForest_Model.ipynb` – Full Python Notebook
- `ltv_predictions_By_RandomForest.csv` – Final output with predicted LTV and customer segments
- `README.md` – Project documentation
- `deliverable_Insights.pdf` – Model comparison.

---

## 🛠️ Tools & Libraries

- Python (Pandas, NumPy, Matplotlib, Seaborn)
- Scikit-learn
- XGBoost
- RandomForest
---

## 📈 Feature Engineering

We use **RFM Analysis** to derive core features:
- **Recency** – Days since last purchase
- **Frequency** – Number of unique purchases
- **AOV** (Average Order Value) – Total spend / Frequency

---

## 🧠 Models & Metrics

### 1. 📦 XGBoost Regressor
- MAE: 318.75
- RMSE: 4828.87
- R²: 0.668

### 2. 🔁 XGBoost + Log Transform
- MAE: 284.56
- RMSE: 3544.34
- R²: 0.778

### 3. 🌲 RandomForest Regressor
- MAE: 403.26
- RMSE: 3736.42
- R²: 0.801

---

## 🧪 Evaluation Metrics

- **MAE**: Average absolute error (lower is better)
- **RMSE**: Penalizes larger errors (lower is better)
- **R² Score**: Measures model fit (closer to 1 is better)

---

## 📊 Customer Segmentation

Based on predicted LTV, customers are categorized into:
- **High Value**
- **Medium Value**
- **Low Value**

Useful for targeted campaigns and personalized offers.

---

## 📌 Future Improvements

- Add more features (e.g., Country, Product Categories)
- Use time-series based modeling (e.g., LSTM or Prophet)
- Deeper hyperparameter tuning (RandomizedSearchCV)

---
---

## ✅ How to Run

1. Clone this repo  
2. Install dependencies using `pip install -r requirements.txt`  
3. Run the notebook: `XGBoost_Model.ipynb and RandomForest_Model.ipynb`  
4. Check `ltv_predictions_By_XGBoost.csv and ltv_predictions_By_RandomForest.csv` for results  

---

## 🧑‍💻 Author

Made with ❤️ by [Aftab Raza]


