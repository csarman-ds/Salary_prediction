# 💼 Salary Prediction using Machine Learning

## 📌 Project Overview

This project predicts an employee's **Salary** based on their **Years of Experience** using a Machine Learning algorithm.

---

## 🎯 Objective

Build a machine learning model that predicts salary from years of experience.

---

## 📂 Dataset

Dataset Name: Salary_Data.csv

Features:
- YearsExperience

Target:
- Salary

Number of Records:
- 30

---

## 🛠️ Technologies Used

- Python
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn
- Joblib

---

## 🤖 Machine Learning Algorithm

- Linear Regression

---

## 📊 Project Workflow

1. Import Libraries
2. Load Dataset
3. Explore Dataset
4. Check Missing Values
5. Visualize Data
6. Select Features (X) and Target (y)
7. Split Dataset into Training and Testing Sets
8. Train Linear Regression Model
9. Make Predictions
10. Evaluate the Model
11. Save the Trained Model

---

## 📈 Model Performance

- MAE: 6286.45
- MSE: 4983096.86
- R² Score: 0.9024

---

## 📉 Data Visualization

- Scatter Plot (Years of Experience vs Salary)
- Regression Line

---

## 📁 Project Structure

```
Salary_Prediction/
│
├── Salary_Data.csv
├── salary_prediction.ipynb
├── salary_model.pkl
├── README.md
└── requirements.txt
```

---

## 💾 Save Model

```python
import joblib

joblib.dump(model, "salary_model.pkl")
```

---

## 📥 Load Saved Model

```python
import joblib

model = joblib.load("salary_model.pkl")
```

---

## 🔮 Example Prediction

Input:

```
Years of Experience = 7
```

Output:

```
Predicted Salary = 91288.29
```

---

## 📚 Libraries Required

```
pandas
numpy
matplotlib
seaborn
scikit-learn
joblib
```

---

## 🚀 Future Improvements

- Compare multiple regression models (Linear Regression, Decision Tree Regressor, Random Forest Regressor).
- Perform hyperparameter tuning.
- Build a Streamlit web application.
- Deploy the model online.

---

## 👨‍💻 Author

**Arman**

B.Sc. Data Science Student

Project: Salary Prediction using Machine Learning