# 🕵️‍♀️ Credit Card Fraud Detection Using Machine Learning

This project analyzes anonymized credit card transactions to detect fraudulent activity using supervised machine learning models.

## 📌 Objective
Build a model that can accurately classify fraudulent transactions based on 28 anonymized features using real-world credit card data.

---

## 🧰 Tools & Technologies
- Python
- Pandas, NumPy
- Scikit-learn
- Matplotlib, Seaborn
- Logistic Regression
- Random Forest
- AUC-ROC, Precision, Recall, F1-score

---

## 📊 Dataset
- Source: [Kaggle – Credit Card Fraud Detection](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud)
- 284,807 transactions over 2 days in Europe
- Only **492 fraud cases** (0.172%)

---

## 🔍 Steps Performed
1. **EDA**: Explored imbalance, transaction patterns
2. **Preprocessing**: Scaled `Time` and `Amount`, dropped originals
3. **Train-Test Split**: Stratified split for fair evaluation
4. **Models Used**:
   - Logistic Regression (baseline)
   - Random Forest (advanced)
5. **Evaluation**:
   - Confusion Matrix
   - Classification Report (Precision, Recall, F1)
   - AUC-ROC Score

---

## 📈 Results

| Model              | Precision (Fraud) | Recall (Fraud) | F1-score (Fraud) | AUC-ROC |
|-------------------|------------------|----------------|------------------|---------|
| LogisticRegression| ~0.87            | ~0.65          | ~0.74            | ~0.92   |
| RandomForest       | **0.96**         | **0.76**       | **0.85**         | **0.958** |

---

## 📁 Files in This Repo
- `credit_card_fraud.ipynb` – Full notebook with preprocessing, modeling, and evaluation
- `creditcard.csv` – Dataset 
- `README.md` – This file

---

## 🤝 Let's Connect
**Adheena Thomas**  
[LinkedIn](https://www.linkedin.com/in/adheenathomas2002)  
[GitHub](https://github.com/Adheenaa123)

---

