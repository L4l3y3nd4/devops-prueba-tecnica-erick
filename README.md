# 🚀 DevOps Technical Test – Django API

This repository contains a simple Django REST API prepared for a DevOps technical test.

It demonstrates:

- Docker containerization
- CI/CD with GitHub Actions
- Django REST Framework API
- Basic DevOps best practices

---

# 📌 Tech Stack

- Python 3.11
- Django
- Django REST Framework
- Docker
- GitHub Actions (CI/CD)

---

# 📂 Project Structure

```
api/        -> Django app
demo/       -> Django project settings
Dockerfile  -> Container definition
requirements.txt -> Dependencies
.github/workflows -> CI/CD pipeline
```

---

# ▶️ Run Locally (Without Docker)

## 1. Clone repo

```bash
git clone https://github.com/L4l3y3nd4/devops-prueba-tecnica-erick.git
cd devops-prueba-tecnica-erick
```

## 2. Create virtual environment

```bash
python -m venv venv
venv\Scripts\activate
```

## 3. Install dependencies

```bash
pip install -r requirements.txt
```

## 4. Apply migrations

```bash
python manage.py migrate
```

## 5. Run server

```bash
python manage.py runserver
```

API available at:

```
http://127.0.0.1:8000/api/
```

---

# 🐳 Run with Docker

## Build image

```bash
docker build -t django-devops-app .
```

## Run container

```bash
docker run -p 8000:8000 django-devops-app
```

API available at:

```
http://localhost:8000/api/
```

---

# ⚙️ CI/CD Pipeline

This project includes a GitHub Actions pipeline that:

- Installs Python dependencies
- Validates project structure
- Builds Docker image
- Ensures application can start

Pipeline runs automatically on push.

Check status in the **Actions tab**.

---

# ✅ Features Demonstrated

✔ Dockerized Django application  
✔ CI/CD with GitHub Actions  
✔ Clean repository practices (.gitignore)  
✔ REST API with Django REST Framework  
✔ DevOps-ready structure  

---

# 📌 Author

Erick  
DevOps Engineer Candidate 🚀
