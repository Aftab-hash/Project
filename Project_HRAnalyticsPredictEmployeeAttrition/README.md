# 🧠 HR Analytics: Employee Attrition Prediction

This project uses machine learning and business intelligence to predict employee attrition and uncover actionable insights using SHAP explainability and Power BI dashboards.

## 📌 Overview

Employee attrition poses significant challenges to organizations. This project aims to:

- Predict which employees are likely to leave the company.
- Identify key drivers of attrition using SHAP.
- Provide actionable prevention strategies.
- Visualize workforce insights using Power BI.

---

## 📂 Project Structure

HR-Attrition-Prediction/
├── data/
│   ├── HR-Employee-Attrition.csv      # Cleaned & feature-engineered dataset
│   └── HR_Attrition_with_SHAP.csv 
│   └── shap_feature_importance_with_attrition.csv
├── notebooks/
│   └── attrition_modeling.ipynb        # Jupyter notebook with EDA, modeling, SHAP
├── reports/
│   ├── Project_report.pdf 
│   └── ModelEvaluationReport_and_AttritionPreventions.pdf    # Accuracy, confusion matrix, SHAP ,SHAP-based HR recommendations
├── dashboard/
│   └── HR_Attrition_DASHBOARD.pdf              # Power BI dashboard
└── README.md
 
🛠️ Tools & Libraries
 -   Python (Pandas, Scikit-learn, SHAP, Seaborn)
 -  Machine Learning Models: Logistic Regression, Decision Tree, Random Forest
 -  Power BI: For interactive dashboards
 -  Jupyter Notebook: For EDA, modeling, and explainability
 
📊 Model Performance
 
| Model               | Accuracy | Precision | Recall | F1-Score |
| ------------------- | -------- | --------- | ------ | -------- |
| Logistic Regression | 86.40%   | 84.50%    | 86.40% | 84.40%   |
| Decision Tree       | 82.00%   | 78.20%    | 82.00% | 79.50%   |
| Random Forest       | 84.40%   | 80.60%    | 84.40% | 79.10%   |

