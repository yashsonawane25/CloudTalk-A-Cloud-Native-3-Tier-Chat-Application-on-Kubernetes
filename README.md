# 🚀 CloudTalk – A Cloud-Native 3-Tier Chat Application on Kubernetes

CloudTalk is a production-style, cloud-native real-time chat application built using a scalable 3-tier architecture. The application is fully containerized using Docker and orchestrated with Kubernetes (Minikube), demonstrating modern DevOps deployment practices.

---

## 🏗 Architecture Overview

CloudTalk follows a structured 3-tier architecture:

1️⃣ **Presentation Layer (Frontend)** – React.js + TailwindCSS
2️⃣ **Application Layer (Backend)** – Node.js + Express.js + Socket.io
3️⃣ **Data Layer (Database)** – MongoDB

Each service runs inside Docker containers and is deployed via Kubernetes manifests for scalable orchestration.

---

## 🎥 Demo Video

▶️ Watch the full demo here:

[https://raw.githubusercontent.com/yashsonawane25/CloudTalk-A-Cloud-Native-3-Tier-Chat-Application-on-Kubernetes/main/Project%20Video.mp4](https://raw.githubusercontent.com/yashsonawane25/CloudTalk-A-Cloud-Native-3-Tier-Chat-Application-on-Kubernetes/main/Project%20Video.mp4)

---

## 🔍 Detailed Workflow Description:

<div align="center">
  <img src="https://github.com/user-attachments/assets/f845a188-8e70-42f7-8577-30af38e83053" alt="workflow"/>
</div>


## 🔥 Key Features

* ⚡ Real-time messaging using Socket.io
* 🔐 Secure authentication & authorization using JWT
* 🐳 Docker containerization for all services
* ☸️ Kubernetes deployment (Minikube)
* 🌐 Nginx reverse proxy configuration
* 📦 Scalable 3-tier production-style architecture
* 👤 Profile management & online status tracking

---

## 🛠 Tech Stack

**Frontend:** React, TailwindCSS, DaisyUI, Zustand
**Backend:** Node.js, Express.js, Socket.io
**Database:** MongoDB
**Containerization:** Docker
**Orchestration:** Kubernetes (Minikube)
**Web Server:** Nginx
**Authentication:** JWT

---

## ⚙️ Prerequisites

* Node.js (v14 or higher)
* Docker
* Kubernetes (Minikube)
* Git

---

## 🔧 Environment Configuration

Navigate to the backend directory:

```
cd backend
```

Create a `.env` file:

```
MONGODB_URI=mongodb://mongoadmin:secret@mongodb:27017/dbname?authSource=admin
JWT_SECRET=your_secure_jwt_secret
PORT=5001
```

---

## 🐳 Running with Docker Compose

```
git clone https://github.com/yashsonawane25/CloudTalk-A-Cloud-Native-3-Tier-Chat-Application-on-Kubernetes.git
cd CloudTalk-A-Cloud-Native-3-Tier-Chat-Application-on-Kubernetes

docker-compose up -d --build
```

Access the application at:

```
http://localhost
```

---

## ☸️ Running on Kubernetes (Minikube)

Start Minikube:

```
minikube start
```

Apply Kubernetes manifests:

```
kubectl apply -f k8s/
```

Check running resources:

```
kubectl get pods
kubectl get services
```

---

## 📊 DevOps Highlights

* Multi-container Docker setup
* Internal container networking
* Kubernetes Deployments & Services
* Scalable microservice-style architecture
* Production-ready configuration structure

---

## 📸 Project Snapshots

![Settings](frontend/public/settings.png)
![Chat](frontend/public/chat.png)
![Logout](frontend/public/logout.png)
![Login](frontend/public/chatapplogin.png)

---

## 🚀 Future Enhancements

* CI/CD Pipeline Integration (Jenkins / GitHub Actions)
* Helm chart packaging
* Cloud deployment (AWS EKS / GKE / AKS)
* Monitoring with Prometheus & Grafana
* Horizontal Pod Autoscaling

---

## 📜 License

This project is licensed under the MIT License.

---

## 👨‍💻 Author

**Yash Sonawane**
DevOps & Cloud Enthusiast

If you found this project helpful, consider giving it a ⭐
