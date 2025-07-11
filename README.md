# 📊 Customer Churn Prediction

This project predicts customer churn using a real-world telecom dataset. It includes complete data preprocessing, feature engineering, visualization, class balancing using SMOTE, and evaluation of three powerful models: **Logistic Regression**, **Random Forest**, and **XGBoost**.

---

## 🚀 Features
- Cleaned and prepared dataset from real-world telecom churn data  
- Exploratory Data Analysis (EDA) using Seaborn and Matplotlib  
- Feature engineering (e.g., tenure grouping, total services count)  
- One-hot encoding & label encoding  
- Class imbalance handled using **SMOTE**  
- Trained and evaluated:
  - Logistic Regression  
  - Random Forest Classifier  
  - XGBoost Classifier  
- AUC-ROC curve comparison  
- XGBoost feature importance visualization  

---

## 🧰 Tech Stack
- Python  
- Pandas, NumPy  
- Scikit-learn  
- XGBoost  
- imbalanced-learn (SMOTE)  
- Matplotlib & Seaborn  

---

## 📈 Model Evaluation
Each model was evaluated using:
- Classification report (Precision, Recall, F1-score)  
- ROC-AUC score  
- ROC Curve  

---

## 📎 How to Use

1. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

2. Run the notebook cells step by step to:
   - Load and clean the dataset  
   - Explore and visualize key patterns  
   - Train models and evaluate performance  

---

## 🔍 Key Insights
- **Long-term contracts** significantly reduce churn likelihood.  
- Customers with more add-on services (like Tech Support, Online Backup) are **less likely** to churn.  
- **MonthlyCharges** and **tenure** have a strong correlation with churn behavior.

---

The internship emphasizes hands-on learning in machine learning through self-paced projects and real-world problem-solving.

---


## 📄 License
This project is open-source and free to use for academic and learning purposes.

---

## 🙌 Acknowledgements
Thanks to:
- Future Interns for the internship opportunity  
- The creators of the Telco dataset  
- All open-source contributors to the libraries used in this project
