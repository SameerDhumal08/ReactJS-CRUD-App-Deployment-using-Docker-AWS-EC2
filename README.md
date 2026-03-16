# 🚀 ReactJS CRUD App Deployment using Docker & AWS EC2

This project demonstrates how to containerize and deploy a **ReactJS CRUD application** using **Docker** and **AWS EC2**.  
The goal of this project was to understand how applications move from **development → containerization → cloud deployment**.

---

## 🎥 Project Demo

[![Watch the Demo](https://img.youtube.com/vi/ph0OW3TlzPI/0.jpg)](https://youtu.be/ph0OW3TlzPI)

Click the image above to watch the full project demo video.

---

## 🛠️ Technologies Used

- ⚛️ ReactJS (Frontend Application)
- 🐳 Docker (Containerization)
- ☁️ AWS EC2 (Cloud Deployment)
- 📦 Docker Hub (Image Repository)
- 🌐 Web Server running on Port 80

---

## 📌 Project Workflow

1. Built a **CRUD application using ReactJS**
2. Created a **Docker image with all dependencies**
3. Pushed the image to **Docker Hub**
4. Launched an **AWS EC2 instance**
5. Pulled the image from Docker Hub to the EC2 server
6. Ran the container and exposed the application on **Port 80**

---

## 🐳 Docker Commands Used

### Build Docker Image

```bash
docker build -t react-crud-app .
