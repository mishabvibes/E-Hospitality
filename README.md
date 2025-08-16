E-Hospitality 🏥

E-Hospitality is a Django-based Hospital Management System designed to streamline healthcare operations such as patient management, doctor appointments, and administrative tasks. This project focuses on delivering an easy-to-use, responsive, and secure solution for healthcare institutions.

🚀 Features

User Authentication – Secure login and account creation for patients and staff.

Appointment Booking – Patients can schedule appointments online.

Patient Management – Doctors and admins can manage patient records.

Admin Dashboard – Manage appointments, users, and system data.

Responsive Design – Works seamlessly on desktop and mobile devices.

Database Integration – Uses MySQL for reliable data management.

🛠️ Tech Stack

Backend: Django (Python)

Database: MySQL

Frontend: HTML, CSS, JavaScript (Bootstrap/Tailwind for styling)

Authentication: Django’s built-in auth system

Deployment: PythonAnywhere / Localhost (XAMPP or MySQL server)

📂 Project Structure
E-Hospitality/
│── hospital/          # Main Django app  
│── templates/         # HTML templates  
│── static/            # CSS, JS, Images  
│── db.sqlite3         # Database (for testing, MySQL for production)  
│── manage.py          # Django project manager  
│── requirements.txt   # Dependencies  

⚙️ Installation & Setup

Clone the repository

git clone https://github.com/heymishab/E-Hospitality.git
cd E-Hospitality


Create a virtual environment & activate it

python -m venv venv
source venv/bin/activate   # On Mac/Linux  
venv\Scripts\activate      # On Windows  


Install dependencies

pip install -r requirements.txt


Database Setup (MySQL)

Create a database in MySQL (e.g., ehospitality_db).

Update settings.py with your database credentials.

DATABASES = {
    'default': {
        'ENGINE': 'django.db.backends.mysql',
        'NAME': 'ehospitality_db',
        'USER': 'your_username',
        'PASSWORD': 'your_password',
        'HOST': 'localhost',
        'PORT': '3306',
    }
}


Run migrations

python manage.py migrate


Create a superuser

python manage.py createsuperuser


Run the server

python manage.py runserver


Now, visit http://127.0.0.1:8000/ in your browser.

🔑 Login Credentials (Demo)

Admin Panel: /admin

Use the superuser credentials you created during setup.

🤝 Contributing

Contributions are welcome! Feel free to fork this repo and submit a pull request.

📜 License

This project is licensed under the MIT License – free to use, modify, and distribute.
