# 🗳️ Online Voting System

![Python](https://img.shields.io/badge/Python-3.x-blue)
![Flask](https://img.shields.io/badge/Flask-Web%20Framework-green)
![Database](https://img.shields.io/badge/Database-SQLite-lightgrey)
![Status](https://img.shields.io/badge/Status-Active-success)

## 📌 Overview
The **Online Voting System** is a secure web-based application built using **Flask** that allows users to vote online with authentication and OTP verification. It also includes an admin panel for managing candidates and viewing results.

---

## 🚀 Features

- 🔐 User Login Authentication  
- 📲 OTP Verification System  
- 🗳️ One User → One Vote  
- 👨‍💼 Admin Dashboard  
- ➕ Add Candidates  
- 📊 Real-Time Results  
- 🛡️ Session Management & Validation  

---

## 🛠️ Tech Stack

| Layer       | Technology        |
|------------|------------------|
| Frontend   | HTML, CSS, JS    |
| Backend    | Python (Flask)   |
| Database   | SQLite           |

---

## 📁 Project Structure
online_voting_system/
│
├── app.py
├── database.db
├── setup_db.py
├── setup_users.py
├── test_flow.py
│
├── static/
│ ├── style.css
│ └── main.js
│
├── templates/
│ ├── login.html
│ ├── admin_login.html
│ ├── admin_dashboard.html
│ ├── add_candidate.html
│ ├── vote.html
│ ├── otp.html
│ └── result.html


---

## ⚙️ Installation & Setup

### 1️⃣ Clone Repository
```bash
git clone https://github.com/your-username/online-voting-system.git
cd online-voting-system

2️⃣ Install Dependencies
pip install flask
3️⃣ Setup Database
python setup_db.py
4️⃣ Create Users
python setup_users.py
5️⃣ Run Application
python app.py
6️⃣ Open in Browser
http://127.0.0.1:5000
👨‍💼 Admin Panel

Admin can:

Login securely
Add candidates
View live voting results
🧪 Testing

Run the test script:

python test_flow.py
🔒 Security Features
OTP-based authentication
Single vote restriction
Session-based login system
📈 Future Enhancements
Email/SMS OTP integration
Blockchain-based voting
Cloud deployment (AWS/Heroku)
Improved UI/UX
Role-based access control
🤝 Contributing

Contributions are welcome!
Feel free to fork this repo and submit a pull request.

📄 License

This project is for educational purposes only.
