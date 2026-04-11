# HR Employee Attrition Prediction

**Best Model Accuracy:** 86.17% | **Type:** Classification

---

## 📌 Business Problem
Employee turnover costs **33-200% of annual salary** ($20k-$120k per employee). This model predicts which employees are likely to leave.

---

## 🔧 Data Preprocessing & EDA

| Step | What We Did |
|------|-------------|
| Missing values | None found (1,470 records) |
| Target encoding | Yes/No → 1/0 |
| Text encoding | 8 columns → numbers |
| Feature selection | Removed ID columns |
| Train-test split | 70/30 |

**Key EDA Finding:** Overtime employees are **33% leave vs 8%** without overtime ⚠️

---

## 📊 Results

| Model | Accuracy | Precision | Recall |
|-------|----------|-----------|--------|
| **Logistic Regression** | **86.17%** | 69.49% | 43.62% |
| Decision Tree | 77.32% | 40.35% | 48.94% |

---

## 🔍 Top 5 Predictors

| Rank | Factor | Impact |
|------|--------|--------|
| 1 | **OverTime** | Working overtime = much higher chance of leaving |
| 2 | **YearsAtCompany** | New employees (under 3 years) leave most |
| 3 | **JobSatisfaction** | Low satisfaction = high risk |
| 4 | **MonthlyIncome** | Lower paid employees leave more |
| 5 | **WorkLifeBalance** | Poor balance increases risk |

---

## 💡 Business Recommendations

| Action | How to Implement |
|--------|------------------|
| **Identify at-risk employees** | Run model monthly on all employees |
| **Reduce overtime** | Review policy, limit mandatory overtime |
| **Mentor new hires** | Focus on first 3 years |
| **Conduct stay interviews** | Talk to high-risk employees before they quit |
| **Fix satisfaction issues** | Act on survey feedback quickly |

**Expected Impact:** Reduce turnover 15-20% | Save **$500,000+ annually**

---

## ⚠️ Limitations

| Limitation | Fix |
|------------|-----|
| Only 1,470 records | Collect more data |
| Recall only 44% | Try better models (Random Forest) |
| Single company data | Test on multiple companies |

---

## 🛠️ Tools
Python (Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn)

## 📁 Files
- `hr_attrition_prediction.ipynb` - Code
- `hr_employee_attrition.csv` - Data

## 👨‍💻 Author
Name: MD  Junayed Uddin 
Course: **Applied Machine Learning for Business Analytics with Python** 
Date: 10/05/2026

## 🔗 GitHub
https://github.com/mdjunayeduddin-BRACU/HR-ATTRITION-PROJECT.git

## 📝 AI Disclosure
AI tools used for code understanding & debugging. All code has been run and tested by me.
