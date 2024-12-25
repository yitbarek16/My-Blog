# My-Blog
Blog Web Application: A Django web app that enables users to create, read, update, and delete blog posts. It features a clean interface and is designed for easy content sharing and management.

## Features
- Create new blog posts with titles, content, and publish dates.
- View all blog posts in a list or detailed view.
- Edit existing blog posts to update content.
- Delete unwanted or outdated posts.
- Clean and responsive interface for better user experience.

---

## Technologies Used
- **Backend**: Django (Python)
- **Frontend**: HTML, CSS, Bootstrap
- **Database**: SQLite (default with Django)

---

## Prerequisites
Before running the application, ensure you have the following installed:
- Python 3.x
- Django 3.x or later

---

## Setup and Installation

1. **Clone the repository**:
   ```bash
   git clone https://github.com/yourusername/blog-app.git
   cd myblog

2. **Create and activate a virtual environment**:
     ```bash
     python -m venv venv
     source venv/bin/activate

3. **Run database migrations**:
     ```bash
     python manage.py migrate

4. **Start the development server**:
     ```bash
     python manage.py runserver
     
5. **Access the application**:
     Open your web browser and navigate to http://127.0.0.1:8000/.
