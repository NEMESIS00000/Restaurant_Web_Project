
# 🍔 Restaurant Web Project

A full-stack café and restaurant management web application built using **Django**.  
This project allows customers to browse the menu, register/login, add items to cart, book tables, and submit feedback, while administrators can manage content through the Django admin panel.

---

## 🚀 Features

### 👤 Customer Features
- User Signup & Login (Django Authentication)
- Secure Password Validation
- Browse Categorized Food Menu
- Add to Cart (Session-based)
- Book a Table with Email Confirmation
- Submit Feedback with Rating & Image Upload

### 🛠 Admin Features
- Manage Menu Items (Add / Edit / Delete)
- Manage Categories
- View Table Bookings
- View Customer Feedback
- Full Django Admin Control

---

## 🧩 Tech Stack

- **Backend:** Django (Python)
- **Frontend:** HTML, CSS, Bootstrap
- **Database:** SQLite
- **Authentication:** Django Built-in Auth System
- **Email Service:** Django SMTP Integration

---

## 📂 Installation & Setup

### 1️⃣ Clone Repository
```bash
git clone https://github.com/NEMESIS00000/Restaurant_Web_Project.git
cd Restaurant_Web_Project
````

### 2️⃣ Create Virtual Environment

```bash
python -m venv venv
venv\Scripts\activate   # Windows
```

### 3️⃣ Install Dependencies

```bash
pip install -r requirements.txt
```

### 4️⃣ Apply Migrations

```bash
python manage.py migrate
```

### 5️⃣ Create Superuser

```bash
python manage.py createsuperuser
```

### 6️⃣ Run Server

```bash
python manage.py runserver
```

Visit:

* 🌐 User Site → [http://127.0.0.1:8000/](http://127.0.0.1:8000/)
* 🔑 Admin Panel → [http://127.0.0.1:8000/admin/](http://127.0.0.1:8000/admin/)

---

## 🔐 Security Features

* CSRF Protection
* Password Hashing
* Django Password Validators
* Role-based Access (Admin vs User)
* Server-side Form Validation

---

## 📌 Project Modules

* Home Page
* Menu Page
* Cart System
* Booking System
* Feedback System
* Admin Dashboard

---

## 🛠 Future Improvements

* Online Payment Integration
* Order History
* Search & Filtering
* Real-time Cart Updates
* Deployment (AWS / Render / Railway)

---

## 📜 License

This project is licensed under the MIT License.

---

⭐ If you like this project, consider giving it a star on GitHub!


