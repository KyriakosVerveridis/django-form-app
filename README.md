# 📬 Django Form Submission App

A simple Django web application that allows users to submit a form with personal details such as first name, last name, email, date, and occupation.  
When a user submits the form, the app:

- Saves the data to a database using Django’s ORM (default: SQLite)  
- Provides an admin interface for managing submitted entries  

---

## 🚀 Features
- Django-based web form for collecting user data  
- Automatic data storage in the database  
- Admin dashboard for viewing, editing, and deleting form submissions  
- Clean and responsive frontend template  
- Secure handling of form data  

---

## 🛠️ Tech Stack
- **Backend:** Django 5.2.7 (Python 3.12)  
- **Frontend:** HTML, CSS, Bootstrap 5  
- **Database:** SQLite (default)  
- **Environment Management:** python-decouple  
- **Dependencies:** asgiref, sqlparse, tzdata (for Windows)  

---

## ⚙️ Installation & Setup

1. **Clone the repository**  
   ```
   git clone https://github.com/yourusername/django-form-app.git
   cd django-form-app
   ```

2. **Create and activate a virtual environment**  
   ```
   python -m venv venv
   source venv/bin/activate    # macOS/Linux
   venv\Scripts\activate       # Windows
   ```

3. **Install dependencies**  
   ```
   pip install -r requirements.txt
   ```

4. **Set up environment variables**  
   Create a `.env` file in the project root and add:  
   ```
   SECRET_KEY=your_secret_key
   DEBUG=True
   ```

5. **Run database migrations**  
   ```
   python manage.py migrate
   ```

6. **Create a superuser (for admin access)**  
   ```
   python manage.py createsuperuser
   ```

7. **Start the development server**  
   ```
   python manage.py runserver
   ```

8. **Access the app**  
   - Main form: http://127.0.0.1:8000  
   - Admin panel: http://127.0.0.1:8000/admin  

---

## 🧩 Project Structure
```
django-form-app/
├── job_application/
│   ├── migrations/
│   │   └── 0001_initial.py
│   ├── templates/
│   │   ├── about.html
│   │   ├── base.html
│   │   ├── contact.html
│   │   └── index.html
│   ├── __init__.py
│   ├── admin.py
│   ├── apps.py
│   ├── forms.py
│   ├── models.py
│   ├── tests.py
│   ├── urls.py
│   └── views.py
│
├── mysite/
│   ├── __init__.py
│   ├── asgi.py
│   ├── settings.py
│   ├── urls.py
│   └── wsgi.py
│
├── db.sqlite3
├── manage.py
└── requirements.txt

```

---

## 🧠 Learning Outcomes
Through this project, I learned how to:
- Build and handle forms in Django using `forms.py`
- Connect models and views through Django’s ORM
- Configure environment variables with `python-decouple`
- Manage and customize the Django admin interface  

---




