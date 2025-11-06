## 🏦 Loan Approval Prediction System
📘 Overview

The Loan Approval Prediction System predicts whether a loan application will be approved or rejected based on user input.
It uses a Random Forest Classifier trained on loan applicant data and provides the result with a confidence score through a Flask web interface.

🚀 Features

Predicts Loan Approval Status (Approved / Rejected)

Displays Confidence Score (%)

Responsive web interface with dropdowns and form validation

Uses preprocessing + model pipeline for clean predictions

🧠 Machine Learning Model

Algorithm: Random Forest Classifier

Libraries: scikit-learn, pandas, numpy, joblib

Programming Language: Python
Libraries: scikit-learn, pandas, numpy, joblib, Flask

Dataset File:

loan_prediction/loan.csv

🧩 Project Structure
loan_prediction/
│
├── app.py                     # Flask backend
├── loan_pipeline.pkl          # Trained Random Forest pipeline
├── templates/
│   └── index.html             # HTML UI
├── static/
│   └── css/
│       └── style.css          # Styling
├── loan_train.py              # Model training script
└── README.md
UI Screenshot Path:

loan_prediction/static
/loan ui.png


(Example Screenshot)
⚙️ How It Works

User enters input data (Gender, Income, Credit History, etc.).

The Flask backend sends data to the trained Random Forest model.

The model predicts Approved / Rejected.

Result and probability are displayed instantly on the webpage
Insights / Outcomes

Automated loan decision-making using ML.

Improved model accuracy via Random Forest Classifier.

Fully functional end-to-end deployment using Flask.
## Wine Type Prediction System
📘 Overview

The Wine Type Prediction System predicts whether a wine is Red or White using physicochemical characteristics such as acidity, pH, sulphates, and alcohol content.
It’s powered by a Random Forest Classifier trained on the UCI Wine Quality Dataset.

🚀 Features

Predicts Wine Type: 🍷 Red Wine or 🥂 White Wine

Flask-based web app for real-time prediction

Uses trained scaler.pkl for data normalization

Simple and clean HTML interface

🧠 Machine Learning Model

Algorithm: Random Forest Classifier

Dataset: UCI Wine Quality Dataset

Libraries: scikit-learn, pandas, numpy, pickle

Language: Python

🧩 Project Structure
wine_prediction/
│
├── app.py                     # Flask backend
├── wine_model.pkl             # Trained model
├── scaler.pkl                 # Trained StandardScaler
├── templates/
│   └── index.html             # Input form
├── static/
│   └── css/
│       └── style.css          # Styling
├── train_wine_model.ipynb     # Model training notebook
└── README.md

⚙️ How It Works

User enters 11 physicochemical features:

Fixed Acidity

Volatile Acidity

Citric Acid

Residual Sugar

Chlorides

Free Sulfur Dioxide

Total Sulfur Dioxide

Density

pH

Sulphates

Alcohol

Data is scaled using scaler.pkl.

Random Forest model predicts Red (0) or White (1).

Example Output:

🍷 Red Wine

📈 Insights / Outcomes

High accuracy classification of wine type using Random Forest.

Demonstrated full ML pipeline with deployment.

Real-time prediction with Flask web interface.



