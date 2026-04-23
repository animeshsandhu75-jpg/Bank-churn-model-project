# 🏦 Customer Churn Prediction System

## 📌 Overview

This project predicts whether a bank customer is likely to churn using machine learning.
It goes beyond modeling by incorporating **statistical analysis, feature engineering, business impact evaluation, and model explainability**.

The goal is to enable **data-driven customer retention strategies**.

---

## 🎯 Business Problem

Customer churn leads to significant revenue loss. Retaining existing customers is more cost-effective than acquiring new ones.

This project identifies **high-risk customers** and helps businesses:

* Target retention campaigns efficiently
* Reduce unnecessary marketing costs
* Maximize revenue recovery

---

## 🧠 Approach

### 1. Exploratory Data Analysis (EDA)

* Distribution analysis
* Outlier detection
* Feature relationships

---

### 2. Statistical Validation

* T-test (Age vs Churn)
* Chi-square test (Categorical features)
* Confidence Intervals

---

### 3. Feature Engineering

* Age grouping
* Credit score segmentation
* Balance-to-salary ratio
* Log transformations

---

### 4. Data Preprocessing

* ColumnTransformer pipeline
* Standard scaling (numerical features)
* One-hot encoding (categorical features)

---

### 5. Modeling

* Logistic Regression
* Random Forest (final model)

---

### 6. Hyperparameter Tuning

* GridSearchCV with cross-validation
* Optimized for **recall (churn detection)**

---

### 7. Model Evaluation

* Precision, Recall, F1-score
* ROC-AUC Curve
* Threshold tuning

---

### 8. Business Metrics

* Lift analysis
* Cost-benefit simulation

---

### 9. Model Explainability

* SHAP (feature-level impact)
* Global & individual predictions explained

---

## 📊 Results

* **Recall:** ~73% (captures majority of churn customers)
* **ROC-AUC:** 0.85 (strong classification ability)
* **Lift:** ~4.7 (top customers are ~5x more likely to churn)

---

## 💰 Business Impact

Using model-based targeting (top 20% high-risk customers):

* **Revenue Saved:** ₹12.1M
* **Retention Cost:** ₹2.0M
* **Net Profit:** ₹10.1M

Compared to random targeting:

* **Profit:** ₹1.65M

👉 **~6x improvement in profitability**

---

## 🔍 Key Insights

* Inactive customers are highly likely to churn
* Older customers show higher churn tendency
* Customers with more products have increased churn risk
* Behavioral factors outweigh demographic features

---

## 🖥️ Deployment

The model is deployed using:

* **Streamlit** (interactive UI)
* User inputs → churn prediction
* Risk categorization (High / Medium / Low)

---

## 🛠️ Tech Stack

* Python
* Pandas, NumPy
* Scikit-learn
* Matplotlib, Seaborn
* SHAP
* Streamlit

---

## 📂 Project Structure

```
├── data/
├── notebook/
├── model/
├── app.py
├── requirements.txt
├── README.md
```

---

## 🚀 How to Run

```bash
pip install -r requirements.txt
streamlit run app.py
```

---

## 💬 Conclusion

This project demonstrates an end-to-end data science workflow, combining:

* Statistical rigor
* Machine learning
* Business impact analysis
* Model explainability

It highlights how machine learning can be used not just for prediction, but for **real-world decision-making and profitability improvement**.

---

## 📌 Future Improvements

* Model monitoring & retraining pipeline
* Advanced models (XGBoost, LightGBM)
* A/B testing for retention strategies
* Integration with real-time data systems

---

## 👤 Author

Animesh Sandhu
