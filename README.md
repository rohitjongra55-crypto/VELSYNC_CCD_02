# 🚀 Dockerized Flask App
This is a simple Flask application containerized using Docker.
## 📌 Project Objective
Build a tiny Flask app with one endpoint `/` that returns:

Hello, Velsync!
The application is containerized using Docker and runs locally.

## 🛠️ Tech Stack
- Python 3.10
- Flask
- Docker

## 📂 Project Structure

flask-docker-app/
│── app.py
│── requirements.txt
│── Dockerfile
│── README.md

## ▶️ How to Run the Project
### 1️⃣ Build Docker Image

docker build -t velsync-flask-app .

2️⃣ Run Docker Container
docker run -d -p 5001:5000 velsync-flask-app

3️⃣ Open in Browser
http://localhost:5001

✅ Output
The application displays:
Hello, Velsync!

