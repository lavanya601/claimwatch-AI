# Insurance Fraud Detection System
An AI-based web application that predicts whether an insurance claim is fraudulent or not using Machine Learning.
##  Project Overview
Insurance fraud causes major financial losses to companies.  
This project uses a Machine Learning model to analyze claim details and predict fraud risk.
The system includes:
- Frontend (User Interface using Gradio)
- Backend (Machine Learning model using Scikit-learn)
- Hosted using Google Colab
##  Features
- Predicts fraud risk instantly
- User-friendly web interface
- Takes claim details as input
- Displays fraud risk result (Low / High)
- Simple and lightweight model
##  Technology Stack
- Python
- Scikit-learn
- Pandas
- NumPy
- Gradio
- Google Colab
## Input Parameters

The system takes the following inputs:

- Claim Amount
- Annual Income
- Number of Previous Claims
##  Machine Learning Model

- Logistic Regression
- Binary Classification (Fraud / Not Fraud)
- Supervised Learning
- ## Project Architecture

User Input → Gradio Frontend → ML Model → Prediction Output

##  Project Structure

insurance-fraud-detection/
│
├── fraud_detection.ipynb
├── README.md
└── requirements.txt

## How to Run the Project

1. Open the notebook in Google Colab
2. Install required libraries
3. Run all cells
4. Launch Gradio interface
5. Enter input values
6. Click Submit to see prediction

##  Future Improvements

- Add real dataset
- Improve model accuracy
- Deploy on cloud (Render / Heroku)
- Add user authentication
- Add dashboard analytics

