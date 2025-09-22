# Ayur.dev

**Ayur.dev** is a full-stack web platform that bridges traditional Ayurvedic wisdom with modern technology. It enables patients to connect with certified Ayurvedic doctors, manage appointments, analyze their health constitution, and receive personalized care — all in one place.

## Key Features

- 🔐 **User Authentication:** Secure login system for patients, doctors, and administrators with role-based access.
- 📅 **Appointment Scheduling:** Patients can book, reschedule, or cancel appointments. Doctors and admins can manage bookings via a real-time dashboard.
- 📋 **Patient Profiles & Records Management:** Access comprehensive patient profiles, securely store and update medical history, prescriptions, and treatment plans.
- 🧾 **Prescription Summarization:** AI-powered summarization helps doctors quickly understand treatment history and progress.
- 🧬 **PrakrutiSense – Constitution Analysis:** Guided questionnaire to identify the patient's Prakruti (Vata, Pitta, Kapha) for personalized treatments and lifestyle guidance.
- 🥗 **AyuChart – Personalized Ayurvedic Diet Plans:** Generates diet charts based on Prakruti for nutritional balance.
- 🗣️ **VaaniAI – Voice-Based Ayurveda Assistant:** Conversational voice assistant offering real-time advice and support.
- 💬 **AyurMind – Chatbot for Ayurvedic Guidance:** AI chatbot providing instant, reliable responses to queries.
- 📊 **Admin Dashboard:** Centralized dashboard for managing users, appointments, and platform analytics.
- 🔒 **Secure Data Storage:** All data securely stored in MongoDB, ensuring privacy and compliance.

## Tech Stack

- **Frontend:** React / TailwindCSS
- **Backend:** Node.js / Express
- **Database:** MongoDB
- **AI/ML:**
  - NLP models for prescription summarization
  - LLMs for chatbot and voice assistant

## Demo & Deployment

- **Live Demo:** [https://ayurdev.vercel.app/](https://ayurdev.vercel.app/)  
- **Admin Panel:** [https://ayurdev-admin.vercel.app](https://ayurdev-admin.vercel.app)


## Local Setup Instructions (Windows & macOS)

Follow these steps to run the Ayur.dev project locally.

### 1. Clone the Repository
Open your terminal or command prompt and run:

```bash
git clone GITHUB_LINK_TO_THE_REPO
cd REPO_DIRECTORY

# Admin Panel
cd admin
npm install

# Frontend
cd ../frontend
npm install

# Backend
cd ../backend
npm install

# Backend Server
cd backend
npm run server

# Admin Panel
cd ../admin
npm run dev

# Frontend Panel
cd ../frontend
npm run dev
