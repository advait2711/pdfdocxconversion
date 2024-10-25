# PDF and DOCX Conversion Project

## Overview

This project provides a web-based application for converting PDF files to DOCX format and vice versa. Built using Django, it offers a user-friendly interface for file uploads and displays conversion results. 
It also includes user authentication features such as registration, login, and logout.

## Features

- User authentication:
  - Registration: Create a new account.
  - Login: Access your account.
  - Logout: Securely sign out of your account.
- Upload PDF and DOCX files for conversion.
- Convert PDF files to DOCX format.
- Convert DOCX files to PDF format.
- Download converted files easily.

## Technologies Used

- **Backend**: Django (5.1.1)
- **Frontend**: HTML, CSS, JavaScript
- **Libraries**:
  - `docx2pdf`: For converting DOCX to PDF.
  - `pdf2docx`: For converting PDF to DOCX.
  

## Set up a Virtual Environment 
- python -m venv .venv
- .venv\scripts\activate

## Install the Required Packages:
- pip install -r requirements.txt
  
## Run the Django Development Server:
- python manage.py runserver
  
## Access the Application:
-Open your web browser and go to http://127.0.0.1:8000/accounts/register to register and start using the application.
