# 🚀 Microservice-Based Backend Module

## 📌 Overview

This project demonstrates a simple **microservice-based backend system** with two independent services:

* **Customer Service**
* **Order Service**

Each service runs separately and handles its own functionality.

---

## 🏗️ Project Structure

```
project/
│── customer-services/
│   │── customer_app.py
│   │── requirements.txt
│   │── venv/   (ignored)
│
│── order_services/
│   │── order_service_app.py
│   │── requirements.txt
│   │── venv/   (ignored)
│
│── .gitignore
│── README.md
```

---

## ⚙️ Tech Stack

* Python
* Flask (or FastAPI)
* REST API
* Git & GitHub

---

## 🚀 How to Run

### 1. Clone Repository

```bash
git clone https://github.com/your-username/your-repo.git
cd your-repo
```

---

### 2. Run Customer Service

```bash
cd customer-services
python -m venv venv
venv\Scripts\activate   # Windows
pip install -r requirements.txt
python customer_app.py
```

---

### 3. Run Order Service

```bash
cd order_services
python -m venv venv
venv\Scripts\activate   # Windows
pip install -r requirements.txt
python order_service_app.py
```

---

## 🔗 API Overview (Example)

### Customer Service

* GET /customers → Fetch all customers
* POST /customers → Add a customer

### Order Service

* GET /orders → Fetch all orders
* POST /orders → Create an order

---

## ❌ Important Notes

* Do NOT upload `venv/` to GitHub
* Use `.gitignore` to exclude it
* Each service has its own `requirements.txt`

---

## 🎯 Features

* Independent services
* Easy to scale
* Modular structure
* Simple REST APIs

---

## 👨‍💻 Author

Developed as part of a microservices backend experiment.