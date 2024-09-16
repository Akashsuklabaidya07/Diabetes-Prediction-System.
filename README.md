# Diabetes Prediction System
## Overview
This project is a web application that predicts whether a person has diabetes based on medical inputs. The machine learning model used in this project is **Logistic Regression**. The web app is built using **Flask**, and it allows users to input several medical parameters such as glucose levels, blood pressure, and age to predict whether the person is diabetic or not.

## Project Structure

Here is the project structure with a tree diagram:

```bash
├── Model/                               # Directory containing pre-trained model and scaler
│   ├── standardScalar.pkl               # Scaler for data normalization
│   └── modelForPrediction.pkl           # Trained logistic regression model
├── templates/                           # HTML templates for the web application
│   ├── index.html                       # Landing page for the web app
│   ├── single_prediction.html           # Page to display the prediction result
│   └── home.html                        # Form page for user input
├── app.py                               # Main Flask application script
├── requirements.txt                     # File containing the required Python packages
└── README.md                            # Project documentation

