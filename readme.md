**Job Management App**

A web application built using Python and Django for managing jobs and job applications.

**Features**

- User registration and login
- Job posting and application
- Resume and cover letter upload
- Admin panel for managing jobs and applications
- Email notifications for job status update

**Getting Started**

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.

**Prerequisites**

- Python 3.x
- Django 2.1.7
- pytz 2018.9
- whitenoise 4.1.2
- Gunicorn

- PostgreSQL

**Installation**

Clone the repository

| git clone https://github.com/[username]/job-management-app.git |
| --- |

Navigate to the project directory

| **cd** job-management- **app** |
| --- |

Create a virtual environment and activate it

| **python** -m venv **env**
**source**** env**/bin/activate |
| --- |

Install the required packages

| pip **install** -r requirements.txt |
| --- |

Create a PostgreSQL database and update the settings in job\_management/settings.py

Migrate the database

| python manage.py makemigrations

 python manage.py migrate |
| --- |

Run the development server

| python manage.py runserver |
| --- |

**Deployment**

For deployment, you can use a web server like Apache or Nginx. You can also use a service like Heroku to deploy the app.

**Built With**

Python

Django

PostgreSQL