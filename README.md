# Diabetes Detector

## Overview
The Diabetes Detector is a web-based application that predicts the likelihood of diabetes based on user input. It uses a machine learning model trained on the Pima Indians Diabetes Dataset to provide predictions. The project leverages Flask for the backend, HTML for the frontend, and Python for data processing and machine learning.

---

## Features
- **Machine Learning Model**: Logistic Regression for binary classification.
- **Web Application**: Built using Flask with an intuitive user interface for data input and results display.
- **Data Visualization**: Insights and exploration of the dataset visualized with Seaborn and Matplotlib.
- **Feature Scaling**: StandardScaler to preprocess the input data for better model performance.
- **Custom Predictions**: Users can input their health metrics to get real-time predictions on diabetes likelihood.

---

## How It Works
1. **User Input**: Users input their health metrics (e.g., glucose level, BMI, insulin level, etc.) on the homepage.
2. **Data Preprocessing**: The application preprocesses the data by scaling features using StandardScaler.
3. **Prediction**: The trained Logistic Regression model predicts whether the user is likely to have diabetes.
4. **Results Display**: The prediction is displayed on a result page, along with a message explaining the likelihood.

---

## Dataset
- **Source**: [Pima Indians Diabetes Dataset](https://raw.githubusercontent.com/jbrownlee/Datasets/master/pima-indians-diabetes.data.csv)
- **Features**:
  - Pregnancies
  - Glucose
  - BloodPressure
  - SkinThickness
  - Insulin
  - BMI
  - DiabetesPedigreeFunction
  - Age
  - Outcome (0 = No Diabetes, 1 = Diabetes)
  
The dataset includes 768 entries, each representing a patient's medical records and diabetes diagnosis.

---

## Technology Stack
- **Backend**: Flask
- **Frontend**: HTML, CSS, Bootstrap (optional for styling)
- **Machine Learning**: Scikit-learn for model training and prediction
- **Data Handling**: Pandas and NumPy
- **Data Visualization**: Seaborn and Matplotlib for exploratory data analysis (EDA)

---

## Installation

### Prerequisites
- Python 3.8 or higher
- Pip package manager

### Steps
1. Clone the repository:
   ```bash
   git clone[ repository-url>](https://github.com/joyo11/diabetesdetector)
   python app.py
