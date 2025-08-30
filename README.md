# 🧮 Django Calculator

A simple web-based calculator built with **Django**.  
Users can input two numbers, choose an operation (Add, Subtract, Multiply, Divide), and get the result displayed instantly.

---

## 🚀 Features
- Perform basic arithmetic operations
- Error handling for invalid inputs
- Clean and simple user interface with Django templates

---

## 📂 Project Structure
myproject/
│
├── calculator/ # App with views, templates, urls
│ ├── templates/
│ │ └── calculator/
│ │ └── home.html
│ ├── views.py
│ ├── urls.py
│ └── models.py
│
├── myproject/ # Main project settings
│ ├── settings.py
│ ├── urls.py
│ └── wsgi.py
│
├── db.sqlite3 # Database (ignored in .gitignore)
├── manage.py
└── README.md

yaml
Copy code

---

## ⚙️ Installation & Setup

1. **Clone the repository**
   ```bash
   git clone https://github.com/Theo1039/django_calculator.git
   cd django_calculator
Create & activate a virtual environment

bash
Copy code
python -m venv venv
# On Windows
venv\Scripts\activate
# On Mac/Linux
source venv/bin/activate
Install dependencies

bash
Copy code
pip install django
Run migrations

bash
Copy code
python manage.py migrate
Start the development server

bash
Copy code
python manage.py runserver
Open in browser

cpp
Copy code
http://127.0.0.1:8000/
📜 License
This project is licensed under the MIT License.

✨ Author
Theophilus Kpurugbara
📧 theophiluskpurugbara@gmail.com
🔗 GitHub

yaml
Copy code

