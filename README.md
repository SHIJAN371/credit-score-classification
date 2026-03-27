# 💳 Credit Score Classification

> **Internship Project 1** — Spinnaker Analytics Data Analyst Internship  
> Classifying customer credit scores using Machine Learning

---

## 📌 Project Overview

This project builds a machine learning pipeline to classify customers into credit score categories — **Good**, **Standard**, or **Poor** — based on their financial and demographic attributes. The goal is to help financial institutions make faster, data-driven lending decisions.

---

## 📁 Repository Structure

```
credit-score-classification/
│
├── credit_score_classification.ipynb   # Main Jupyter Notebook (full pipeline)
├── credit_score_data.csv               # Dataset used for training and testing
├── Credit_Score_Classification.pptx   # Project presentation slides
└── README.md                           # Project documentation
```

---

## 🔧 Tools & Technologies

| Category | Tools |
|---|---|
| Language | Python |
| Environment | Jupyter Notebook |
| Data Manipulation | Pandas, NumPy |
| Visualization | Matplotlib, Seaborn |
| Machine Learning | Scikit-learn |
| Models Used | Random Forest, XGBoost |

---

## 🔄 Project Workflow

1. **Data Loading & Exploration** — Understanding the dataset structure, features, and target variable
2. **Exploratory Data Analysis (EDA)** — Visualizing distributions, correlations, and class balance
3. **Data Cleaning & Preprocessing** — Handling missing values, encoding categorical features, scaling
4. **Model Training** — Training Random Forest and XGBoost classifiers
5. **Model Evaluation** — Comparing models using accuracy, classification report, and confusion matrix
6. **Conclusion** — Selecting the best model and summarizing key findings

---

## 🏆 Results

- **Best Model:** Random Forest Classifier
- Random Forest outperformed XGBoost on this dataset based on overall classification accuracy and consistency across all three credit score categories

---

## 📊 Target Classes

| Label | Description |
|---|---|
| `Good` | Low credit risk — eligible for loans/credit |
| `Standard` | Moderate credit risk — conditional approval |
| `Poor` | High credit risk — likely to be declined |

---

## 💡 Key Learnings

- Feature importance analysis revealed which financial factors most influence credit scores
- Data preprocessing (handling nulls, encoding, scaling) had a significant impact on model performance
- Ensemble methods like Random Forest are robust and effective for multi-class classification problems

---

## 👤 Author

**Shijan** — Data Analyst Intern at Spinnaker Analytics  
🔗 [LinkedIn](https://linkedin.com/in/your-linkedin-here) <!-- Replace with your actual LinkedIn URL -->

---

> *This project was completed as part of a 6-month Data Analyst Internship at Spinnaker Analytics.*
