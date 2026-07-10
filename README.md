# Forecasting-National-Level-Self-Harm-Trends-Using-Machine-Learning-and-Social-Network-Signals
A Flask-based Machine Learning application that forecasts national-level self-harm trends using social network-derived mental health indicators, secure user authentication, and predictive analytics.
Overview

This project presents an intelligent machine learning system that predicts national-level self-harm trends by analyzing mental health indicators extracted from social network data. The application combines predictive analytics with a secure web interface to assist researchers, policymakers, and healthcare professionals in understanding potential self-harm patterns.

The project is implemented using Python, Flask, Machine Learning, and SQLite, providing an end-to-end solution from user authentication to prediction generation.

Features
Secure User Registration & Login
Machine Learning-based Self-Harm Trend Prediction
Dual Prediction Models
Interactive Flask Web Application
SQLite Database Integration
Input Validation & Authentication
Fast Prediction using Pre-trained Models
Simple and Responsive User Interface
Technology Stack
Frontend
HTML5
CSS3
JavaScript
Bootstrap
Backend
Python
Flask
Machine Learning
Scikit-learn
NumPy
Pandas
Joblib
Database
SQLite
Project Architecture
User
   │
   ▼
Login / Signup
   │
   ▼
Input Features
   │
   ▼
Flask Backend
   │
   ├── Model 1 (.sav)
   ├── Model 2 (.sav)
   │
   ▼
Prediction Engine
   │
   ▼
Prediction Results
Dataset

The project utilizes a social network mental health dataset inspired by research on forecasting self-harm trends using social media signals.

Dataset Source

https://github.com/krittintey/psimilan-fast

Folder Structure
Forecasting-Self-Harm-Trends/

│
├── app.py
├── signup.db
├── model.sav
├── model1.sav
├── templates/
├── static/
├── DatasetLink.txt
├── requirements.txt
├── README.md
└── LICENSE
Installation

Clone the repository

git clone(https://github.com/masood-pasha25/Forecasting-National-Level-Self-Harm-Trends-Using-Machine-Learning-and-Social-Network-Signals.git)
Move into the project

cd Forecasting-Self-Harm-Trends

Install dependencies

pip install -r requirements.txt

Run the application

python app.py

Open

http://127.0.0.1:5000
Modules
User Authentication
User Registration
Login
Validation
SQLite Database
Prediction Module
Accepts user input
Loads trained ML models
Generates prediction
Displays result instantly
Database Module
Stores registered users
Prevents duplicate usernames
Secure validation
Machine Learning

Algorithms Used

Scikit-learn Models
Pre-trained Regression/Prediction Models
Joblib Serialization

Libraries

NumPy
Pandas
Scikit-learn
Joblib
Future Enhancements
Deep Learning (LSTM)
Real-time Social Media Data Collection
Interactive Dashboard
Cloud Deployment
Email Alert System
API Integration
Visualization using Plotly
Research Motivation

Traditional self-harm monitoring systems rely on delayed reporting methods. This project leverages machine learning and social media-derived mental health indicators to support earlier detection of behavioral trends and enable proactive intervention strategies.

Results
Fast prediction using trained ML models
Secure web-based interface
Accurate preprocessing pipeline
User-friendly workflow
Modular architecture for future improvements
Author

MD Masood Pasha

Java Full Stack Developer | Data Engineer | Machine Learning Enthusiast

LinkedIn:
https://www.linkedin.com/in/masood-pasha

GitHub:
https://github.com/masood-pasha25

License

This project is developed for educational and research purposes.
