# 🚀 OCPI Simulator + UBC Adaptor (Docker Setup)

## 📌 Project Overview

This project runs multiple services using Docker:

* 🧠 UBC OCPI Adaptor
* ⚡ OCPI Simulator
* 🐘 PostgreSQL Database

All services are connected using **docker-compose**.

---

## 🐳 Prerequisites

Make sure you have installed:

* Docker Desktop
* Docker Compose

---

## 📦 Docker Images Used

* `harishsahu/ubc-ocpi-adaptor-release-v2-app:latest`
* `harishsahu/ocpi-simulator:latest`
* `postgres:16-alpine`

---

## ▶️ How to Run

### 1. Clone the repository

```bash
git clone https://github.com/Hks199/bpp_compose.git
cd your-repo
```

### 2. Run all services

```bash
docker-compose up -d
```

---

## 🌐 Access Services

* UBC Adaptor → http://localhost:6001
* OCPI Simulator → http://localhost:6002
* PostgreSQL → localhost:5432

---

## ⚙️ Environment Variables

You can configure using `.env` file:

```env
PORT=6001
POSTGRES_PASSWORD=postgres
```

---

## 🛑 Stop Services

```bash
docker-compose down
```

---

## 📁 Project Structure

```
.
├── docker-compose.yml
├── .env
└── README.md
```

---

## 👨‍💻 Author

Harish Sahu 🚀
