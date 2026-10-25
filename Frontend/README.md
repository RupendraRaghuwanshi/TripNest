# TripNest 🏡

**A rental accommodation booking platform inspired by Airbnb.**

TripNest is a full-stack web application designed to connect guests with hosts. Users will be able to discover accommodations, explore property details, and manage their bookings through a simple and user-friendly interface.

## 🚀 Features

### Planned Features
- User registration and authentication
- Property listing and detailed property pages
- Search and filtering of accommodations
- Property booking and reservation management
- Host dashboard to manage property listings
- Responsive user interface
- Secure payment integration

> Features will be added progressively as development continues.

## 🛠️ Tech Stack

### Frontend
- React
- Vite
- JavaScript
- HTML5 and CSS3

### Backend
- Python
- Django
- Django REST Framework

### Database
- SQLite for local development
- PostgreSQL for production (planned)

### Tools
- Git and GitHub
- Visual Studio Code

## 📁 Project Structure

```text
TripNest/
├── frontend/       # React frontend
├── backend/        # Django backend
├── .gitignore
└── README.md
```

*The project structure may evolve during development.*

## ⚙️ Getting Started

### Prerequisites
- Node.js and npm
- Python 3
- Git

### 1. Clone the repository

```bash
git clone https://github.com/RupendraRaghuwanshi/TripNest/
cd TripNest
```

### 2. Run the frontend

```bash
cd frontend
npm install
npm run dev
```

### 3. Run the backend

Open a new terminal:

```bash
cd backend
python -m venv venv
```

Activate the virtual environment.

**Windows:**
```bash
venv\Scripts\activate
```

Install dependencies and run Django:

```bash
pip install -r requirements.txt
python manage.py migrate
python manage.py runserver
```

> Backend setup instructions assume that `requirements.txt` and the Django project configuration are present.

## 🔐 Environment Variables

Store sensitive configuration in environment variables. Do not commit secret keys, database credentials, or payment provider secrets.

Create local environment files using the configuration documented by the project. An `.env.example` file may be provided as a reference.

## 🗺️ Development Roadmap

- [ ] Initialize React frontend
- [ ] Set up Django REST API
- [ ] Implement user authentication
- [ ] Develop property listing pages
- [ ] Add search and filtering
- [ ] Implement booking management
- [ ] Build the host dashboard
- [ ] Integrate payment processing
- [ ] Deploy the application

## 🤝 Contributing

This project is being developed as a learning project. Contributions and suggestions can be considered as development progresses.

## 📄 License

A license will be added when the project's distribution terms are decided.

---

**TripNest** — Find your next stay.
