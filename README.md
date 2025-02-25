# PredictEase

PredictEase is an advanced predictive analytics application designed to provide accurate predictions for various health conditions using machine learning models. This project integrates powerful prediction models in a user-friendly interface, making health assessments more accessible and reliable.

## Table of Contents

- [Features](#features)
- [Models Used](#models-used)
- [Installation](#installation)
- [Usage](#usage)
- [About Us](#about-us)
- [License](#license)

## Features

- **Diabetes Prediction**: Predicts the likelihood of diabetes based on input parameters such as glucose level, blood pressure, BMI, etc.
- **Heart Disease Prediction**: Uses logistic regression to predict the presence of heart disease using various health metrics.
- **Parkinson's Disease Prediction**: Utilizes XGBoost to assess the likelihood of Parkinson's disease based on voice and speech characteristics.

## Models Used

- **Diabetes Model**: SVM model trained on diabetes-related health data.
- **Heart Disease Model**: Logistic Regression model trained on heart disease datasets.
- **Parkinson's Model**: XGBoost model trained on voice and speech features related to Parkinson's disease.

## Installation

1. **Clone the repository:**

   ```bash
   git clone https://github.com/your-username/PredictEase.git
   cd PredictEase
   ```

2. **Install dependencies:**

   Make sure you have Python 3.8+ installed. Install the required Python packages using pip:

   ```bash
   pip install -r requirements.txt
   ```

3. **Run the application:**

   ```bash
   streamlit run app.py
   ```

   The application will launch in your default web browser.

## Usage

- Select the prediction type (Diabetes, Heart Disease, or Parkinson's) from the sidebar menu.
- Enter the required input parameters.
- Click on the respective button to see the prediction result.
- For more details about the project and its creators, click on the "About Us" section in the sidebar.

## About Us

PredictEase was developed as a project for Vellore Institute of Technology (VIT) by:
- Shubham Nijhawan
- Manit Gera
- Aditya Aryan

## Link of the web app
https://predictease1.streamlit.app/



