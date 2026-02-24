# 🚀 MEAN Stack Application – DevOps Deployment

This project demonstrates containerization, CI/CD automation, and cloud deployment of a full-stack MEAN (MongoDB, Express, Angular, Node.js) application.

---

## 📌 Project Overview

This project includes:

- **Frontend** – Angular
- **Backend** – Node.js + Express
- **Database** – MongoDB
- **Reverse Proxy** – Nginx
- **Containerization** – Docker
- **Orchestration** – Docker Compose
- **CI/CD** – GitHub Actions
- **Cloud Deployment** – Ubuntu VM (Cloud Platform)

---

## 🏗️ Architecture

Client → Nginx (Port 80)  
→ `/` → Angular Frontend  
→ `/api` → Node.js Backend  
→ MongoDB  

---

## 🐳 Docker Setup

### 1️⃣ Build Images (Local)

```bash
docker build -t <dockerhub-username>/frontend:latest ./frontend
docker build -t <dockerhub-username>/backend:latest ./backend