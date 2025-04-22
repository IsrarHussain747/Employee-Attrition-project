# HR Analytics Attrition Report

## 📊 Overview

This project focuses on analyzing employee attrition using a dataset containing various demographic and employment-related features. The objective is to identify key factors that contribute to employee turnover and provide actionable business insights to improve employee retention.

---

## 🎯 Objective

- Understand the primary reasons behind employee resignations.
- Analyze demographic and workplace factors affecting attrition.
- Use machine learning models to predict employee attrition.
- Interpret model results using SHAP for transparency and decision-making.
- Provide business-level recommendations based on data insights.

---

## 📁 Dataset Features

Key features included in the dataset:

- `Age`
- `Job Role`
- `Monthly Income`
- `Distance From Home`
- `Education`
- `Attrition` (Target variable)

---

## ⚙️ Technologies Used

- **Python** (Data Processing & Modeling)
- **Pandas, NumPy** – Data manipulation
- **Matplotlib, Seaborn** – Data visualization
- **Scikit-learn, XGBoost** – Machine Learning
- **imblearn** – SMOTE for class balancing
- **SHAP** – Model interpretability

---

## 📈 Methodology

1. **Data Loading & Preprocessing**
   - Label encoding for categorical features
   - SMOTE to handle class imbalance

2. **Exploratory Data Analysis**
   - Visual trends in attrition by department, income, commute, and education

3. **Modeling**
   - Random Forest Classifier (87% Accuracy)
   - XGBoost Classifier (89% Accuracy)

4. **Model Interpretation**
   - SHAP values used to highlight the most influential features

---

## 💡 Business Insights

- **Key Causes of Attrition:**
  - Low monthly income
  - Long commuting distances
  - Job role mismatches (Sales, HR)
  - Education-job fit issues

- **Departments to Watch:**
  - Sales and HR show the highest turnover

- **Recommendations:**
  - Adjust salary structures
  - Introduce hybrid/remote policies
  - Enhance career development
  - Use regular feedback loops

---

## 📄 Report

A full Word report is included in this repository:  
📄 `HR_Analytics_Attrition_Report.docx`

---

## 📬 Contact

**Author:** Israr Hussain  
📧 [Your Email Here]  
🔗 [LinkedIn/GitHub/Twitter if applicable]

---

## 📌 License

This project is licensed under the MIT License.
