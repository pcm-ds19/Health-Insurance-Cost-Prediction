# Health-Insurance-Cost-Prediction
Capstone Project – Predicting health insurance costs using personal, lifestyle,  and medical attributes | PGP-DSBA (Great Learning | Great Lakes & Texas McCombs).


This repository contains my **Capstone Project** completed as part of the  **Post Graduate Program in Data Science and Business Analytics (PGP-DSBA), delivered on the Great Learning platform in collaboration with Great Lakes Institute of Management & Texas McCombs School of Business (Aug 2024 – Aug 2025).**

---

## 🔹 Project Overview
The project focuses on predicting **health insurance costs** using individual lifestyle, medical, and demographic attributes.  
Rising healthcare costs make accurate, personalized premium estimation essential for both insurers and customers.  
This project builds data-driven models to personalize pricing, manage risk, and provide business recommendations.

---

## 🔹 Key Steps
1. **Exploratory Data Analysis (EDA)**  
   - Distribution & trend analysis  
   - Bivariate & multivariate relationships  
   - K-Means clustering for customer segmentation  

2. **Data Preprocessing**  
   - Missing value treatment (BMI, Year_last_admitted)  
   - Outlier handling (retained medically significant values)  
   - Encoding categorical variables  
   - Feature engineering: Age groups, BMI categories, Health Risk Score, log_BMI_by_Age  

3. **Model Building & Validation**  
   - 8 Models tested: Linear, Ridge, Lasso, Decision Tree, Random Forest, Gradient Boosting, XGBoost, SVR, KNN  
   - Hyperparameter tuning using GridSearchCV  
   - Model explainability with SHAP  

---

## 🔹 Final Model
- **Chosen Model:** Tuned Random Forest Regressor  
- **Performance:**  
  - R² = **0.9549**  
  - MAE ≈ **₹2408**  
  - RMSE = **₹3030**  
- **Interpretability:** SHAP used to identify top drivers (Glucose, BMI, Age, Fat %, Weight Change).  

---

## 🔹 Business Insights
- **High BMI, glucose, and smoking** → major cost inflators.  
- **Regular checkups & active lifestyle** → associated with reduced costs.  
- **Cluster segmentation (K=3)** identified low, moderate, and high-risk groups for insurers.  
- Recommendations include risk-based pricing, wellness incentives, and preventive health campaigns.

---

## 🔹 Files
- https://github.com/pcm-ds19/Health-Insurance-Cost-Prediction/blob/main/Capstone_Health_Insurance_Cost_Prediction.ipynb.ipynb → Full Google Colab notebook (EDA, modeling, SHAP).  
- https://github.com/pcm-ds19/Health-Insurance-Cost-Prediction/blob/main/Final%20business%20report%20of%20capstone%20project.pdf → Detailed report with visuals, insights, and recommendations.  

---

 *This project demonstrates end-to-end application of data science: EDA, clustering, regression modeling, model tuning, interpretability, and business translation.*

