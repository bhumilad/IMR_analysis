# 🩺 Healthcare Insurance Review & Diagnosis Analytics

## 📌 Project Overview
This project focuses on uncovering inefficiencies and bias within healthcare insurance decision-making processes. We analyzed patient demographics, diagnosis categories, and decision timelines to help healthcare organizations **streamline operations, reduce delays, and promote fairness in medical determinations.**

> **Objective**: Transform raw healthcare review data into actionable insights and future-ready dashboards using **Python, Power BI, and Machine Learning** foundations.

---

## 💡 Key Business Questions
- What demographic groups experience longer review times or higher rejection rates?
- Are certain diagnoses linked to slower processing or more overturns?
- How has the fairness of decisions evolved over time?
- What improvements can be made in review processes and healthcare communication?

---

## 🛠️ Tools & Technologies
| Stack | Tools Used |
|-------|------------|
| **Data Cleaning & Prep** | Python (Pandas, NumPy), Excel |
| **Visualization** | Matplotlib, Seaborn , Power BI |
| **Data Modeling (next phase)** | ML model for Determination prediction |

---

## 🧹 Data Preparation
- Handled missing values, standardized diagnosis names, and extracted meaningful features.
- Engineered key variables: `DaysToReview`, `AgeGroup`, `DecisionType`, `DiagnosisType`.
- Created filtered and optimized datasets for dashboarding and future ML usage.

---

## 📊 Dashboards Created
### 📌 1. **Medical Insurance Rejection Analysis**
- Yearly trends of Rejections, Overturned vs. Upheld
- 2016 spike linked to **Senate Bill 863** — uncovered through web research
- Visual drill-down into rejection reasons and gender/age-based discrepancies

### 📌 2. **Patient & Diagnosis Overview**
- Mental disorders are **most diagnosed**, while **infection diseases** dominate **ages 51–64**
- Younger and underrepresented gender patients (11–20, ‘Others’ category) face more rejections — but show higher **acceptance upon reapplication**
- After **2019**, overturned outcomes have increased, indicating **improved fairness**

---

## 🔍 Notable Findings

- 📈 **Overturned decisions are processed faster** than upheld ones
- 🧑‍⚕️ **After 2008**, decision adoption takes **longer** than review — change in process?
- 🔁 Reapplication success is highest for underrepresented groups (age 11–20, gender "Others")
- 🧠 **Mental health and infections** dominate case diagnoses
- 📅 **2016** anomaly tied to policy changes (**Senate Bill 863**)

---

## ✅ Recommendations
- **Transparent communication** with youth and guardians during initial filing
- **Tailored outreach** programs for patients aged **51–64**
- **Conduct quality audits** on decisions with high overturn likelihood
- **Feedback loop** to improve and refine decision-making protocols
- **AI-Powered Recommendation Engine** (Next Phase) for automated risk-based predictions

---

## 📈 Next Steps
- 💻 **Real-Time Monitoring**: Embed dashboards for real-time decision insights
- 🤖 **Predictive Modeling**: Train ML models to predict `Determination` variable using logistic regression, random forest, or XGBoost
- 🔁 **Automated Alerts**: Flag potential unfair or delayed cases for manual re-evaluation

---

## 🧠 Conclusions
- **Mental health and infectious diseases** top the list of diagnosed conditions, especially in ages **51–64**
- **Fairness is improving post-2019**, with more overturned decisions
- **Timely processing** often leads to **more favorable outcomes** (faster = overturned)
- **Younger and underrepresented patients** are more likely to face rejections, but also more likely to succeed on reapplication

---
