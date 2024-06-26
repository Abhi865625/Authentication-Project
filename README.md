# Authentication Project

## Setup Instructions

1. **Clone the repository**:

   ```
   git clone git@github.com:Abhi865625/Authentication-Project.git
   ```

2. **Create a virtual environment and activate it**:

   ```
   python -m venv venv
   source venv/bin/activate  # On Windows use `venv\Scripts\activate`
   ```

3. **Install the required dependencies**:

   ```
   pip install -r requirements.txt
   ```

4. **Apply migrations**:

   ```
   python manage.py migrate
   ```

5. **Create a superuser**:

   ```
   python manage.py createsuperuser
   ```

6. **Run the development server**:

   ```
   python manage.py runserver
   ```

7. **Access the application**:
   Open your web browser and navigate to `http://127.0.0.1:8000/`.

## Features

- User Registration
- User Login
- Protected Index Page
- User Logout
- Password Reset
