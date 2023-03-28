# College Management System

CMS is a college management system built using the Django framework, designed for facilitating interactions between students and teachers. The system offers features such as attendance management, marks management, and time table management.

## Installation

Before installation, make sure that Python and Django are installed on your system. To install Django, run the following command:

```bash
pip install django
```

## Usage

After installing Django, navigate to the College-ERP folder and run the following command:

```bash
python manage.py runserver
```

This will start the server. Then, open your browser and enter the URL http://127.0.0.1:8000/ to access the system.

## Login Info

### Teacher:

Teachers can log in using their name as the username.

#### Example:

Username: 'trisila'

Password: 'project123'

### Admin:

You can also access the Django admin page at http://127.0.0.1:8000/admin

#### Example:

Username: 'admin'

Password: 'project123'

Additionally, you can create a new admin user by running the following command:

```bash
python manage.py createsuperuser
```

## Manage Users

You can add new students and teachers to the system through the admin page. Each new user needs to be created separately. The admin page can also be used to modify all tables such as students, teachers, departments, courses, classes, and more.

For more details regarding the system and its features, please refer to the included reports.
