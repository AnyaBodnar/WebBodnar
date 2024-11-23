# Hardware Control

A course project for Web Technologies and Web Design discipline.

## Description
Hardware Control is a web application designed to manage and monitor hardware components. This project is developed as part of the Web Technologies and Web Design course.

## Installation

### Prerequisites
- Python 3.x
- Git

### Clone the Repository
```bash
git clone https://github.com/AnyaBodnar/WebBodnar.git
```

### Setup Virtual Environment
1. Create a virtual environment:
```bash
python -m venv venv
```

2. Activate the virtual environment:
- On Windows:
```bash
source venv/Scripts/activate
```
- On Unix or MacOS:
```bash
source venv/bin/activate
```

### Install Dependencies
Install all required packages using pip:
```bash
pip install -r requirements.txt
```

### Database Setup
1. Apply migrations:
```bash
python manage.py migrate
```

2. Create a superuser:
```bash
python manage.py createsuperuser
```

### Running the Application
Start the development server:
```bash
python manage.py runserver
```

The application will be available at `http://localhost:8000`

## Access
After starting the server, you can:
- Access the admin panel at: `http://localhost:8000/admin`
- Login using your superuser credentials

## License
This project is part of an academic course and is available for educational purposes.

## Author
Anna Bodnar