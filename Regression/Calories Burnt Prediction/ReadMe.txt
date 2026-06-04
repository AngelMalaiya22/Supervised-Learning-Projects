# Calories Burnt Prediction using Machine Learning

## Project Overview
This project focuses on predicting the number of calories burnt during exercise using Machine Learning algorithms. The dataset contains various health and physical activity related features such as age, gender, height, weight, exercise duration, heart rate, and body temperature.

Different regression models were trained and compared to identify the best performing algorithm for calorie prediction.

---

# Dataset Information

The dataset contains the following features:

| Feature | Description |
|---|---|
| User_ID | Unique ID of user |
| Gender | Male/Female |
| Age | Age of person |
| Height | Height of person |
| Weight | Weight of person |
| Duration | Exercise duration |
| Heart_Rate | Heart rate during exercise |
| Body_Temp | Body temperature |
| Calories | Calories burnt (Target Variable) |

---

# Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

---

# Machine Learning Algorithms Used

1. Linear Regression
2. Support Vector Regressor (SVR)
3. Decision Tree Regressor
4. Random Forest Regressor

---

# Data Preprocessing

The following preprocessing steps were performed:

- Removed unnecessary columns
- Encoded categorical data
- Checked missing values
- Split dataset into training and testing sets

---

# Evaluation Metrics

The models were evaluated using:

- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)
- R² Score

---

# Model Performance

## Linear Regression
- MAE : 8.44
- MSE : 132.06
- R² Score : 0.9657

## Support Vector Regressor
- MAE : 3.03
- MSE : 41.77
- R² Score : 0.9885

## Decision Tree Regressor
- MAE : 3.62
- MSE : 31.62
- R² Score : 0.9921

## Random Forest Regressor
- MAE : 1.81
- MSE : 8.00
- R² Score : 0.9979

---

# Data Visualizations

The following visualizations were created in this project:

- Correlation Heatmap
- Calories Burnt vs Duration
- Calories Burnt vs Heart Rate
- Distribution Plot of Calories
- Actual vs Predicted Calories
- Feature Importance Graph

---

# Conclusion

The Calories Burnt Prediction project was successfully implemented using multiple Machine Learning regression algorithms. After comparing all models, the Random Forest Regressor achieved the best performance with the highest accuracy and lowest prediction error.

The Actual vs Predicted graph showed that the predicted values were very close to the actual values, indicating excellent model performance and strong prediction capability.

This project demonstrates how Machine Learning can be effectively used in health and fitness applications to estimate calories burnt based on physical and physiological parameters.

---

# Future Improvements

- Deploy the model using Flask or Streamlit
- Build a fitness recommendation system
- Use Deep Learning models for improved prediction
- Create a real-time calorie prediction web app

---

# How to Run the Project

```bash
# Clone the repository
git clone <your-repository-link>

# Install required libraries
pip install -r requirements.txt

# Run the notebook
jupyter notebook