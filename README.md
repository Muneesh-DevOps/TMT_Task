# 🚀 TMT_Task

Task to deploy a **Fullstack React + Node.js** application using **Docker** and **GitHub Actions**.

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
git clone [https://github.com/Muneesh-DevOps/TMT_Task.git](https://github.com/Muneesh-DevOps/TMT_Task.git)
cd TMT_Task
docker compose up -d
````

* Frontend: [http://localhost:3000](http://localhost:3000)
* Backend: [http://localhost:5000](http://localhost:5000)

---

### 🐳 Option 2: Run with Prebuilt Docker Images (No Code Needed)

```bash
docker pull muneesh181/tmt-client
docker pull muneesh181/tmt-server

docker run -d -p 3000:80 muneesh181/tmt-client
docker run -d -p 5000:5000 muneesh181/tmt-server
```

---

## 📁 Project Structure

```
TMT_Task/
├── client/                     # React frontend application
├── server/                     # Node.js backend API
├── docker-compose.yml          # Docker orchestration file
└── .github/
    └── workflows/
        └── docker-build-push.yml  # GitHub Actions CI/CD workflow
```

---

## ✅ Notes

* Make sure Docker is installed and running on your machine.
* If ports 3000 or 5000 are in use, change them in the `docker-compose.yml` or during `docker run`.
* CI/CD is automated with GitHub Actions — any push to `main` builds and pushes new images to Docker Hub.

---
