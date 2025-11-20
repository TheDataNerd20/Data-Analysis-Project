# 🏗️ Data-Driven Concrete Compressive Strength Prediction  
Business Analytics • Statistical Modeling • Regression • Data Visualization  

This repository contains a complete Business Analytics project focused on predicting the **compressive strength of concrete** using statistical analysis, regression modeling, and data-driven insights.  
The project was developed as part of the **BUSA-511: Business Analytics for Managers** course (MS in Business Analytics).

---

## 📘 Project Overview

Concrete strength testing is critical for safety and structural quality, but traditional methods rely on **expensive and slow destructive testing**.  
This project demonstrates how **data analytics + regression modeling** can:

- Predict concrete compressive strength  
- Reduce destructive testing cost  
- Improve mix design quality  
- Support material optimization  
- Enhance construction decision-making  

The analysis is fully documented in the report and Excel sheets included in this repository.

---

## 📂 Repository Structure

---

## 📊 Dataset Summary

- **1030 concrete mix samples**
- **8 input variables**  
  (cement, slag, fly ash, water, superplasticizer, coarse agg., fine agg., age)
- **1 target**: Concrete compressive strength (MPa)
- **No missing values**
- Dataset sourced from **Kaggle / UCI Repository**

---

## 🧪 Techniques Used

### **1. Descriptive Analytics**
- Mean, median, standard deviation  
- Distribution analysis  
- Outlier identification  

### **2. Data Visualization**
- Histograms  
- Scatter plots  
- Correlation matrix  

### **3. Statistical Testing**
- **T-Test** comparing low vs high cement mixes  
- Result: Higher cement → significantly higher strength (p-value ≪ 0.05)

### **4. Regression Modeling**
A multi-variable regression model was trained on 70% of the dataset.

**Model Performance**
- **R² = 0.604**  
- **Adjusted R² = 0.599**  
- **MAE = 8.99**  
- **MAPE = 33.34%**  
- **MSE = 124.25**

**Significant predictors:**
- Cement  
- Blast furnace slag  
- Fly ash  
- Water  
- Superplasticizer  
- Age  

Negative impact: **Water**  
Positive impact: **Cement, Slag, Superplasticizer, Age**

---

## 🧠 Key Insights

- Cement has the strongest positive impact on strength  
- Water reduces strength (expected due to dilution effect)  
- Superplasticizer improves workability + strength  
- Aggregates show weak correlations  
- Strength increases with age due to hydration  

---

## 🏢 Business Value

This model provides immediate benefits to construction companies:

- Reduce the need for destructive testing  
- Optimize material proportions  
- Improve mix design efficiency  
- Increase structural reliability  
- Reduce cost & environmental waste  

---

## 🚀 Future Enhancements

- Add machine learning models (Random Forest, SVR, Neural Networks)  
- Build a Jupyter Notebook pipeline  
- Deploy a Streamlit web app for instant predictions  
- Apply SHAP for model explainability  
- Perform feature engineering for accuracy improvement  

---

## 🧑‍💻 Tech Used

- Microsoft Excel  
- Statistical Analysis  
- Regression Modeling  
- Business Analytics Concepts  
 
---

## 👤 Author

**Vishnu Vardhan Akula – The Data Nerd**  
MS in Business Analytics | Data Analyst
Texas A&M University–Commerce  

---

## 📎 Files Included

- **Data Analysis.xlsx** – full statistical analysis  
- **Project Report.docx** – complete report with findings  
- **Concrete Strength Prediction.pptx** – presentation slides  

---

### ⭐ If you like this project, feel free to star the repo!
