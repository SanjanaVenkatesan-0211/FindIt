# 🔍 FindIT – AI-Powered Lost & Found System

## 📌 Overview

FindIT is an AI-powered lost and found platform designed to help users report, search, and recover lost items efficiently. The system uses image similarity and intelligent matching to connect lost items with found reports.

---

## 🚀 Features

* 📸 Upload lost/found item images
* 🤖 AI-based image similarity matching
* 🔎 Smart search for items
* 🔐 Secure backend with authentication
* ☁️ Cloud storage integration (Firebase / Cloudinary)
* 📊 Real-time database updates

---

## 🛠️ Tech Stack

### Frontend

* React.js
* HTML, CSS, JavaScript

### Backend

* Node.js
* Express.js

### AI Microservice

* Python
* Image similarity models / embeddings

### Database & Storage

* Firebase Firestore
* Cloudinary

---

## 🧠 How It Works

1. User uploads a lost or found item
2. Image is processed by AI microservice
3. Feature embeddings are generated
4. System compares with existing items
5. Matches are returned to the user

---

## ⚙️ Installation & Setup

### 1️⃣ Clone the repository

```bash
git clone https://github.com/SanjanaVenkatesan-0211/FindIt.git
cd FindIT
```

### 2️⃣ Install dependencies

#### Frontend

```bash
cd frontend
npm install
```

#### Backend

```bash
cd backend
npm install
```

#### AI Service

```bash
cd AI_SIMILARITY
pip install -r requirements.txt
```

---

### 3️⃣ Setup Environment Variables

Create `.env` files in required folders and add:

```
API_KEYS=your_keys_here
FIREBASE_CONFIG=your_config
```

⚠️ Do NOT upload `.env` or `serviceAccountKey.json`

---

### 4️⃣ Run the project

#### Start backend

```bash
cd backend
node server.js
```

#### Start frontend

```bash
cd frontend
npm run dev
```

#### Start AI service

```bash
cd AI_SIMILARITY
python app.py
```

---

## 📂 Project Structure

```
FindIT/
│
├── frontend/
├── backend/
├── AI_SIMILARITY/
├── .gitignore
└── README.md
```

---

## 🔐 Security Practices

* Sensitive files excluded using `.gitignore`
* Environment variables used for credentials
* API keys not exposed publicly

---

## 🌟 Future Improvements

* Mobile app integration
* Advanced AI matching
* Notification system
* Location-based tracking

---

## 👩‍💻 Author

**Sanjana V**
 B.Tech Information Technology Student 
Aspiring Data Scientist | AI Enthusiast

---

## ⭐ Contribute

Feel free to fork this repository and contribute!

---

## 📬 Contact

For queries or collaboration, reach out via GitHub.
