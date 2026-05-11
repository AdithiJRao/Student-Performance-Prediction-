# 🎓 Student Performance Prediction System using Machine Learning

## 📌 Project Overview
The Student Performance Prediction System is a Machine Learning-based project developed to predict whether a student is likely to pass or fail based on academic, personal, and social factors.

The system analyzes student-related features such as study time, absences, previous grades, and family background to identify students who are at risk of poor academic performance.

This project helps educational institutions take early preventive actions and improve overall academic outcomes using data-driven insights.

---

# 🎯 Objectives

- Predict student academic performance
- Identify at-risk students early
- Help teachers take corrective measures
- Improve educational outcomes
- Apply Machine Learning techniques for predictive analysis

---

# 📊 Dataset Information

- Dataset Name: Student Performance Dataset
- Source: UCI Machine Learning Repository
- File Used: `student-mat.csv`
- Total Records: 395 Students

### Features Used
- Study Time
- Absences
- Previous Grades (G1, G2)
- Family and Social Factors
- Final Grade (G3)

### Target Variable
The target variable is created using the final grade (`G3`):

- Pass = 1
- Fail = 0

Condition:

```python
G3 >= 10 → Pass
G3 < 10 → Fail
