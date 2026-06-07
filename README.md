# healthcare-readmission-prediction
End-to-End Healthcare Readmission Prediction using Python, Machine Learning, and Interactive Dashboard.

# Healthcare Readmission Prediction

## Project Overview

This project analyzes healthcare patient data and predicts whether a diabetic patient will be readmitted within 30 days after hospital discharge.

The project covers:

- Data Cleaning
- Exploratory Data Analysis (EDA)
- Feature Engineering
- Machine Learning
- Dashboard Development

---

## Dataset

Healthcare Diabetic Patient Dataset

Records: 101,766

---

## Tools Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-Learn
- Power BI / HTML Dashboard
- GitHub

---

## Key Insights

- Patients aged 70–80 have the highest readmission frequency.
- Emergency visits increase the likelihood of readmission.
- Gender has minimal impact on readmission.
- Readmission rate is approximately 11%.

---

## Machine Learning Results

| Model | Accuracy | Recall |
|---------|---------|---------|
| Logistic Regression | 88.77% | 0% |
| Balanced Logistic Regression | 58.28% | 40.7% |
| Random Forest | 89% | 1% |

### Selected Model

Balanced Logistic Regression

Reason:

Healthcare prediction prioritizes recall because identifying high-risk patients is more important than maximizing accuracy.

---

## Dashboard

Interactive dashboard available in:

dashboard/healthcare_readmission_dashboard.html

---

## Author

Your Name
