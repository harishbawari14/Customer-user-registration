# Customer User Registration

This is a Django-based project that provides a customer user registration system with authentication and user management features.

## Features

- User Registration
- User Login & Logout
- Profile Management
- Password Reset & Change
- Email Verification (if configured)
- Admin Panel for User Management

## Installation

### 1. Clone the Repository

```sh
git clone https://github.com/harishbawari14/Customer-user-registration.git
cd Customer-user-registration
```

### 2. Create a Virtual Environment (Optional but Recommended)

```sh
python -m venv venv
source venv/bin/activate  # On macOS/Linux
venv\Scripts\activate     # On Windows
```

### 3. Install Dependencies

```sh
pip install -r requirements.txt
```

### 4. Apply Migrations

```sh
python manage.py migrate
```

### 5. Create a Superuser (For Admin Access)

```sh
python manage.py createsuperuser
```

### 6. Run the Development Server

```sh
python manage.py runserver
```

Visit `http://127.0.0.1:8000/` in your browser to access the application.
