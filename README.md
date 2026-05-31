# Pet Adoption Website

A web application for pet adoption and rescue services with both frontend and backend functionality.

## Features

- User authentication (login/register)
- Pet adoption listings
- Donation system
- Contact form
- Rescue team information
- Responsive design

## Setup Instructions

1. Make sure you have Python 3.8+ installed on your system

2. Create a virtual environment (recommended):
```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```

3. Install the required dependencies:
```bash
pip install -r requirements.txt
```

4. Initialize the database:
```bash
python
>>> from app import app, db
>>> with app.app_context():
...     db.create_all()
>>> exit()
```

5. Run the application:
```bash
python app.py
```

The application will be available at `http://localhost:5000`

## Project Structure

- `app.py` - Main Flask application file
- `requirements.txt` - Python dependencies
- HTML files - Frontend templates
- CSS files - Styling
- Images - Static assets

## Database Models

- User - For user authentication and management
- Pet - For pet listings and adoption
- Donation - For tracking donations

## Security Features

- Password hashing
- User session management
- Form validation
- SQL injection protection 