Chronic Kidney Disease Prediction System

A machine learning–based web application that predicts the presence of Chronic Kidney Disease (CKD) using clinical and medical parameters. The project demonstrates the complete pipeline from data preprocessing and model training to deployment using a Flask web application.

📌 Project Overview

Chronic Kidney Disease is a long-term medical condition that can lead to kidney failure if not detected early. This project leverages supervised machine learning algorithms to analyze patient health data and provide accurate predictions, helping in early diagnosis and decision support.

🎯 Objectives

Analyze and preprocess real-world medical data

Train and evaluate machine learning classification models

Save trained models for reuse

Deploy the model using a Flask web application

Demonstrate a real-world healthcare analytics use case

🧠 Technologies Used

Programming Language: Python

Machine Learning: Scikit-learn

Web Framework: Flask

Data Analysis: Pandas, NumPy

Model Serialization: Pickle / Joblib

Development Environment: Jupyter Notebook

📂 Project Structure
Chronic-kindney-predictor-/
│
├── .ipynb_checkpoints/                 # Jupyter notebook checkpoints
├── model/                              # Saved trained model(s)
├── Train, Testing, Saving Models Code.ipynb
├── kidney_disease.csv                  # Dataset
├── app.py                              # Flask application
├── requirements.txt                    # Project dependencies
└── README.md                           # Project documentation

📊 Dataset Description

The dataset (kidney_disease.csv) contains clinical and diagnostic features, including but not limited to:

Age

Blood Pressure

Specific Gravity

Albumin

Sugar

Hemoglobin

Serum Creatinine

Packed Cell Volume

Red Blood Cell Count

These features are used to classify whether a patient has Chronic Kidney Disease.

⚙️ System Workflow
1. Data Preprocessing

Handling missing values

Encoding categorical variables

Feature scaling and cleaning

2. Model Training

Training machine learning classification models

Evaluating performance using accuracy metrics

Saving the best-performing model

3. Model Deployment

Loading the trained model in Flask

Accepting user inputs via web interface

Returning prediction results in real time

🚀 Installation and Execution
Step 1: Clone the Repository
git clone https://github.com/Goofyparag/Chronic-kindney-predictor-.git
cd Chronic-kindney-predictor-

Step 2: Create a Virtual Environment (Recommended)
python -m venv venv
venv\Scripts\activate   # For Windows

Step 3: Install Dependencies
pip install -r requirements.txt

Step 4: Run the Application
python app.py


The application will run at:

http://127.0.0.1:5000/

🧪 Output

CKD Detected

No CKD Detected

The prediction is based on the input medical parameters provided by the user.

📌 Use Cases

College Mini / Major Project

Machine Learning Portfolio Project

Healthcare Analytics Demonstration

Flask + ML Deployment Example

⚠️ Disclaimer

This project is intended for educational purposes only.
It should not be used as a substitute for professional medical diagnosis or treatment.

👤 Author

Parag Tiwari
GitHub: https://github.com/Goofyparag

⭐ Acknowledgements

UCI Machine Learning Repository

Scikit-learn Documentation

Flask Documentation
