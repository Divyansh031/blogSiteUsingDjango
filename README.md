# blogSiteUsingDjango
Django Blog Site
"A simple Django-based blog site that allows users to create, read, update, and delete (CRUD) blog posts."


Features
Create, Read, Update, and Delete (CRUD) blog posts


Simple and clean user interface


Django-based backend

Project Structure:


blog/
│── blog/            # Django app for blog functionality
│── posts/           # Django app for posts functionality
│── templates/       # HTML templates
│── db.sqlite3       # Database file
│── manage.py        # Django management script
└── README.md        # Project documentation

Technologies Used:
Python
Django
SQLite 
HTML and CSS


Installation & Setup:
1. Clone the Repository

git clone https://github.com/Divyansh031/blogSiteUsingDjango.git
cd blog

2. Create a Virtual Environment

python -m venv venv
source venv/bin/activate  # For Linux/macOS
venv\Scripts\activate  # For Windows

3. Install Dependencies

pip install -r requirements.txt


4. Apply Migrations

python manage.py migrate


5. Run the Development Server

python manage.py runserver

Now open http://127.0.0.1:8000 in your browser.
