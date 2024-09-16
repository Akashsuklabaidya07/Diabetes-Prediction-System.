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
git clone https://github.com/Akashsuklabaidya07/https://github.com/Akashsuklabaidya07/Diabetes-Prediction-System..git<br>
cd https://github.com/Akashsuklabaidya07/Diabetes-Prediction-System..git<br>

Install dependencies:

Install the required libraries using requirements.txt:
pip install -r requirements.txt

Ensure pre-trained models and scaler are in place:

Model/standardScalar.pkl: Pre-trained scaler for normalizing input data.
Model/modelForPrediction.pkl: Pre-trained logistic regression model for predicting diabetes.

Running the Application
To run the application locally, follow these steps:

Start the Flask app:

Run the following command in your terminal:
python app.py


Access the application:

Open your web browser and go to:http://127.0.0.1:5000/

## How It Works
### Input:
The user inputs values for the following medical parameters:

Pregnancies
Glucose Level
Blood Pressure
Skin Thickness
Insulin Level
BMI (Body Mass Index)
Diabetes Pedigree Function
Age
### Scaling:
The input values are normalized using the pre-trained Standard Scaler to ensure consistency with the training data used in the model.

### Prediction:
The scaled data is fed into the pre-trained Logistic Regression model, which predicts whether the user is Diabetic or Non-Diabetic.

### Output:
The prediction result is displayed on the single_prediction.html page. The output can be one of two:

Diabetic
Non-Diabeti

## Example Flow
Open the app in your browser.
Enter the medical data in the provided form.
Submit the form, and the app will predict whether the individual is diabetic or non-diabetic.

## License
This project is licensed under the MIT License - see the LICENSE file for details.

## Acknowledgements
This project was developed as a part of my machine learning journey, with a focus on data preprocessing, logistic regression, and Flask web application development. Special thanks to open-source libraries and resources for their contributions.

This readme provides a clear and structured guide to set up and use of this project. If you have any questions, feedback, or issues, please feel free to contact at akashsuklabaidya@gamil.com






