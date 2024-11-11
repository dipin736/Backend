# Backend - Django CRUD Application

This is the **Backend** for the CRUD application, built with Django and Django REST Framework. It provides APIs to manage users and other resources for the frontend React application.

## Features:
- Create, read, update, and delete user data via API endpoints.
- Built using Django REST Framework.
  
## Setup Instructions:

### Prerequisites:
- Python (v3.8 or later)
- pip (Python Package Installer)

### Install dependencies:
1. Clone this repository to your local machine:
    ```bash
    git clone https://github.com/dipin736/Backend.git
    ```

2. Navigate into the backend directory:
    ```bash
    cd Backend
    ```

3. Create and activate a virtual environment:
    ```bash
    python -m venv venv
    source venv/bin/activate  # On Windows use 'venv\Scripts\activate'
    ```

4. Install the required dependencies:
    ```bash
    pip install -r requirements.txt
    ```

### Database Setup:
1. Run migrations to set up the database:
    ```bash
    python manage.py migrate
    ```

2. Create a superuser to access the Django admin:
    ```bash
    python manage.py createsuperuser
    ```

### Run the backend server:
1. Start the Django development server:
    ```bash
    python manage.py runserver
    ```

2. The API will be available at `http://127.0.0.1:8000/`.

## How to contribute:
1. Fork the repository.
2. Create a new branch for your feature or bug fix.
3. Push your changes and create a pull request.
