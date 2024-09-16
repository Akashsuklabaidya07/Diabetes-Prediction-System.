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
├── application.py                       # Main Flask application script
├── requirements.txt                     # Python dependencies for the project
└── README.md                            # Project documentation
```


## Setup

### Prerequisites
- Python 3.8
- Flask
- Pandas
- NumPy
- Scikit-Learn
- PyMongo
- MongoDB

### Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/Akashsuklabaidya07/Dibetes-Prediction-System.git
    cd Dibetes-Prediction-System
    ``` 

2. Install the dependencies:
    ```bash
    pip install -r requirements.txt
    ```

### Run the application

1. Start the Flask Application:
    ```bash
    python application.py
    ```

2. Access the Application:
    Open a web browser and navigate to `http://127.0.0.1:5000` to access the application.

## How It Works

### Data Preparation:
- The dataset `diabetes2.csv` is loaded and preprocessed.
- Missing values are replaced with the mean of the respective columns.

### Model Training:
- The data is split into training and testing sets.
- Features are standardized using `StandardScaler`.
- A Logistic Regression model is trained on the standardized training data.
- The trained model and scaler are saved using pickle.

### Web Application:
- The Flask application serves a web form where users can input their health parameters.
- The input data is standardized using the pre-trained scaler.
- The standardized data is fed into the Logistic Regression model to make predictions.
- The results and user data are stored in a MongoDB database.

## License
This project is licensed under the MIT License.

## Acknowledgements
- The dataset used for training is from Kaggle.
- The project is built using Flask and Scikit-Learn.
- Pickle for saving and loading the machine learning model and scaler.
- HTML/CSS for building the web interface.

## Contact
If you have any questions, feedback, or issues, please feel free to contact at: **akashsuklabaidya780@gamil.com**.

   





