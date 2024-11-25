---

# Web Applications 🌐📝  
_A Web App Built with Django_

Welcome to the **Web Application** project! This application is a simple and intuitive journal platform where users can record and track their learning progress. With account creation, secure logins, and a streamlined interface, users can document their journey across various topics.

---

## 🌟 Features  
- **User Authentication:**  
  Users can create accounts with usernames and passwords.  

- **Topic Management:**  
  Create, edit, and delete topics related to your learning interests.  

- **Journal Entries:**  
  Add detailed entries under each topic to track your progress and insights.  

- **Web Deployment:**  
  The app is deployed on a remote server, making it accessible worldwide.  

---

## 🛠️ Technology Stack  
- **Framework:** Django  
- **Programming Language:** Python  
- **Database:** SQLite (default), upgradeable to other databases  
- **Deployment:** Remote server hosting  

---

## 📂 Project Structure  
```bash
Web-Application/
├── learning_log/             # Main project folder
│   ├── __init__.py
│   ├── settings.py           # Django settings
│   ├── urls.py               # URL routing
│   ├── wsgi.py               # WSGI configuration
├── logs/                     # App folder for the journal feature
│   ├── __init__.py
│   ├── admin.py              # Admin panel configuration
│   ├── models.py             # Database models
│   ├── views.py              # View functions
│   ├── urls.py               # App-specific URL routing
│   ├── templates/            # HTML templates
│   │   ├── base.html         # Base template
│   │   ├── topics.html       # Topics page
│   │   ├── entries.html      # Entries page
├── static/                   # Static files (CSS, JS, images)
├── db.sqlite3                # SQLite database
├── manage.py                 # Django management script
├── requirements.txt          # Dependencies
└── README.md                 # Project documentation
```

---

## ⚙️ Installation and Setup  

### Prerequisites  
- Python 3.x installed on your machine.
- Install Django and other dependencies by running:
   ```bash
   pip install django
   
### Run the App Locally
1. Clone the repository:
   ```bash
   git clone https://github.com/AdityaSah2030/Web-Journal.git
   cd Web-Application
2. Set up the database
   ```bash
   python manage.py migrate
3. Start the development server
   ```bash
   python manage.py runserver
4. Open the app in your browser:
http://127.0.0.1:8000

---
## 🌍 Deployment
This project is deployed on a remote server for global access. You can follow these steps to deploy it yourself:

1. Set up a hosting service like Heroku or PythonAnywhere.
2. Configure the ```settings.py``` file to use the production environment.
3. Use a database like PostgreSQL for better scalability.
4. Deploy the app using Git and the hosting service's CLI tools.

---

## 🙌 Acknowledgments
- Inspired by the "Web Application" project in the book Python Crash Course by Eric Matthes.
- Special thanks to the developers of Django for their robust web framework.

---
