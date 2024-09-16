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
git clone https://github.com/your_username/your_repository.git
cd your_repository
Create and activate a virtual environment (optional but recommended):

bash

python -m venv venv
source venv/bin/activate         # On macOS/Linux
venv\Scripts\activate            # On Windows
Install dependencies:

## nstall the required libraries using requirements.txt:

bash

pip install -r requirements.txt
Ensure pre-trained models and scaler are in place:

Model/standardScalar.pkl: Pre-trained scaler for normalizing input data.
Model/modelForPrediction.pkl: Pre-trained logistic regression model for predicting diabetes.
Running the Application
To run the application locally, follow these steps:

Start the Flask app:

Run the following command in your terminal:

bash
Copy code
python app.py
Access the application:

Open your web browser and go to:

bash
Copy code
http://127.0.0.1:5000/
The application should be running, and you will see the home page with an input form for entering medical details.

How It Works
Input:
The user inputs values for the following medical parameters:

Pregnancies
Glucose Level
Blood Pressure
Skin Thickness
Insulin Level
BMI (Body Mass Index)
Diabetes Pedigree Function
Age
Scaling:
The input values are normalized using the pre-trained Standard Scaler to ensure consistency with the training data used in the model.

Prediction:
The scaled data is fed into the pre-trained Logistic Regression model, which predicts whether the user is Diabetic or Non-Diabetic.

Output:
The prediction result is displayed on the single_prediction.html page. The output can be one of two:

Diabetic
Non-Diabetic
Example Flow
Open the app in your browser.
Enter the medical data in the provided form.
Submit the form, and the app will predict whether the individual is diabetic or non-diabetic.
Acknowledgements
This project was made possible using the following technologies:

Flask: For creating the web application.
Scikit-learn: For training the logistic regression model and scaling the data.
Pickle: For saving and loading the machine learning model and scaler.
HTML/CSS: For building the web interface.
Feel free to fork, contribute, or raise issues in the repository if you would like to improve the project. Contributions are welcome!

markdown
Copy code

### Explanation of Each Section:

1. **Title and Overview**:
   - Explains what the project is and what it does, giving a brief description of the model and framework used.

2. **Project Structure**:
   - A tree diagram showing the project structure and where important files like the model and templates are located.

3. **Setup and Installation**:
   - Step-by-step instructions on how to set up the project, including cloning the repository, installing dependencies, and ensuring the models are in place.

4. **Running the Application**:
   - Instructions on how to run the Flask application locally, with the link to access it in a browser.

5. **How It Works**:
   - A detailed explanation of how the app processes the input, scales the data, runs the prediction, and displays the result.

6. **Example Flow**:
   - A simple example of how a user would interact with the web application.

7. **Acknowledgements**:
   - Recognizing the libraries and technologies that helped build the project.

You can replace placeholders like `your_username` and `your_repository` with your actual GitHub details when uploading. Let me know if you need any further customization!









