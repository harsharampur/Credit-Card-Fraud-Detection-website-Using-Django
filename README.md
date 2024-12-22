


# Credit Card Detection Web Application with Django

## Overview
This project is a **web-based system** built with **Django** to detect and extract credit card numbers from images using **Optical Character Recognition (OCR)** and **image processing**. The application allows users to upload an image containing a credit card, and it processes the image to detect the credit card number securely and in real time.

## Features
- **Image Upload & Processing**: Users can upload an image of a credit card, and the system will extract the card number.
- **OCR Technology**: Utilizes **Tesseract OCR** to detect and extract text from images.
- **Image Preprocessing**: Uses **OpenCV** to preprocess the uploaded image for better OCR accuracy.
- **Credit Card Validation**: Validates the extracted credit card number using **Luhn’s Algorithm**.
- **Security**: Focuses on securely handling and processing sensitive information.

## Tech Stack
- **Python**: The programming language for backend logic and OCR integration.
- **Django**: Web framework used for building the web application.
- **Tesseract OCR**: For optical character recognition to extract text from images.
- **OpenCV**: For image preprocessing to improve text extraction accuracy.
- **SQLite/PostgreSQL**: Database for storing necessary data (optional).
- **Bootstrap**: Front-end styling for creating a user-friendly interface (optional).
