# Hospital Management System (HSM)

A full-stack **Hospital Management System (HSM)** built with **React** (frontend), **Laravel** (backend), and **MySQL** (database).  
This project aims to manage hospital operations efficiently, including patient records, appointments, staff management, and more.

---

## 🏗️ Project Structure

```cpp
hospital-management-system/
├── backend/          # Laravel backend
├── frontend/         # React frontend
├── database/         # Database scripts / seeds
├── .gitignore
└── README.md
```

- **backend/**: Laravel API and server-side logic.
- **frontend/**: React-based user interface.
- **database/**: SQL scripts for initial database setup and sample data.

---

## ⚡ Features

- User authentication (Admin, Doctor, Nurse, Receptionist, etc.)
- Patient management (add, update, delete records)
- Appointment scheduling
- Staff management
- Role-based access control
- Reports generation

---

## 🛠️ Technologies Used

- **Frontend:** React, JavaScript, Tailwind CSS
- **Backend:** Laravel (PHP), RESTful API
- **Database:** MySQL
- **Version Control:** Git, GitHub

---

## 💻 Installation

### 1. Clone the repository

```bash
git clone git@github.com:RayhanaAkterDev/hospital-management-system.git 
cd hospital-management-system
```

### 2. Setup Backend (Laravel)

```bash
cd backend
composer install
cp .env.example .env
php artisan key:generate
php artisan migrate
php artisan db:seed
php artisan serve
```

### 3. Setup Frontend (React)

```bash
cd frontend
npm install
npm start
```

### 4. Database

- Import the SQL file from `database/` folder if needed.

---

## 📄 Usage

- Open your browser at `http://localhost:8000` for backend API (Laravel).  
- Open your browser at `http://localhost:3000` for frontend (React).  
- Use default seeded accounts for testing (see `database/seeds`).

---

## 🤝 Contributing

1. Fork the repository.
2. Create a new branch: `git checkout -b feature/your-feature`
3. Commit your changes: `git commit -m "feat: add new feature"`
4. Push to the branch: `git push origin feature/your-feature`
5. Open a pull request.

---

## 📄 License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
