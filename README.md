# ◈ Credit Risk — Probability of Default Model

> Predicting loan defaults using machine learning to identify high-risk borrowers before it's too late.

---

## ◉ Overview

Banks and financial institutions lose billions every year from loans that go unpaid. This project builds a **Probability of Default (PD) model** on real-world public loan data to predict which borrowers are most likely to default — the same type of model used by banks like AIB for credit risk assessment.

---

## ⬡ The Problem

Lenders struggle to identify bad loans before approving them. Without a reliable scoring system, high-risk borrowers slip through and default rates rise. This project answers the question:

> **"Given a borrower's profile, how likely are they to default on their loan?"**

---

## ⟁ Tools & Technologies

| Area | Tools Used |
|------|-----------|
| Language | Python |
| Data Processing | pandas, NumPy, SQL |
| Modelling | scikit-learn (Logistic Regression) |
| Evaluation | ROC-AUC, Gini Coefficient, KS Statistic |
| Visualisation | Matplotlib, Seaborn |
| Environment | Jupyter Notebook |

---

## ⊹ Project Structure

```
credit-risk-pd-model/
│
├── data/
│   └── loan_data.csv          # Raw dataset
│
├── notebooks/
│   ├── 01_eda.ipynb           # Exploratory Data Analysis
│   ├── 02_preprocessing.ipynb # Cleaning & Feature Engineering
│   └── 03_model.ipynb         # Model Building & Evaluation
│
├── src/
│   └── model.py               # Core model script
│
└── README.md
```

---

## ↝ How It Works

**① Data Extraction & Cleaning (SQL + Python)**
- Loaded public loan dataset (e.g. Lending Club / German Credit)
- Used SQL queries to extract and segment borrower data
- Cleaned missing values, encoded categorical variables

**② Exploratory Data Analysis**
- Analysed default rates by loan grade, income band, and credit history
- Identified key features that drive default risk

**③ Model Building**
- Trained a **Logistic Regression** model — the industry standard for PD modelling
- Split data into training and test sets (80/20)

**④ Model Evaluation**
- **ROC-AUC:** `[add your score]`
- **Gini Coefficient:** `[add your score]`
- **KS Statistic:** `[add your score]`

---

## ◫ Results

| Metric | Score |
|--------|-------|
| ROC-AUC | `[your result]` |
| Gini Coefficient | `[your result]` |
| KS Statistic | `[your result]` |
| Accuracy | `[your result]` |

> The model successfully segments borrowers into risk bands, with high-risk borrowers showing significantly elevated default probabilities.

---

## ⟳ Future Improvements

- ▷ Add **macroeconomic stress testing** (e.g. simulate 5% unemployment rise)
- ▷ Build **LGD (Loss Given Default)** and **EAD** models alongside PD
- ▷ Align output with **IFRS 9** expected credit loss reporting format
- ▷ Deploy as a simple **web app** using Streamlit

---

## ◑ Author

**Sofiya Sarah Asif**
MSc Data Analytics — National College of Ireland
[GitHub](https://github.com/sofiya) · [LinkedIn](https://www.linkedin.com/in/sofiya-sarah-8331a32a1/)

---

## ◻ Dataset

Public dataset sourced from [Kaggle — Lending Club Loan Data](https://www.kaggle.com/datasets/wordsforthewise/lending-club) / [UCI German Credit Dataset](https://archive.ics.uci.edu/ml/datasets/statlog+(german+credit+data))

---

*Built as part of an MSc Data Analytics portfolio project, 2026.*
