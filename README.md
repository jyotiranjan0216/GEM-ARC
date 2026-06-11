# GEM-ARC 🎓
### AI-Powered University Event Management Ecosystem

[![IEEE Published](<img width="1919" height="979" alt="image" src="https://github.com/user-attachments/assets/81a7a7fb-d7d4-4388-834f-b229556ef587" />
)](https://ieeexplore.ieee.org/document/11438699/)
[![Live Demo](<img width="1919" height="981" alt="image" src="https://github.com/user-attachments/assets/8314a9d1-e98a-4901-bf6d-4ee09317b0cc" />
)](https://gem-arc.netlify.app)
[![Live Demo2](<img width="1919" height="981" alt="image" src="https://github.com/user-attachments/assets/db276de0-ea36-47b0-baff-32e90f9c29aa" />
)](https://gem-arc.netlify.app)

> 📄 **Research Paper:** [10.1109/ICCIST67338.2025.11438699](https://doi.org/10.1109/ICCIST67338.2025.11438699) — Published at ICCIST 2025, Bangalore | Added to IEEE Xplore: March 2026

---

## 🌐 Live Demo
🔗 [https://gem-arc.netlify.app](https://gem-arc.netlify.app)

---

## 📌 Overview

University events are a fundamental part of student life, yet existing platforms remain fragmented and non-customizable. **GEM-ARC** is an AI-powered ecosystem built specifically for university event management, addressing these limitations in a unified, intelligent manner.

**Key Results (Preliminary Assessment):**
- 📈 **42% increase** in event participation
- 📉 **37% reduction** in administrative workload

---

## 🤖 AI Features

| Feature | Description |
|---|---|
| 🎯 **Smart Recommendations** | Multi-layered system combining Reinforcement Learning, Collaborative Filtering, and Content-Based Filtering |
| 🔔 **Dynamic Notifications** | Personalized alerts based on each student's skills and interests |
| 🎮 **Gamification Engine** | Students earn coins redeemable via physical cards or digitally |
| 🤖 **NLP Chatbot** | Handles event idea generation and query resolution using Natural Language Processing |
| 💬 **Sentiment Analysis** | Evaluates event feedback to enable continuous system improvement |

---

## 🛠️ Tech Stack

### Frontend
- **React** — UI library
- **Tailwind CSS** — Utility-first styling
- **Vite** — Fast build tooling
- **Framer Motion** — Animations
- **Chart.js** — Data visualizations
- **Axios** — HTTP client
- **React Router DOM** — Client-side routing

### Backend
- **Express.js** — REST API framework
- **MongoDB + Mongoose** — Database & ODM
- **JWT + Bcryptjs** — Authentication & password hashing
- **Twilio** — SMS notifications
- **Gemini 1.5 API** — AI/NLP capabilities
- **TF-IDF** — Text-based content filtering

---

## 🚀 Getting Started

### Prerequisites
- Node.js v18+
- MongoDB (local or Atlas)
- npm or yarn

### Installation

```bash
# Clone the repository
git clone https://github.com/jyotiranjan0216/GEM-ARC.git
cd GEM-ARC

# Install frontend dependencies
cd frontend
npm install

# Install backend dependencies
cd ../backend
npm install
```

### Environment Variables

Create a `.env` file in the backend directory with the following:

```env
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret
GEMINI_API_KEY=your_gemini_api_key
TWILIO_ACCOUNT_SID=your_twilio_sid
TWILIO_AUTH_TOKEN=your_twilio_token
```

### Running the App

```bash
# Start backend
cd backend
npm start

# Start frontend (in a separate terminal)
cd frontend
npm run dev
```

---

## 📰 Publication

**Title:** GEM-ARC: An AI-Powered Ecosystem for University Event Management  
**Conference:** 2025 International Conference on Computational Innovations and Sustainable Technologies (ICCIST)  
**Date:** 18–19 December 2025, Bangalore, India  
**IEEE Xplore:** [View Paper](https://ieeexplore.ieee.org/document/11438699/)  
**DOI:** 10.1109/ICCIST67338.2025.11438699

---

## 👥 Contributors

Built by a team of 5 as a final year research project.

---

## 📄 License

This project is for academic and research purposes.
