# 🩺 Diabetes Prediction using Machine Learning

This project focuses on predicting whether a person is diabetic or non-diabetic using various Machine Learning classification algorithms. The dataset contains several medical attributes such as Glucose level, BMI, Age, Insulin, Blood Pressure, etc. Different models were trained and evaluated to determine the best-performing algorithm for diabetes prediction.

---

# 📌 Project Objective

The main objective of this project is to build a Machine Learning model that can accurately predict diabetes based on medical and health-related features.

---

# 📂 Dataset Information

| Feature | Description |
|---|---|
| Pregnancies | Number of pregnancies |
| Glucose | Glucose level |
| BloodPressure | Blood pressure value |
| SkinThickness | Skin fold thickness |
| Insulin | Insulin level |
| BMI | Body Mass Index |
| DiabetesPedigreeFunction | Diabetes hereditary function |
| Age | Age of the patient |
| Outcome | 0 = Non-Diabetic, 1 = Diabetic |

---

# 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

---

# 🤖 Machine Learning Algorithms Used

- Logistic Regression
- K-Nearest Neighbors (KNN)
- Support Vector Classifier (SVC)
- Decision Tree Classifier
- Random Forest Classifier

---

# 📊 Data Visualization

The following visualizations were used in this project:

- Correlation Heatmap
- Confusion Matrix
- Outcome Distribution Countplot
- Glucose Distribution Plot
- BMI vs Glucose Scatter Plot
- Accuracy Comparison Bar Chart
- Feature Importance Graph

---

# 📈 Model Performance

| Model | Accuracy |
|---|---|
| Logistic Regression | 75.32% |
| KNN | 68.83% |
| Support Vector Classifier | 72.72% |
| Decision Tree | 74.02% |
| Random Forest | 72.72% |

---

# ✅ Best Performing Model

Logistic Regression achieved the highest accuracy of **75.32%**, making it the best-performing model for this dataset.

---

# 📌 Conclusion

Different Machine Learning classification algorithms were implemented and evaluated for diabetes prediction. Among all models, Logistic Regression performed the best with an accuracy of 75.32%. The project demonstrates how Machine Learning can be effectively used in healthcare systems for early diabetes prediction and medical analysis.

---

# 🚀 Future Improvements

- Hyperparameter tuning
- Cross-validation
- Deep Learning implementation
- Deployment using Flask or Streamlit
- Real-time prediction system

---

# ▶️ How to Run the Project

```bash
# Clone the repository
git clone <your-repository-link>

# Install required libraries
pip install pandas numpy matplotlib seaborn scikit-learn

# Run the notebook
jupyter notebook