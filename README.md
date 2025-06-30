

# 🌿 AyurvediCure – AI Meets Ayurveda

🧑‍⚕️ Your Personalized Ayurvedic Health Companion, powered by AI and Human Expertise.

---

## 📖 Overview

**AyurvediCure** is a full-stack AI-ML-based web application that reimagines Ayurvedic healthcare through technology. It offers secure, smart, and user-friendly interactions with both AI-powered and real Ayurvedic doctors. The platform bridges ancient natural healing with intelligent automation — for everyone, anywhere, anytime.

---

## 🌟 Features

### 🤖 AI-Powered Ayurvedic Doctor

Get instant health advice and natural treatment suggestions through a machine learning-powered chat interface trained on Ayurvedic data.

### 🧑‍⚕️ Human Doctor Consultation

Choose to chat with real Ayurvedic doctors directly — for deeper, personalized guidance.

### 🗂️ Secure Medical Dashboard

* View past interactions
* Store consultation history
* All protected with JWT and hosted securely on MongoDB Atlas

### 📍 Doctor Locator

Find certified Ayurvedic practitioners near you — integrated with geolocation-based logic.

### 🔁 Flexible AI ↔ Human Switching

Begin a conversation with the AI and seamlessly switch to a human doctor without losing chat context.

### 📊 Dataset-Driven Intelligence

Uses a curated CSV (`Disease, Symptoms, Ayurvedic Treatment.csv`) to provide fast and relevant responses.

---

## 🚀 Live Project

[Visit AyurvediCure →](https://ayurvedi-cure-git-main-mukund-thakurs-projects.vercel.app/)



---

## 🛠️ Tech Stack

### ⚛️ Frontend

* **HTML/CSS/JS**
* Hosted via **Vercel**
* Responsive layout optimized for mobile and desktop

### 🐍 Backend

* **Python + Flask**
* MongoDB Atlas for storage
* `Flask-CORS`, `python-dotenv`, and `gunicorn`
* Deployed on **Render**

### 🧠 ML & Data

* **Pandas** for data parsing
* AI logic trained on Ayurvedic treatment data from CSV

---

## 🧪 API Overview

### 🔐 Authentication

* `POST /auth/register` – User registration
* `POST /auth/login` – Login & token generation

### 💬 Consultations

* `POST /ai/diagnose` – Get AI-generated response
* `POST /doctor/chat` – Human doctor interaction
* `GET /dashboard` – Retrieve consultation history

---

## 🏗️ Local Setup

```bash
# Clone the repository
git clone https://github.com/Mukund934/AyurvediCure.git
cd AyurvediCure
```

---

### ▶️ Backend Setup

```bash
cd backend
pip install -r requirements.txt
```

Create a `.env` file:

```env
MONGODB_URI=your_mongo_db_uri
JWT_SECRET=your_jwt_secret
```

Run the backend:

```bash
python app.py
```

---

### 🖼️ Frontend Deployment (Already Live on Vercel)

> All files are in root — no build step needed. You can re-deploy anytime via Vercel dashboard.

---

## 🛡️ Security & Architecture

| Layer        | Details                              |
| ------------ | ------------------------------------ |
| Auth         | JWT-based login/register             |
| Storage      | MongoDB Atlas                        |
| AI Layer     | Rule-based + CSV-trained logic       |
| Hosting      | Vercel (frontend) + Render (backend) |
| Env Handling | `dotenv` and Render/Vercel secrets   |

---

## 🎯 Future Enhancements

* 📱 PWA support (Offline Access)
* 🧠 Integration with LangChain or Gemini APIs
* 🗣️ Voice-to-Text AI chat
* 📥 PDF export of consultations
* 🔔 Notifications for doctor messages
* 🧬 Ayurvedic Dosha Scanner

---

## 💡 Why AyurvediCure?

✅ Merges ancient healing with modern AI
⚡ Blazing fast frontend on Vercel
🔐 Secure backend hosted on Render
🧠 Intelligent responses from structured Ayurvedic data
🌍 Useful for patients, doctors & curious health enthusiasts

---

## 🤝 Contributing

We’d love your contributions!
Fork → Branch → Commit → PR 🚀

---

## 📜 License

Licensed under the **MIT License**.
View the [LICENSE](./LICENSE) file for full terms.

---

## 📬 Contact

👨‍💻 Built by [Mukund Thakur](https://github.com/Mukund934)
📩 Email: `mukund.th04@gmail.com`
🔗 GitHub: [github.com/Mukund934](https://github.com/Mukund934)

---

