# Credit Card Detection Web Application with Django

## Overview
This project is a **web-based system** built with **Django** to detect credit card numbers from data records using **data processing** techniques. The application processes a dataset (e.g., CSV or Excel file), detects credit card numbers, validates them, and provides results in real-time. The system ensures secure handling of sensitive data while providing a user-friendly interface for interacting with the dataset.

## Features
- **Data Upload & Processing**: Users can upload a dataset (CSV/Excel) containing records with credit card data.
- **Credit Card Detection**: The system extracts credit card numbers from the dataset based on predefined patterns or rules.
- **Credit Card Validation**: Validates the detected credit card numbers using **Luhn’s Algorithm**, which is commonly used for card number validation.
- **Secure Data Handling**: The system is built with a focus on security, ensuring that sensitive information is processed correctly and not stored unnecessarily.
- **Web Interface**: A clean and responsive Django web interface that allows users to interact with the dataset easily.

## Tech Stack
- **Python**: The programming language used to implement the backend logic and validation.
- **Django**: Web framework that powers both the frontend and backend of the application.
- **Pandas**: For processing and manipulating the dataset (CSV, Excel files).
- **Scikit-learn** (optional): For implementing machine learning models or additional data processing (if applicable).
- **SQLite/PostgreSQL**: Database management system for storing the uploaded data (optional).
- **Bootstrap**: Used for front-end design to create a responsive and user-friendly interface.

Dataset Link :- https://www.kaggle.com/mlg-ulb/creditcardfraud

First Create virtualenvironment with following COMMAND:-

virtualenv venv
NOTE:- venv is name of name of virtualenvironment. we can give any name which we want.

Then Activate venv:-

 venv\Scripts\activate
Then Install requirements.txt with following COMMAND:-

 pip install -r requirements.txt
create superuser by following COMMAND in your root directory:-

python manage.py createsuperuser
Then start your server by typing following COMMAND:-

python manage.py runserver
NOTE:- If you are adding some model in models.py or changing something don't forget to make migrations

python manage.py makemigrations
and migrate it to database

python manage.py migrate
