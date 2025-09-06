# 💳 Loan Repayment Prediction

This project aims to predict whether a loan applicant is likely to repay the loan using machine learning techniques. It's a complete data science pipeline that includes data preprocessing, exploratory data analysis (EDA), feature engineering, model training, evaluation, and result interpretation.

## 📌 Problem Statement

Given customer data, predict whether they will **repay the loan** or **default**, helping financial institutions make informed lending decisions and reduce risk.

## 📂 Project Structure

- `Loan_Repayment_Prediction.ipynb` – Main notebook with all preprocessing, model training, and evaluation.
- `data/` – Contains the input dataset (CSV format).
- `outputs/` – Stores charts, confusion matrix plots, and model evaluation results.

## 🔧 Technologies Used

- **Python**
- **Pandas, NumPy** – Data manipulation
- **Matplotlib, Seaborn** – Data visualization
- **Scikit-learn** – ML models and evaluation
- **XGBoost** – Gradient boosting classifier

## 🧠 ML Models Used

- Logistic Regression
- Decision Trees

## 📊 Evaluation Metrics

- Accuracy
- Confusion Matrix
- Precision, Recall, F1-Score

## 🔍 Key Steps

1. **Data Cleaning**: Handled nulls, categorical encoding, outlier removal
2. **EDA**: Visualized correlations and trends to understand patterns in defaults
3. **Feature Engineering**: Selected relevant features based on correlation and business logic
4. **Modeling**: Trained and compared multiple models
5. **Interpretation**: Analyzed key predictors of loan repayment

## ✅ Results

- Best performing model: **Decision Tree** with highest accuracy and recall
- Insights: Features like income, credit history, and loan amount played major roles in predicting repayment.

## 📈 Future Work

- Hyperparameter tuning using GridSearchCV
- Model deployment using Streamlit or Flask
- Add explainability with SHAP or LIME

## 👨‍💻 Author

SATYAVOLU SURYA VAMSI KRISHNA  


---

**Feel free to fork this project and customize it to improve model performance or integrate it into a web application.**
