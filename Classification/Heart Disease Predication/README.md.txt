# Heart Disease Prediction using Machine Learning

## Project Overview

This project focuses on predicting the presence of heart disease using Machine Learning algorithms. Various medical attributes such as age, cholesterol level, blood pressure, chest pain type, and heart rate were used to train classification models.

The main objective of this project is to build an accurate model that can help in early heart disease prediction.

---

## Dataset Information

The dataset contains medical information of patients and includes features such as:

- Age
- Sex
- Chest Pain Type
- Resting Blood Pressure
- Cholesterol
- Fasting Blood Sugar
- Resting ECG
- Maximum Heart Rate
- Exercise Induced Angina
- Oldpeak
- Slope
- CA
- Thal
- Target

### Target Variable

- 0 → No Heart Disease
- 1 → Heart Disease

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

---

## Machine Learning Algorithms Used

- Logistic Regression
- Support Vector Classifier (SVC)
- Decision Tree Classifier
- Random Forest Classifier

---

## Data Preprocessing

The following preprocessing steps were performed:

- Data Cleaning
- Feature Selection
- Train Test Split
- Feature Scaling using StandardScaler

---

## Model Performance

| Model | Accuracy |
|---|---|
| Logistic Regression | 85.25% |
| SVC (Polynomial Kernel, degree=3) | 90% ✅ |
| Decision Tree | 83.60% |
| Random Forest | 83.60% |

---

## Best Model

The Support Vector Classifier (SVC) with:

```python
kernel='poly'
degree=3
```

achieved the highest accuracy of **90%**.

---

## Data Visualizations

The following visualizations were created:

- Correlation Heatmap
- Heart Disease Count Plot
- Age vs Heart Disease
- Chest Pain Type vs Heart Disease
- Cholesterol Distribution
- Confusion Matrix

---

## Conclusion

The tuned SVC model achieved the best performance and proved to be the most effective algorithm for heart disease prediction on this dataset.

---

## How to Run the Project

1. Clone the repository

```bash
git clone <your-repository-link>
```

2. Install required libraries

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

3. Run the notebook or Python file

---
