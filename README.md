<div align="center">

# 🏆 SportKart

> A full-stack sports e-commerce platform to buy and sell shoes, jerseys, boots, footballs and more — built for Indian sports lovers.

![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![Django](https://img.shields.io/badge/Django-092E20?style=flat&logo=django&logoColor=white)
![DRF](https://img.shields.io/badge/DRF-REST_API-red?style=flat)
![React](https://img.shields.io/badge/React-20232A?style=flat&logo=react&logoColor=61DAFB)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=flat&logo=postgresql&logoColor=white)
![JWT](https://img.shields.io/badge/JWT-Auth-black?style=flat&logo=jsonwebtokens)

</div>

---

## 🚀 Live Demo
- **Frontend:** [Deployed on Vercel](#)
- **Backend API:** [Deployed on Railway](#)

---

## 📌 Features

### 👤 Three User Roles
- **Seller** — Add products, manage inventory, track orders
- **Buyer** — Browse & buy products, track deliveries
- **Admin** — Full platform control & user management

### 🔑 Core Functionality
- JWT-based Authentication & Authorization
- Role-Based Access Control (RBAC)
- Product listing with photo uploads (Cloudinary)
- Search & filter by sport, brand, size, price
- Cart & Wishlist management
- Order tracking system
- Razorpay payment integration
- RESTful API with Django REST Framework

---

## 🛠️ Tech Stack

| Layer | Technology |
|---|---|
| Frontend | React.js, Tailwind CSS |
| Backend | Django, Django REST Framework |
| Database | PostgreSQL |
| Auth | JWT (SimpleJWT) |
| Image Storage | Cloudinary |
| Payment | Razorpay |
| Deployment | Railway (Backend), Vercel (Frontend) |

---

## 📁 Project Structure
```
sportkart/
├── backend/
│   ├── accounts/        # User auth & roles
│   ├── products/        # Product listings
│   ├── orders/          # Order management
│   ├── payments/        # Razorpay integration
│   └── sportkart/       # Django settings
├── frontend/
│   ├── src/
│   │   ├── components/
│   │   ├── pages/
│   │   └── api/
└── README.md
```

---

## ⚙️ Local Setup

### Backend
```bash
git clone https://github.com/Gytgowtham/sportkart.git
cd sportkart/backend
python -m venv venv
source venv/bin/activate
pip install -r requirements.txt
python manage.py migrate
python manage.py runserver
```

### Frontend
```bash
cd frontend
npm install
npm start
```

---

## 🔗 API Endpoints

| Method | Endpoint | Description |
|---|---|---|
| POST | `/api/auth/register/` | User Registration |
| POST | `/api/auth/login/` | JWT Login |
| GET | `/api/products/` | List all products |
| POST | `/api/products/` | Add product (Seller) |
| GET | `/api/products/:id/` | Product detail |
| POST | `/api/cart/` | Add to cart |
| POST | `/api/orders/` | Place an order |
| GET | `/api/orders/my/` | View my orders |
| POST | `/api/payments/` | Razorpay payment |

---

## 👨‍💻 Developer

**Gowtham Krish**
- 📧 gowthamkrish4506@gmail.com
- 💼 [LinkedIn](https://linkedin.com/in/gowtham-krish-009021276)
- 🐙 [GitHub](https://github.com/Gytgowtham)

---

## 📄 License
This project is licensed under the [MIT License](LICENSE).
