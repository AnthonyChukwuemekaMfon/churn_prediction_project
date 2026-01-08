# Customer Churn Prediction

A machine learning project focused on predicting customer churn using Python and scikit-learn. This project demonstrates key AI and data science skills, including data preprocessing, model training, and deployment-ready prediction logic.

## Project Overview

The goal of this project is to predict which customers are likely to leave (churn) a service based on historical behavior and demographic data. The project covers the end-to-end machine learning workflow and is designed to showcase skills relevant for a Junior AI Engineer internship.

## Dataset

The dataset contains features such as:

- Customer demographics (age, gender, location)  
- Account information (subscription plan, tenure)  
- Service usage patterns  
- Target variable: `Churn` (Yes/No)

## Project Structure

- `churn_data.csv` – Dataset used for training and evaluation  
- `churn_model.ipynb` – Data exploration, preprocessing, and model development  
- `churn_model.pkl` – Saved trained machine learning model  
- `churn_app.py` – Script/application for making predictions  
- `requirements.txt` – Python dependencies  

## Tools & Technologies

- Python  
- Pandas  
- NumPy  
- Scikit-learn  

## Machine Learning Workflow

1. Load and clean the dataset  
2. Encode categorical features and scale numerical features  
3. Train a classification model (e.g., Logistic Regression, Random Forest)  
4. Evaluate model performance using accuracy, precision, recall, and F1-score  
5. Save the trained model for reuse  
6. Use the model to generate predictions for new data via a Python script

## Installation

Clone the repository:

```bash
git clone https://github.com/AnthonyChukwuemekaMfon/churn-prediction.git
cd churn-prediction
