# Employee-Attrition-Detection
Employee Attrition Prediction

Project Overview

This project aims to predict employee attrition using machine learning techniques. The system takes employee details as input and provides a prediction on whether an employee is likely to leave the organization. It also visualizes key factors influencing attrition, helping HR teams make informed decisions.

Features

Real-time Attrition Prediction: Enter employee details to get instant attrition predictions.

Data Visualization: Charts and insights to understand attrition trends.

User-Friendly Web Interface: Simple and intuitive design for easy navigation.

Machine Learning Model: Utilizes a trained Random Forest model for predictions.

Flask-Based Web Application: Accessible via a web browser.

Cloud Deployment: Can be deployed on platforms like Heroku for scalability.

Technologies Used

Programming Language: Python

Web Framework: Flask

Machine Learning Model: Random Forest

Frontend: HTML, CSS, JavaScript

Visualization: Matplotlib, Seaborn

Deployment: Flask, GitHub, Heroku

Installation Guide

Prerequisites

Python 3.7+

Flask

Pandas

Scikit-learn

Matplotlib

Seaborn

Pickle

Steps to Run Locally

Clone the repository:

git clone https://github.com/yourusername/attrition-predictor.git
cd attrition-predictor

Create and activate a virtual environment:

python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate

Install dependencies:

pip install -r requirements.txt

Run the Flask application:

python app.py

Open the browser and visit:

http://127.0.0.1:5000

Usage

Open the application in your browser.

Enter employee details such as age, education, job role, etc.

Click the Predict button to get an attrition prediction.

View the results and insights on the dashboard.

Project Structure

├── ml_models/
│   ├── final_model.py
│   ├── attrition_prediction_model.bin
├── static/
│   ├── css/
│   ├── js/
├── templates/
│   ├── index.html
│   ├── form.html
├── app.py
├── requirements.txt
├── README.md

Future Enhancements

Improve model accuracy with advanced ML techniques.

Add more features for deeper HR analytics.

Implement a secure login system for user access.

License

This project is open-source and available under the MIT License.

Contact

For any queries or contributions, feel free to reach out via GitHub Issues.

