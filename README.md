# 🎯 AKTU SGPA Predictor

A full-stack platform built with **Django (Backend)** and **React (Frontend)** to help AKTU students log sessional test marks, predict internal marks, and suggest target scores to achieve their goal SGPA. 

## 🚀 Features

 ## Features

- **✅Student Profiles**: Create and manage student profiles.
- **✅Sessional Marks Log**: Log marks scored in sessional tests.
- **✅Internal Marks Prediction**: Predict internal marks based on sessional performance.
- **✅SGPA Calculator**: Calculate current SGPA and predict the required end-semester marks to achieve a target SGPA.
- **✅Attendance Tracker**: (Future) Integrate with (AKGConnect) system to track attendance.


---

## 🛠️ Tech Stack

| Technology     | Usage            |
|-----------------|----------------------|
| 🐍 Django         | Backend API           |
| ⚛️ React           | Frontend UI            |
| 🐘 PostgreSQL   | Production Database  |
| 🐬 SQLite          | Development Database |
| 🐳 Docker           | Deployment                 |

---

## 🎯 Project Structure

```bash
AKTU-SGPA-Predictor/
│
├── backend/
│   ├── auth/
│   ├── api/
│   ├── marks/
│   ├── attendance/
│   ├── templates/
│   ├── static/
│   ├── settings.py
│   └── manage.py
│
├── frontend/
│   ├── src/
│   ├── components/
│   ├── pages/
│   ├── services/
│   └── App.js
│
├── docker-compose.yml
├── README.md
└── .env
```

---

## 🔧 Setup Instructions

1️⃣ Clone the Repository:
```bash
git clone https://github.com/yourusername/aktu-sgpa-predictor.git
```

2️⃣ Install Backend Dependencies:
```bash
cd backend
python -m venv env
source env/bin/activate   # for macOS/Linux
.\env\Scripts\activate     # for Windows
pip install -r requirements.txt
```

3️⃣ Install Frontend Dependencies:
```bash
cd ../frontend
npm install
```

4️⃣ Run Backend Server:
```bash
cd ../backend
python manage.py runserver
```

5️⃣ Run React Frontend:
```bash
cd ../frontend
npm run dev
```

---

## 🔑 API Endpoints

| Endpoint               | Method | Description            |
|----------------|---------|--------------------|
| `/auth/register/` | POST     | Register User             |
| `/auth/login/`     | POST     | Get JWT Tokens            |
| `/marks/submit/` | POST     | Submit Marks              |
| `/marks/predict/` | GET      | Predict Internal Marks   |
| `/sgpa/calculate/` | GET      | SGPA Calculation          |

---

## 📌 Future Enhancements

- 🎯 Add User Profile Dashboard
- 📈 Analytics and Graphs for Performance Tracking
- 🎓 Connect with `akgconnect` for Attendance Tracking
- 🛡️ Implement OAuth for Secure Authentication

---

## ✨ Contributing

1️⃣ Fork the Repo 🍴
2️⃣ Create a Feature Branch 🌱
3️⃣ Commit Changes ✅
4️⃣ Open a Pull Request 🔥

---

## 🌟 Show Some Love

⭐ Star this repo if you find it helpful!

---

## 📝 License

MIT License © 2025 Rohit YADAV (xyfer)

---
