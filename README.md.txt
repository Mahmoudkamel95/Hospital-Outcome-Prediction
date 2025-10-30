# 🏥 Hospital Outcome Prediction using Machine Learning

## 📘 Project Overview
This project aims to predict **hospital patient outcomes (Discharge vs Expiry)** using real-world clinical data and machine learning algorithms.  
The goal is to assist healthcare professionals in **early identification of high-risk patients**, enabling better resource allocation and timely interventions.

---

## 🧠 Project Workflow
1. **Data Cleaning & Preprocessing**
   - Handle missing values, inconsistent data, and incorrect data types.
   - Convert categorical variables to numeric formats.
2. **Feature Engineering**
   - Compute hospital stay duration and other derived metrics.
3. **Model Building**
   - Logistic Regression (Baseline)
   - Random Forest + SMOTE
   - XGBoost + SMOTE
4. **Model Evaluation**
   - Metrics: Precision, Recall, F1-score, ROC-AUC
   - Validation: Stratified train/test split (80/20)
5. **Feature Importance Analysis**
   - Identify key medical factors influencing patient outcomes.

---

## 📊 Model Performance
| Model | Accuracy | ROC-AUC | Notes |
|--------|-----------|----------|--------|
| Logistic Regression | 88.1% | 0.94 | Baseline model with balanced weights |
| Random Forest + SMOTE | 97.6% | 0.98 | Excellent recall for critical cases |
| XGBoost + SMOTE | **97.3%** | **0.99** | Best overall performance |

---

## 🔬 Top 10 Most Influential Features
- Type of Admission (Emergency / OPD)  
- Shock  
- HFREF (Heart Failure with Reduced Ejection Fraction)  
- Length of Stay (LOS_days)  
- CAD (Coronary Artery Disease)  
- ICU Duration  
- AKI (Acute Kidney Injury)  
- ACS (Acute Coronary Syndrome)  
- Atypical Chest Pain  
- CVA Bleed  

*(See the chart below for visualization)*  

![Feature Importance](A_bar_chart_in_the_image_titled_"Top_10_Most_Impor.png)

---

## 🧰 Tech Stack
- **Programming:** Python  
- **Libraries:** Pandas, NumPy, Scikit-learn, Imbalanced-learn, XGBoost, SHAP, Matplotlib  
- **Environment:** Jupyter Notebook  

---

## 👨‍⚕️ Author
**Dr. Mahmoud Kamel**  
Pharmacist | Data Analyst | AI Enthusiast in Healthcare  
📍 Interested in medical data analysis, AI-driven diagnosis, and predictive modeling in healthcare.

---

## 🧩 Key Takeaway
> Combining clinical data with AI can help predict patient outcomes early, allowing hospitals to make data-driven decisions and improve patient care.

---

⭐ *If you found this project useful, please give it a star on GitHub!*  