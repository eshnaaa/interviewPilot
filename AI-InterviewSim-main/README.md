# 🤖 InterviewPilot

[![CI](https://github.com/rahulprajapati08/AI-InterviewSim/actions/workflows/ci.yml/badge.svg)](https://github.com/rahulprajapati08/AI-InterviewSim/actions/workflows/ci.yml)
[![Docker Image](https://img.shields.io/badge/docker-ready-blue.svg)](https://hub.docker.com/)
[![Python](https://img.shields.io/badge/python-3.10%2B-blue.svg)](https://www.python.org/)
[![React](https://img.shields.io/badge/frontend-react-61DAFB?logo=react&logoColor=white)](https://reactjs.org/)
[![Open Source](https://badgen.net/badge/status/open%20source/green)](https://github.com/rahulprajapati08/AI-InterviewSim)


InterviewPilot is an AI-powered placement preparation platform designed to help students and job seekers practice realistic interviews, identify skill gaps, and improve their readiness for recruitment processes. The platform combines AI-driven interview generation, resume-based questioning, coding assessments, behavioral analysis, and personalized learning recommendations to create a comprehensive interview preparation experience.


---

## 🚀 Features
* 📄 Resume-Based Interview Generation
* 🎙️ Voice-Powered AI Interviews
* 🧑‍💻 Coding Assessment Environment
* 📹 Real-Time Behavioral Analysis
* 📊 Placement Readiness Score
* 🧠 Skill Gap Detection
* 📈 Personalized Learning Roadmaps
* 🏢 Company-Specific Interview Modes
* 📝 Interview History & Performance Analytics
* 🔐 Secure JWT Authentication


---

## 📸 Screenshots

<img width="1920" height="1020" alt="Screenshot 2025-07-24 080006" src="https://github.com/user-attachments/assets/5c469f0a-6272-4734-8228-308788d55477" />
<img width="1920" height="1020" alt="Screenshot 2025-07-24 080456" src="https://github.com/user-attachments/assets/7b5c2143-50d9-41cb-b004-28cebc72b67c" />
<img width="1920" height="1020" alt="Screenshot 2025-07-24 080045" src="https://github.com/user-attachments/assets/082634db-628c-4200-a8fb-55db409b08d4" />


---




## 🎥 Demo Video

[![Watch the Demo](https://img.youtube.com/vi/ZddswtI6TSs/0.jpg)](https://youtu.be/ZddswtI6TSs)


---

## 🧠 Tech Stack

- **Backend**: FastAPI, LangChain, MongoDB
- **Frontend**: React.js + Vite
- **Voice**: Whisper , SpeechSynthesizer
- **LLM**: Groq (LLaMA 3) 
- **Auth**: JWT
- **CI/CD**: GitHub Actions
- **Containerization**: Docker

---

## ⚙️ Setup Instructions

1. **Clone this repo:**
   ```bash
   git clone https://github.com/rahulprajapati08/AI-InterviewSim.git
   cd AI-InterviewSim
2. Create .env file:
    ```bash
    MONGO_URL=your_mongo_uri
    DB_NAME = your_db_name
    DEFAULT_GROQ_API_KEY=your_groq_key
3. Install Dependencies   
    ```bash
    cd backend
    pip install -r requirements.txt
4. Run the Server
   ```bash
   uvicorn app:app --reload --port 5000
5. Frontend (React)
   ```bash
   cd ai-interviewsim
    npm install
    npm run dev

---

## 🔁 CI/CD
GitHub Actions is configured to:

- ✅ Install dependencies
- 🧪 Run unit tests
- 📦 Build Docker image

---

## 🧑‍💻 Author
Eshna Gothalwal -------------- eshnagothawal666@gmail.com

---

## ⭐️ Show Your Support
If you liked this project:
- ⭐ Star the repo
- 🛠️ Create an issue or PR
- 📣 Share with your peers
