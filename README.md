# 📖 Overview

**Emreo** is a real-time emergency response optimization platform designed to improve ambulance dispatch efficiency during critical situations.

The system intelligently assigns the most suitable ambulance based on:

- 🚑 Ambulance Availability
- 📍 Current Location
- ⚡ Emergency Severity
- 🧠 AI-Based Decision Making

The platform combines **Machine Learning**, **Real-Time Communication**, and **GPS Tracking** to simulate a modern emergency management system that can be extended for Smart City and IoT-enabled healthcare infrastructure.

---

# 🖥️ Dashboard Preview

![Dashboard Preview](https://github.com/user-attachments/assets/24ce6f34-b675-45e3-9b60-7218ff45d2ab)

---

# ✨ Key Features

## 🚑 Intelligent Ambulance Dispatch

- Automatically identifies the nearest available ambulance
- Prioritizes incidents based on predicted severity
- Optimizes ambulance allocation during emergencies

---

## 🤖 Machine Learning-Based Severity Prediction

- XGBoost-based severity prediction
- Support Vector Machine (SVM) integration
- AI-assisted dispatch prioritization

---

## 📡 Real-Time Tracking

- Live ambulance location updates
- WebSocket-based communication
- Continuous incident monitoring
- Dynamic fleet status updates

---

## 🚓 Fleet Management

- Real-time ambulance availability
- Operational status monitoring
- Efficient resource allocation

---

## 🚨 Incident Management

- Report new emergencies
- Track incident lifecycle
- Maintain historical incident records

---

# 📸 Screenshots

## 🚨 Incident Severity & Current Status

![Incident Panel](https://github.com/user-attachments/assets/d6ff3e85-0ea2-47b6-a5a9-280a41b17ac0)

---

## 🚑 Available Fleet

![Fleet](https://github.com/user-attachments/assets/cbeed07c-1454-40c0-bed5-c367ccd4cf62)

---

## 🗺️ Live Map Tracking

![Live Map](https://github.com/user-attachments/assets/948c2e29-c2e4-489a-8289-91eaca43bf48)

---

## 📝 Log New Incident

![Incident Form](https://github.com/user-attachments/assets/4b6fece4-8ea0-42bf-ae4f-a80531689de6)

# 🛠️ Tech Stack

## 🎨 Frontend

- React.js
- Vite
- JavaScript
- HTML5
- CSS3
- WebSocket Client

---

## ⚙️ Backend

- FastAPI
- Python
- SQLAlchemy
- Pydantic

---

## 🤖 Machine Learning

- XGBoost
- Scikit-learn
- Support Vector Machine (SVM)
- Pandas
- NumPy

---

## 🗄️ Database

- SQLite
- SQLAlchemy ORM

---

## 📡 Real-Time Communication

- WebSockets
- HTTP REST APIs

---

# 🏗️ System Architecture

## 🎨 Frontend Layer

Interactive dashboard for monitoring:

- Emergency incidents
- Ambulance locations
- Fleet status
- Live dispatch operations

---

## ⚙️ API Layer

FastAPI backend responsible for:

- Incident processing
- Ambulance allocation
- API communication
- Database interaction

---

## 🤖 Machine Learning Layer

AI model responsible for:

- Emergency severity prediction
- Dispatch prioritization
- Decision support

---

## 📡 Real-Time Layer

Uses WebSocket connections to provide:

- Live ambulance tracking
- Instant incident updates
- Fleet synchronization

---

## 🗄️ Data Layer

- SQLite Database
- SQLAlchemy ORM
- Persistent data storage

---

# 🚀 Core Functionalities

- 🚑 Real-Time Ambulance Dispatch
- 🧠 Emergency Severity Prediction
- 📍 GPS Simulation
- 🚓 Fleet Management
- 📋 Incident Tracking
- 📡 WebSocket Communication
- 🔄 RESTful APIs
- 🛣️ Route Optimization
- 📊 Live Dashboard Analytics

---

# 📁 Project Structure

```text
ambulance-optimizer/
│
├── backend/
│   ├── core/
│   ├── models/
│   ├── repositories/
│   ├── routers/
│   ├── services/
│   └── tests/
│
├── frontend/
│   ├── public/
│   └── src/
│
├── ml/
│   ├── models/
│   ├── train.py
│   ├── evaluate.py
│   └── features.py
│
├── scripts/
│   ├── seed.py
│   └── gps_simulator.py
│
├── ambulance.db
├── requirements.txt
└── README.md
```

---

# ⚙️ Installation

## 1️⃣ Clone Repository

```bash
git clone https://github.com/Nomaddiwakar/Ai-based-emrgency-optimzer.git
cd Ai-based-emrgency-optimzer
```

---

## 2️⃣ Create Virtual Environment

```bash
python -m venv venv
```

### Windows

```powershell
.\venv\Scripts\Activate
```

---

## 3️⃣ Install Dependencies

```bash
pip install -r requirements.txt
```

---

## 4️⃣ Configure Environment

### Windows PowerShell

```powershell
$env:PYTHONPATH="."
```

---

# ▶️ Running the Backend

```bash
python -m uvicorn backend.main:app --reload
```

Backend Server:

```
http://127.0.0.1:8000
```

API Documentation:

```
http://127.0.0.1:8000/docs
```

---

# 🌱 Seeding Sample Data

Generate sample ambulances and emergency incidents:

```bash
python scripts/seed.py
```

If your version supports resetting data:

```bash
python scripts/seed.py --wipe
```

---

# 📍 Running GPS Simulator

```bash
python scripts/gps_simulator.py
```

This simulates real-time ambulance movement.

---

# 💻 Running the Frontend

```bash
cd frontend
npm install
npm run dev
```

Frontend:

```
http://localhost:3000
```

---

# 📖 Learning Outcomes

This project demonstrates:

- FastAPI Backend Development
- Machine Learning Integration
- WebSocket Communication
- GPS-Based Fleet Tracking
- Event-Driven Architecture
- SQLAlchemy Database Management
- REST API Development
- Frontend-Backend Integration
- AI-Assisted Decision Making

---

# 🚀 Future Enhancements

- 🌍 Real GPS Device Integration
- 🚦 Traffic-Aware Route Optimization
- 🏥 Hospital Bed Availability
- 📱 Android & iOS Mobile Application
- ☁️ Cloud Deployment
- 🛰️ Google Maps Integration
- 🤖 Advanced AI Dispatch Optimization
- 🏙️ Smart City Infrastructure Support

---

# 👨‍💻 Author

**Diwakar Kumar**

- 🎓 Final Year Computer Science Engineering Student
- 🚀 MERN Stack & AI Enthusiast
- 📍 India

GitHub:
https://github.com/Nomaddiwakar

---

# 📜 License

This project is developed for **educational, research, and portfolio purposes** as a Final Year Engineering Project.

Feel free to fork, learn from, and contribute to the project.





