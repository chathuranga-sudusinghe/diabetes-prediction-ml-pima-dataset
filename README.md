# 🩺 Diabetes Prediction – Machine Learning (Pima Dataset)

This project presents an **end-to-end machine learning analysis** to predict whether a patient has diabetes using clinical and demographic features from the **Pima Indians Diabetes Dataset**.

The objective is to follow a **professional ML workflow**, including data cleaning, exploratory data analysis (EDA), baseline modeling, non-linear model comparison, and model explainability, suitable for **healthcare decision support**.

This is a **real-world healthcare machine learning project** focused on model performance, interpretability, and best practices.

---

## 📊 Project Objectives

- Build a machine learning model to predict diabetes
- Understand clinical feature distributions using EDA
- Handle medically invalid zero values appropriately
- Establish a baseline model using Logistic Regression
- Train and evaluate a non-linear model (Random Forest)
- Compare models using healthcare-relevant metrics
- Interpret model behavior using feature importance
- Produce a Kaggle-ready and GitHub-ready ML project

---

## 📂 Dataset

- **Source:** Pima Indians Diabetes Dataset (UCI / Kaggle)
- **Records:** 768 patients
- **Features:** Clinical and demographic measurements
- **Target Variable:** `Outcome`
  - `0` → No Diabetes
  - `1` → Diabetes

---

## 🧠 Machine Learning Workflow

- Data loading and understanding  
- Exploratory Data Analysis (EDA)  
- Identification of medically invalid zero values  
- Data cleaning using median imputation  
- Train/Test split with stratification  
- Feature scaling  
- Baseline model: Logistic Regression  
- Non-linear model: Random Forest  
- Model comparison and selection  
- Feature importance interpretation  
- Final conclusions and future work  

---

## 🤖 Models Used

- **Logistic Regression** (Baseline Model)
- **Random Forest Classifier** (Final Model)

### ✅ Final Model Selection
Random Forest was selected as the final model due to:
- Higher overall accuracy (~74%)
- Improved recall for diabetic patients
- Better handling of non-linear relationships

---

## 🔍 Key Insights

- **Glucose** is the most influential feature in diabetes prediction
- **BMI, Age, and Insulin** significantly affect risk levels
- Random Forest captures clinically meaningful patterns better than linear models

---

## ⚠️ Limitations

- Moderate class imbalance in the dataset
- Relatively small sample size
- No hyperparameter tuning applied

---

## 🚀 Future Improvements

- Hyperparameter tuning (GridSearch / RandomSearch)
- Class imbalance handling (class weights, SMOTE)
- Threshold optimization to improve recall
- Advanced model explainability using SHAP

---

## 🛠️ Tools & Technologies

- Python  
- Pandas, NumPy  
- Matplotlib, Seaborn  
- Scikit-learn  
- Kaggle Notebook  
- GitHub  

---

## 📎 Links

- **Kaggle Notebook:** *(add your Kaggle notebook link here)*  
- **Dataset:** https://www.kaggle.com/datasets/uciml/pima-indians-diabetes-database  

---

## 👤 Author

**Chathuranga**  
Data Analyst | Aspiring Data Scientist  

---

## 🏁 Project Status

✅ Completed  
📌 Ready for Kaggle publishing and GitHub portfolio
