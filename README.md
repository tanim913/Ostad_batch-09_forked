# Todo Application

A simple task management web application built with Django. Users can create,
view, and manage their daily tasks through a clean web interface.

## Tech Stack
- Python 3.11
- Django 5.2.9
- SQLite (database)
- Gunicorn (production server)
- WhiteNoise (static files)

## How to Run Locally

1. Clone the repository:
   git clone https://github.com/tanim913/Ostad_batch-09_forked
   cd Ostad_batch-09

2. Create a virtual environment and activate it:
   python3 -m venv venv
   source venv/bin/activate

3. Install dependencies:
   pip install -r requirements.txt

4. Run database migrations:
   python manage.py migrate

5. Start the development server:
   python manage.py runserver

6. Open http://127.0.0.1:8000/ in your browser.

## Live Deployment

The application is deployed and publicly accessible at:
https://todo-app-assignment-2-tanim.onrender.com/

(Replace the URL above with your actual Render deployment URL)

## Author
K M Azizullah Tanim
