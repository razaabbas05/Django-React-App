📘 Django + React Notes Application

A full-stack Notes Application built using Django REST Framework for the backend and React for the frontend. The app includes JWT authentication, protected routes, and full CRUD functionality for managing notes.

🚀 Features
🔐 Authentication

Secure JWT-based login & logout

Protected routes with React Router

Auto-redirect for unauthorized users

📝 Notes Management

Create new notes

View all notes

Delete existing notes

Real-time UI updates via React Hooks

🌐 Frontend (React)

Component-based structure

Axios-based API integration

Responsive and intuitive UI

LocalStorage for token handling

🖥️ Backend (Django)

REST API built with Django REST Framework

Endpoints for authentication & CRUD

Token-based authentication using SimpleJWT

Scalable API architecture

🏗️ Tech Stack
Frontend

React

React Router

Axios

HTML / CSS

JavaScript (ES6+)

Backend

Python

Django

Django REST Framework

SimpleJWT

📦 Installation & Setup
1️⃣ Clone the repository
git clone https://github.com/yourusername/Django-React-App.git
cd Django-React-App

⚙️ Backend Setup (Django)
2️⃣ Create virtual environment
python -m venv env

3️⃣ Activate environment
source env/bin/activate      # Mac/Linux
env\Scripts\activate         # Windows

4️⃣ Install dependencies
pip install -r requirements.txt

5️⃣ Run migrations
python manage.py migrate

6️⃣ Start backend server
python manage.py runserver


Backend runs at: http://localhost:8000

🎨 Frontend Setup (React)
7️⃣ Navigate to frontend
cd frontend

8️⃣ Install dependencies
npm install

9️⃣ Start frontend
npm start


Frontend runs at: http://localhost:3000

🔗 API Endpoints
Method	Endpoint	Description
POST	/api/token/	Login (JWT)
GET	/api/notes/	Fetch all notes
POST	/api/notes/	Create a note
DELETE	/api/notes/delete/<id>/	Delete a note
