🏦 Loan Approval Prediction System

### 📘 Overview
The **Loan Approval Prediction System** predicts whether a loan application will be **Approved ✅** or **Rejected ❌** based on applicant and financial data.  
It uses a **Random Forest Classifier** trained on a structured dataset of loan applicants.

---

### 🚀 Features
- Predicts **Loan Status:** Approved / Rejected  
- Displays **Prediction Confidence (%)**  
- Fully responsive web UI using Flask + HTML/CSS  
- Integrated **Machine Learning pipeline**

---

### 🧠 Model Details
- **Algorithm:** Random Forest Classifier  
- **Language:** Python  
- **Libraries:** `scikit-learn`, `pandas`, `numpy`, `joblib`, `Flask`  
- **Dataset Path:**

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

---

### ⚙️ How It Works
1. User inputs applicant details (Gender, Income, Loan Amount, etc.).
2. Flask sends input to the trained Random Forest model.
3. The model predicts:
   - ✅ **Loan Approved**
   - ❌ **Loan Rejected**
4. The prediction and confidence score are displayed on the webpage.

---

### 🌐 Output Screenshot
**Local Flask URL:** [http://127.0.0.1:5000/predict](http://127.0.0.1:5000/predict)

📸 **UI Screenshot:**
<img src="loan_prediction/static/loan ui.png" width="700">

**Example Output:**

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

📸 **UI Screenshot:**
<img src="wine_quality/static" width="700">
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



