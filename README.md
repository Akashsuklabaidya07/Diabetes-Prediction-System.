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
├── application.py                               # Main Flask application script
├── requirements.txt                     # File containing the required Python packages
└── README.md                            # Project documentation

Installation
Clone the repository:

bash
Copy code
git clone https://github.com/your_username/your_repository.git
cd your_repository
Create and activate a virtual environment (optional but recommended):

bash
Copy code
python -m venv venv
source venv/bin/activate       # On macOS/Linux
venv\Scripts\activate          # On Windows
Install dependencies: All required packages are listed in the requirements.txt file. Install them using:

bash
Copy code
pip install -r requirements.txt
Ensure the Model folder contains the pre-trained model and scaler:

standardScalar.pkl: Used to scale the user input data.
modelForPrediction.pkl: The logistic regression model for predicting diabetes.
