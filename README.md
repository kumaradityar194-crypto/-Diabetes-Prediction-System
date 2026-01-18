# Diabetes Prediction System

A machine learning–based diabetes prediction system in Python.  
The application preprocesses medical input data, applies scaling and a classification model, and predicts whether a person has diabetes.

## 📌 Overview

This project uses the PIMA Indians diabetes dataset to train a classification model.  
It includes data analysis, preprocessing, feature scaling, and prediction logic.

## 📊 Model Performance

- Data preprocessing with **StandardScaler**
- Trained using machine learning models
- Achieved **~81% accuracy** on test data

## 📁 Dataset

The dataset includes diagnostic measurements such as:
- Pregnancies
- Glucose
- BloodPressure
- SkinThickness
- Insulin
- BMI
- DiabetesPedigreeFunction
- Age  
Target column: `Outcome`

## 🧠 How It Works

1. Load and explore the diabetes dataset  
2. Handle class imbalance and scale features  
3. Train a classification model  
4. Predict output for user input

## 🚀 Usage

1. Place `diabetes.csv` in the project folder  
2. Run the Python script:

```bash
python daibtes_app.py
