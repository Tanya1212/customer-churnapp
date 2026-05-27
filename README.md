# Customer Churn Prediction App

A machine learning and Streamlit web application that predicts whether a customer is likely to churn based on their account and service details.

## Overview

Customer churn is a major problem for businesses because losing customers affects growth and revenue. This project uses a machine learning model to estimate churn risk and provides a simple web interface for real time prediction.

This is my personal version of the project, customized and maintained by Tanya Chugh.

## Problem Statement

The goal of this project is to predict whether a customer will leave a service based on features such as contract type, tenure, monthly charges, and service usage. Businesses can use churn predictions to identify at-risk customers and improve retention strategies.

## Dataset

This project uses the **Telco Customer Churn** dataset.

- Target column: `Churn`
- Type of problem: Binary classification
- Input features include customer demographics, account information, internet service details, billing details, and contract type

## Features

- Predicts customer churn in real time.
- Simple and interactive Streamlit interface.
- Uses a trained machine learning model.
- Helps identify customers at risk of leaving.
- Easy to run locally and deploy online.

## Tech Stack

- Python
- Pandas
- NumPy
- Scikit-learn
- Streamlit
- Joblib
- Matplotlib / Seaborn
- Docker

## Project Structure

```text
customer-churnapp/
├── data/
├── model/
├── notebooks/
├── streamapp.py
├── train.py
├── requirements.txt
├── Pipfile
├── Dockerfile
└── README.md
```

## How It Works

1. The dataset is cleaned and preprocessed.
2. Categorical values are encoded.
3. A classification model is trained on churn data.
4. The trained model is saved.
5. Streamlit collects user input.
6. The app predicts whether a customer is likely to churn.

## How to Run Locally

### 1. Clone the repository

```bash
git clone https://github.com/your-username/customer-churnapp.git
cd customer-churnapp
```

### 2. Install dependencies

If you are using `requirements.txt`:

```bash
pip install -r requirements.txt
```

If you are using `Pipfile`:

```bash
pipenv install
pipenv shell
```

### 3. Run the app

```bash
streamlit run streamapp.py
```

## Deployment

After deploying the app, add your live link here:

**Live App:** https://your-app-link-here

## Model Evaluation

Model performance can be added here after training.

Example:
- Accuracy: XX%
- Precision: XX%
- Recall: XX%
- F1 Score: XX%
- ROC-AUC: XX%

## Future Improvements

- Try multiple models and compare performance.
- Add feature importance visualization.
- Improve the UI design.
- Add explanation for each prediction.
- Deploy with better monitoring.

## What I Learned

- Data cleaning and preprocessing.
- Handling categorical data.
- Building a classification model.
- Creating a real-time ML app with Streamlit.
- Deploying a project using GitHub and Docker.

## Author

**Tanya Chugh**

## Acknowledgements

- Telco Customer Churn dataset.
- Streamlit documentation.
- Scikit-learn documentation.
