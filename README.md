<h1>Login System using Python and Flask </h1>

<p>This repository contains a login system implemented using Python and Flask. It utilizes the Flask-Login module for user authentication and session management. The password security is ensured by leveraging the Werkzeug security library. The front-end is designed using HTML.</p>

## Features

- User registration: Users can create new accounts by providing their desired email,     username and password.
- User login: Registered users can log in to their accounts using their credentials.
- Password hashing: Passwords are securely hashed and stored in the database using Werkzeug's password hashing functions.
- Session management: Flask-Login handles user session management and provides convenient methods to check if a user is authenticated, retrieve the currently logged-in user, and more.
- HTML templates: The front-end views are created using HTML templates for a visually appealing and user-friendly interface.

## Prerequisites

To run this project, you need to have the following installed:

- Python (version 3.6 or above)
- Flask (version 2.0.1 or above)
- Flask-Login (version 0.5.0 or above)
- Werkzeug (version 2.0.1 or above)
- SQLAlchemy (version 2.0.16 or above)

## For Python 
   ```sh
    https://www.python.org/downloads/
   ```
## For Flask, Flask-Login, Werkzeug
   ```sh
    pip install flask flask-login werkzeug sqlalchemy
   ```

## Run application
  ```sh
   python main.py
  ```
- Open your web browser and visit http://127.0.0.1:5000/ to access the login system

## File Structure

- main.py: The main entry point of the application.

- models.py: Defines the database schema using SQLAlchemy ORM.

- views.py: Contains the routes and views for the application.

- templates/: Directory containing HTML templates.

- static/: Directory containing static assets (CSS, JavaScript, etc.).


## Contact
For any inquiries or support, please contact mdbusiness1803@gmail.com.