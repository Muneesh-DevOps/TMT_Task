# 🚀 TMT_Task

> Task to deploy a Fullstack React + Node.js application using Docker and GitHub Actions.

---

## 🌐 Tech Stack

- ✅ React (Frontend)
- ✅ Node.js + Express (Backend)
- ✅ Docker (Containerization)
- ✅ GitHub Actions (CI/CD)
- ✅ Docker Hub (Deployment)

> 🧑‍💻 Anyone can run this project using Docker — no manual setup needed.

---

## 📦 How to Run This Project

### 🧭 Option 1: Run with Docker Compose (Recommended)

```bash
git clone https://github.com/Muneesh-DevOps/TMT_Task.git
cd TMT_Task
docker compose up -d

### Option 2: Pull Prebuilt Docker Images (No Code Needed)

docker pull muneesh181/tmt-client
docker pull muneesh181/tmt-server

docker run -d -p 3000:80 muneesh181/tmt-client
docker run -d -p 5000:5000 muneesh181/tmt-server



