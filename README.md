# 📝 Blog Site Using Django

A simple **Django-based blog site** that allows users to **Create, Read, Update, and Delete (CRUD)** blog posts. The project features a clean and user-friendly interface with a Django-powered backend.

---

## 🚀 Features

- 🖊 **Create, Read, Update, and Delete (CRUD) blog posts**
- 🎨 **Simple and clean user interface**
- 🛠️ **Django-based backend with SQLite database**
- 🔍 **Responsive and easy to use**

---

## 🏗️ Project Structure

blogSiteUsingDjango/ │── blog/ # Django app for blog functionality │── posts/ # Django app for posts functionality │── templates/ # HTML templates for frontend │── db.sqlite3 # SQLite database file │── manage.py # Django management script └── README.md # Project documentation

t

---

## 🛠️ Technologies Used

- **Python**
- **Django**
- **SQLite**
- **HTML & CSS**

---

## 🔧 Installation & Setup

```bash
### 1️⃣ **Clone the Repository**
git clone https://github.com/Divyansh031/blogSiteUsingDjango.git
cd blogSiteUsingDjango

2️⃣ Create a Virtual Environment (Recommended)

python -m venv venv
source venv/bin/activate  # For Linux/macOS
venv\Scripts\activate     # For Windows

3️⃣ Install Dependencies

pip install -r requirements.txt

4️⃣ Apply Migrations

python manage.py migrate

5️⃣ Run the Development Server

python manage.py runserver
Now, open http://127.0.0.1:8000 in your browser to access the blog site
