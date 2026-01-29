Chronic Kidney Disease Prediction System

A machine learning–based web application designed to predict Chronic Kidney Disease (CKD) using clinical and medical parameters. The system integrates data preprocessing, model training, and deployment through a Flask web interface.

📌 Project Description

Chronic Kidney Disease is a long-term condition that can lead to kidney failure if not detected early. This project applies supervised machine learning techniques to analyze patient medical data and predict the presence of CKD.

The application enables users to input clinical values and receive an instant prediction, demonstrating the practical use of machine learning in healthcare analytics.

🎯 Objectives

Analyze and preprocess real-world medical data

Train and evaluate machine learning classification models

Save and reuse trained models

Deploy the model using a Flask web application

Provide a simple and user-friendly prediction interface

🧠 Technologies Used

Programming Language: Python

Machine Learning: Scikit-learn

Web Framework: Flask

Data Analysis: Pandas, NumPy

Model Serialization: Joblib / Pickle

Development Tools: Jupyter Notebook

📂 Project Structure
Chronic-kindney-predictor-/
│
├── .ipynb_checkpoints/               # Jupyter checkpoints
├── model/                            # Saved trained model(s)
├── Train, Testing, Saving Models Code.ipynb
├── kidney_disease.csv                # Dataset
├── app.py                            # Flask application
├── requirements.txt                  # Project dependencies
└── README.md                         # Project documentation

📊 Dataset Information

The dataset (kidney_disease.csv) contains multiple clinical features such as:

Age

Blood Pressure

Specific Gravity

Albumin

Sugar

Hemoglobin

Serum Creatinine

Packed Cell Volume

Red Blood Cell Count

These features are used to classify whether a patient has Chronic Kidney Disease or not.

⚙️ Workflow

Data Preprocessing

Handling missing values

Encoding categorical features

Feature scaling

Model Training

Train machine learning classification models

Evaluate performance using accuracy metrics

Select and save the best-performing model

Model Deployment

Load the trained model in Flask

Accept user input through a web interface

Return prediction results in real time

🚀 Installation & Execution
Step 1: Clone the Repository
git clone https://github.com/Goofyparag/Chronic-kindney-predictor-.git
cd Chronic-kindney-predictor-

Step 2: Create Virtual Environment (Optional but Recommended)
python -m venv venv
venv\Scripts\activate   # Windows

Step 3: Install Dependencies
pip install -r requirements.txt

Step 4: Run the Application
python app.py


The application will run on:

http://127.0.0.1:5000/

🧪 Sample Output

Input: Patient medical parameters

Output:

CKD Detected

No CKD Detected

📌 Use Cases

Academic mini / major project

Machine learning portfolio project

Healthcare analytics demonstration

Flask + ML deployment example

⚠️ Disclaimer

This project is developed for educational purposes only.
It should not be used as a substitute for professional medical diagnosis or treatment.

👤 Author

Parag Tiwari
GitHub: https://github.com/Goofyparag

⭐ Acknowledgment

UCI Machine Learning Repository

Scikit-learn Documentation

Flask Documentation
