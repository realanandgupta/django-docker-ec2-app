# Django Notes App - Docker Deployment

## 🚀 Project Overview

This project is a Django-based Notes Application deployed using Docker on a cloud VM (AWS EC2).

## 🛠 Tech Stack

* Django
* Docker
* AWS EC2
* SQLite (for development)

## ⚙️ Features

* Create, update, delete notes
* REST API support
* Containerized deployment

## 🐳 How to Run

```bash
docker build -t django-notes-app .
docker run -d -p 8000:8000 django-notes-app
```

## 🌐 Access

http://<your-ec2-ip>:8000

## 📌 Future Improvements

* Add Nginx reverse proxy
* Use Gunicorn
* Integrate MySQL/PostgreSQL
* Docker Compose setup

