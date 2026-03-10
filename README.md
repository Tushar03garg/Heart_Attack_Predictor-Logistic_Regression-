# Heart_Attack_Predictor-Logistic_Regression-
# Heart Attack Prediction using Logistic Regression

## Project Overview

This project predicts the **possibility of a heart attack** using a **Logistic Regression model** built with Python.
The model is trained on a dataset containing various medical attributes such as age, cholesterol level, blood pressure, and other clinical parameters.

The goal of this project is to demonstrate how **machine learning can assist in predicting heart disease risk** based on patient health data.

---

## Dataset

The dataset contains **303 patient records and 14 attributes** related to heart health.

### Features in the Dataset

| Feature  | Description                                |
| -------- | ------------------------------------------ |
| age      | Age of the patient                         |
| sex      | Gender (1 = male, 0 = female)              |
| cp       | Chest pain type                            |
| trestbps | Resting blood pressure                     |
| chol     | Serum cholesterol in mg/dl                 |
| fbs      | Fasting blood sugar (>120 mg/dl)           |
| restecg  | Resting electrocardiographic results       |
| thalach  | Maximum heart rate achieved                |
| exang    | Exercise induced angina                    |
| oldpeak  | ST depression induced by exercise          |
| slope    | Slope of peak exercise ST segment          |
| ca       | Number of major vessels                    |
| thal     | Thalassemia type                           |
| target   | Heart attack possibility (1 = Yes, 0 = No) |

---

## Technologies Used

* Python
* Pandas
* NumPy
* Scikit-learn
* Jupyter Notebook / Python Script

---

## Machine Learning Model

The model used in this project is:

**Logistic Regression**

Why Logistic Regression?

* Suitable for **binary classification problems**
* Efficient and interpretable model
* Works well with structured medical datasets

---

## Project Workflow

1. Import libraries
2. Load the dataset
3. Data preprocessing
4. Exploratory Data Analysis (EDA)
5. Feature selection
6. Train-test split
7. Train Logistic Regression model
8. Model evaluation
9. Prediction

---

## Model Evaluation

The model is evaluated using metrics such as:

* Accuracy Score
* Confusion Matrix
* Classification Report

These metrics help measure how well the model predicts heart attack risk.

---

## Installation

Clone the repository:

```bash
git clone https://github.com/your-username/heart-attack-prediction.git
```

Install required libraries:

```bash
pip install pandas numpy scikit-learn
```

Run the project:

```bash
python heart_prediction.py
```

---

## Example Prediction

The model takes patient medical attributes as input and predicts:

* **1 → High possibility of heart attack**
* **0 → Low possibility of heart attack**

---

## Project Structure

```
heart-attack-prediction
│
├── heart.csv
├── heart_prediction.py
├── notebook.ipynb
└── README.md
```

---

## Future Improvements

* Add more machine learning models (Random Forest, SVM, XGBoost)
* Improve model accuracy with feature engineering
* Deploy the model as a **web application**
* Create a **user interface for prediction**

---

## Author

Tushar Garg

GitHub: https://github.com/Tushar03garg
