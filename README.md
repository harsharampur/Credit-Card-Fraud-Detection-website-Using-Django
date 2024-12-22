
# Credit Card Detection Web Application with Django

## Overview
This project is a **web-based system** built with **Django** to detect credit card numbers from data records using **data processing** techniques. The application processes a dataset (e.g., CSV or Excel file), detects credit card numbers, validates them, and provides results in real-time. The system ensures secure handling of sensitive data while providing a user-friendly interface for interacting with the dataset.

The dataset used for this project is from [Kaggle: Credit Card Fraud Detection](https://www.kaggle.com/mlg-ulb/creditcardfraud).

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

## Installation

Follow the steps below to get your local environment set up:

### 1. Clone the repository:
```bash
git clone https://github.com/yourusername/CreditCardDetection.git
```

### 2. Navigate into the project directory:
```bash
cd CreditCardDetection
```

### 3. Create a virtual environment:
Create a virtual environment to keep your dependencies isolated:
```bash
virtualenv venv
```
**NOTE**: You can give the virtual environment any name (e.g., `venv`, `env`, etc.).

### 4. Activate the virtual environment:
- **Windows**:
  ```bash
  venv\Scripts\activate
  ```
- **Linux/Mac**:
  ```bash
  source venv/bin/activate
  ```

### 5. Install the required dependencies:
Use the following command to install all the necessary Python packages listed in `requirements.txt`:
```bash
pip install -r requirements.txt
```

### 6. Install additional dependencies for data handling:
Install **Pandas** (for dataset processing) and **Openpyxl** (for reading Excel files):
```bash
pip install pandas openpyxl
```

### 7. Create a Django superuser:
To access the Django admin interface, create a superuser account:
```bash
python manage.py createsuperuser
```

### 8. Apply migrations (if using a database):
If your project uses a database (like SQLite or PostgreSQL), run the following to apply database migrations:
```bash
python manage.py makemigrations
python manage.py migrate
```

### 9. Start the Django development server:
Run the development server to test the application:
```bash
python manage.py runserver
```

### 10. Open the web application:
Visit [http://127.0.0.1:8000](http://127.0.0.1:8000) in your web browser.

## Dataset
The dataset used in this project is the [Credit Card Fraud Detection dataset from Kaggle](https://www.kaggle.com/mlg-ulb/creditcardfraud), which contains anonymized credit card transactions labeled with either 'fraudulent' or 'non-fraudulent'.

## Usage
1. Open the web app in your browser.
2. Upload a dataset (CSV/Excel) that contains records with credit card data.
3. The system will process the dataset, detect credit card numbers, and display the results with their validation status.
4. The application validates credit card numbers using **Luhn’s Algorithm**, indicating whether the number is valid or not.

## Contributing
Feel free to fork the repository, create issues, and submit pull requests. Contributions are welcome!

## License
This project is licensed under the **MIT License** - see the [LICENSE](LICENSE) file for details.

