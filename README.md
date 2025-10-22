# Simple Registration Web Application

A simple web application built with Python Flask that provides user registration and login functionality with SQLite database.

## Features

- User Registration with username and password
- User Login with session management
- Password hashing for security
- SQLite database for storing user credentials
- Clean and responsive UI

## Requirements

- Python 3.7+
- Flask 3.0.0
- Werkzeug 3.0.1

## Installation

1. Install dependencies:
```bash
pip install -r requirements.txt
```

## Running the Application

1. Start the application:
```bash
python app.py
```

2. Open your browser and navigate to:
```
http://localhost:5000
```

## Usage

1. **Register**: Visit `/register` to create a new account with username and password
2. **Login**: Visit `/login` to login with your credentials
3. **Main Page**: After successful login, you'll be redirected to the main page
4. **Logout**: Click the logout button to end your session

## Database

The application uses SQLite database (`users.db`) to store user information. The database is automatically created when you first run the application.

## Security Features

- Passwords are hashed using Werkzeug's security functions
- Session-based authentication
- Protection against duplicate usernames
