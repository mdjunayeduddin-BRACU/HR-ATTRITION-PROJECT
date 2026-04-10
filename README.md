# HR Employee Attrition Prediction

**Project Type:** Classification (Predict Yes/No)  
**Target Variable:** Attrition (Will employee leave?)  
**Best Model Accuracy:** 86.17%

---

## 📌 Business Problem

Employee turnover costs companies **33-200% of annual salary** ($20k-$120k per employee). This model predicts which employees are likely to leave, enabling proactive retention.

---

## 📊 Quick Results

| Model | Accuracy | Precision | Recall |
|-------|----------|-----------|--------|
| **Logistic Regression** | **86.17%** | 69.49% | 43.62% |
| Decision Tree | 77.32% | 40.35% | 48.94% |

**Best Model:** Logistic Regression (86.17% accurate)

---

## 🔍 Key Predictors & Their Impact

| Rank | Predictor | Impact on Attrition |
|------|-----------|---------------------|
| 1 | **OverTime** | Working overtime = MUCH higher chance of leaving |
| 2 | **YearsAtCompany** | New employees (under 3 years) leave most |
| 3 | **JobSatisfaction** | Low satisfaction = high risk |
| 4 | **MonthlyIncome** | Lower paid employees leave more |
| 5 | **WorkLifeBalance** | Poor balance increases risk |

---

## 💡 Business Insights

### What the Data Tells Us:
- **Overtime is #1 reason** employees leave (burnout)
- **First 3 years are critical** - highest turnover period
- **Money matters** but satisfaction & balance matter too

### How to Apply This Model:

| Action | How to Implement |
|--------|------------------|
| **Identify at-risk employees** | Run model monthly on all employees |
| **Review overtime policy** | Reduce mandatory overtime, track hours |
| **Focus on new hires** | Mentorship program for first 3 years |
| **Conduct stay interviews** | Talk to high-risk employees before they quit |
| **Fix satisfaction issues** | Act on survey feedback quickly |

### Expected Business Impact:
- Reduce turnover by **15-20%**
- Save **$500,000+ annually** for 500-employee company
- Improve employee morale and retention

---

## ⚠️ Limitations & Improvements

| Limitation | How to Improve |
|------------|----------------|
| Only 1,470 records | Collect more data (5,000+ employees) |
| Recall only 44% | Misses 56% of leavers - need better model |
| Single company data | Test on multiple companies |
| 35 features only | Add manager ratings, commute time |

**Next Steps:** Try Random Forest model, add more data, build HR dashboard

---

## 🛠️ Tools Used

- Python (Pandas, NumPy, Scikit-learn)
- Models: Logistic Regression, Decision Tree
- Visualization: Matplotlib, Seaborn

---

## 📁 Files

- `hr_attrition_prediction.ipynb` - Complete code
- `hr_employee_attrition.csv` - Dataset (1,470 employees)
- `README.md` - This file

---

## 👨‍💻 Author

**Name:** MD Junayed Uddin 
**Course:** Business Analytics  
**Date:** 05/10/2026

---

## 🔗 GitHub Repository

(https://github.com/mdjunayeduddin-BRACU/HR-ATTRITION-PROJECT.git)

---

## 📝 AI Disclosure

AI tools (ChatGPT) were used for code understanding, debugging, and explanation. All code was run and tested by me. I can explain every part of this project.
