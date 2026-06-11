# GEM-ARC 🎓
### AI-Powered University Event Management Ecosystem

[![IEEE Published](https://img.shields.io/badge/IEEE-Published-blue?logo=ieee)](https://ieeexplore.ieee.org/document/11438699/)
[![Live Demo](https://img.shields.io/badge/Live-Demo-brightgreen)](https://gem-arc.netlify.app)
[![Conference](https://img.shields.io/badge/ICCIST-2025-orange)](https://ieeexplore.ieee.org/xpl/conhome/11436007/proceeding)

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
