# Hackathon 2024: hobby finder

Project my team built during a hackathon in 2024. It's a web app that helps you find a new hobby: you answer a short quiz and get hobbies that fit your answers, or you can just browse the list. Every hobby has tags, a short description and a few links to get started. The content is in Polish.

The frontend is in frontend/hackathon2024 (React) and the backend in backend (Django REST Framework). backend/BZ has a script that loads data into MongoDB and expects the password in a .env file, which isn't in the repo.

Frontend:

    cd frontend/hackathon2024
    npm install
    npm start

Backend:

    cd backend
    pip install django djangorestframework
    python manage.py migrate
    python manage.py runserver
