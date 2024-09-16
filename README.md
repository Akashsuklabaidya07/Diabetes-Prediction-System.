# Diabetes Prediction System

## Overview
The **Diabetes Prediction System** is a web-based application built using **Flask** that predicts whether a person is diabetic or not based on medical inputs. It uses a machine learning model trained with the **Logistic Regression** algorithm. The application allows users to input parameters such as glucose level, blood pressure, insulin level, and BMI, and it returns a prediction of either **Diabetic** or **Non-Diabetic**.

This project aims to provide a simple, user-friendly tool that can assist in the early detection of diabetes by leveraging machine learning.

## Project Structure
The project has the following structure:

```bash
├── Model/                               # Directory containing pre-trained model and scaler
│   ├── standardScalar.pkl               # Pre-trained scaler to normalize input data
│   └── modelForPrediction.pkl           # Pre-trained logistic regression model
├── templates/                           # HTML templates for the web pages
│   ├── index.html                       # Home page
│   ├── single_prediction.html           # Page to show prediction results
│   └── home.html                        # Form for inputting medical data
├── app.py                               # Main Flask application script
├── requirements.txt                     # Python dependencies for the project
└── README.md                            # Project documentation
```
## Setup and Installation
Prerequisites
Ensure you have Python 3.x installed on your system. Additionally, you will need to install the following libraries:

Flask<br>
Numpy<br>
Pandas<br>
Scikit-learn<br>
Pickle

## Installation Steps
Clone the repository:

Open a terminal and run:

bash
Copy code
git clone https://github.com/Akashsuklabaidya07/https://github.com/Akashsuklabaidya07/Diabetes-Prediction-System..git
cd https://github.com/Akashsuklabaidya07/Diabetes-Prediction-System..git







