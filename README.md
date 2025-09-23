# PS Chosen SIH Hackathon

This README provides an overview of the project, including team details, relevant links, tasks completed, tech stack, key features, and steps to run the project locally.

## Team Details

**Team Name:** SIH Winners  

**Project-Title** : Comprehensive Cloud-Based Practice Management & Nutrient Analysis Software for Ayurvedic Dietitians, Tailored for Ayurveda-Focused Diet Plans . 

**Problem statement Id** : **25024**

**Team Leader:** [@vanshkallra](https://github.com/vanshkallra) 

**Team Members:**

- **Tanishka Khandelwal** - 2023UCM2339 - [@Tanishka-tech](https://github.com/tanishka-git2715)  
- **Deepak Goel** - 2023UCS1671 - [@deepakpro190](https://github.com/deepakpro190)  
- **Rashi Raturi** - 2023UCM2317 - [@rashi-raturi](https://github.com/rashi-raturi)  
- **Jaynab P** - 2023UCM2354 - [@JaynabP](https://github.com/JaynabP)  
- **Vansh Kalra** - 2023UCM2372 - [@vanshkallra](https://github.com/vanshkallra)  
- **Swarit Varshney** - 2023UCM2346 - [@stvy2346](https://github.com/stvy2346)  

## Project Links

- **SIH Presentation:** [Final SIH Presentation](TBD)  
- **Video Demonstration:** [Watch Video](https://youtu.be/-QQ5AFvT69k)  
- **Live Deployment:**
   - **User Frontend:** [View User Site](https://ayurdev.vercel.app/)  
   - **Admin Frontend:** [View Admin Site](https://ayurdev-admin.vercel.app)  
- **Source Code:** [GitHub Repository](https://github.com/rashi-raturi/Ayur.dev)  
- **Additional Resources:** TBD

## Key Features

- **User Authentication**  
  Secure login system for patients, doctors, and administrators with role-based access.

- **Appointment Scheduling**  
  Patients can easily book, reschedule, or cancel appointments with Ayurvedic doctors. Doctors and admins can view and manage bookings via a real-time dashboard.

- **Patient Profiles & Records Management**  
  Doctors and patients can access comprehensive patient profiles. The system also allows secure storage, access, and updating of medical history, prescriptions, and treatment plans.

- **Prescription Summarization**  
  AI-powered summarization of patient prescriptions helps doctors quickly understand treatment history and progress over time.

- **PrakrutiSense – Constitution Analysis**  
  A guided questionnaire that identifies the patient's **Prakruti** (Vata, Pitta, Kapha) to enable personalized treatments and lifestyle guidance.

- **AyuChart – Personalized Ayurvedic Diet Plans**  
  Automatically generates diet charts based on the user's Prakruti, promoting nutritional balance as per Ayurvedic principles.

- **VaaniAI – Voice-Based Ayurveda Assistant**  
  A conversational voice assistant offering real-time Ayurvedic advice, lifestyle tips, and support.

- **AyurMind – Chatbot for Ayurvedic Guidance**  
  An AI chatbot that provides instant, reliable responses to user queries about Ayurvedic health and wellness.

- **Admin Dashboard**  
  Centralized dashboard for admins to manage users, oversee appointments, and view platform usage analytics.

- **Secure Data Storage**  
  All patient and consultation data is securely stored in **MongoDB**, ensuring privacy and compliance with data protection best practices.

---

## Tech Stack

- **Frontend**: `React` / `TailwindCSS`
- **Backend**: `Node.js` / `Express` 
- **Database**: `MongoDB` 
- **AI/ML**:
  - NLP models for prescription summarization
  - LLMs for chatbot and voice assistant
  - OmniDimension for AI Agent
---

### Installation

## Install dependencies

1. **Install admin dependencies**
   ```bash
   cd admin
   npm install
   ```

2. **Install frontend and backend dependencies**
   ```bash
   cd frontend
   npm install
   ```

   ```bash
   cd ..
   cd backend
   npm install
   ```

3. **Set up environment variables**
   - .env file structures here -

4. **Start server:**
   ```bash
   cd backend
   npm run server
   ```

5. **Start Admin Panel:**
   ```bash
   cd admin
   npm run dev
   ```
   
