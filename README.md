# Heart Disease Prediction
Comprehensive heart disease prediction project with visualization, machine learning classification, and feature importance analysis.

## Task 1: Data Visualization
Visualize distribution of heart disease dataset:
- Age distribution & heart disease rate by age group
- Sex & heart disease incidence (pie chart)
- Chest pain type (cp) correlation
- Resting blood pressure (trtbps)
- Cholesterol levels
- Fasting blood sugar (fbs)
- Resting ECG results (restecg)
- Maximum heart rate (thalachh)
- Exercise induced angina (exng)
- ST depression (oldpeak)
- ST slope (slp)
- Major vessels (caa)
- Thalassemia (thall)
- Overall heart disease distribution

## Task 2 & 3: Machine Learning Classification & Efficiency Analysis
4 classifiers used:
- Logistic Regression
- Random Forest
- Support Vector Machine (SVM)
- Decision Tree

**Performance Results:**
- Logistic Regression: Accuracy 0.89, Time 0.0614s
- Random Forest: Accuracy 0.85, Time 0.1097s
- SVM: Accuracy 0.70, Time 0.0040s
- Decision Tree: Accuracy 0.77, Time 0.0030s

## Task 4: Feature Importance with SHAP
Using XGBoost + SHAP:
- Most important: caa (number of major vessels)
- Least important: fbs (fasting blood sugar)

---

## 📝 License
This project is for **academic & educational use only**.
