# Predicting Employee Attrition  
### A Data-Driven Approach to Employee Retention  
**By: Enkel Mezini**

---

## 📌 Overview

Employee attrition is a costly issue — both financially and strategically. According to Gallup, **52% of voluntarily exiting employees say their manager or organization could have prevented them from leaving**. This project uses a machine learning approach to **predict employee attrition** and enable HR teams to take proactive retention measures.

---

## 🎯 Objective

To explore how predictive models built around key themes — **Engagement & Culture**, **Wellbeing & Work-Life Balance**, and **Pay & Benefits** — can provide actionable insights to reduce turnover and its associated costs.

---

## 🧠 Hypotheses

- Employees with **low job satisfaction** are more likely to leave.
- Employees with **high monthly income** are less likely to leave.
- Employees who **work overtime** are more likely to leave.

---

## 📊 Dataset Overview

The dataset includes a mix of:
- **Demographic data** (Age, Gender, MaritalStatus, etc.)
- **Job-related features** (Department, JobRole, OverTime, MonthlyIncome, etc.)
- **Performance and satisfaction scores**
- **Target Variable**: `Attrition` (Yes/No)

---

## 🧮 Machine Learning Models Used

| Model | Theme | Accuracy |
|-------|-------|----------|
| **Decision Tree** | Engagement & Culture | 78.91% |
| **SVM (Support Vector Machine)** | Wellbeing & Work-Life Balance | 74.83% |
| **Decision Tree** | Pay and Benefits | 65.99% |
| **Stacking Ensemble (Final Model)** | All Themes Combined | **85%** |

---

## 🧩 Final Model: Stacking Classifier

Combines:
- Logistic Regression
- Decision Tree
- Support Vector Machine (SVM)

**Performance:**
- **Accuracy**: 85%
- **AUC**: 0.80 (Good at distinguishing between stayers and leavers)
- **Lift**: 6x more effective in identifying true leavers early

---

## 📈 Key Variables by Theme

### Engagement & Culture
- JobSatisfaction
- JobRole
- Department
- JobInvolvement
- EnvironmentSatisfaction
- RelationshipSatisfaction

### Wellbeing & Work-Life Balance
- Age
- OverTime
- DistanceFromHome
- WorkLifeBalance
- MaritalStatus
- YearsSinceLastPromotion

### Pay and Benefits
- MonthlyIncome
- PercentSalaryHike
- StockOptionLevel
- JobLevel
- Education

---

## 🔍 Visual Insights

- **Confusion Matrix**: Indicates strong performance across categories
- **ROC Curve**: Shows high separability
- **Lift Curve**: 6x higher chance of catching potential attrition in early deciles

---

## 💼 Business Impact

- **Reduced Innovation Velocity**: Loss of skilled employees in R&D/AI slows down growth.
- **High Cost of Replacement**: ~$100K per lost employee in rehiring and training.
- **Loss of Client Trust**: Attrition in client-facing roles impacts relationships and delivery.

---

## ✅ Recommendations

1. **Predictive Retention Dashboards**
   - Integrate model into HR systems
   - Automate monthly attrition risk alerts

2. **Tailored Interventions**
   - Engagement risks: manager coaching, job rotation
   - Pay-related risks: off-cycle salary reviews or retention bonuses

3. **Pilot and Iterate**
   - Start with one region or department
   - Monitor attrition reduction and engagement scores

---


