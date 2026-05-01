# 🧠 ThinkMirror — AI-Powered Decision Analysis App

## 🔗 Project Repositories
- 💻 Frontend: https://github.com/ALIM23700/ThinkMirror_Frontend 
- ⚙️ Backend:https://github.com/ALIM23700/ThinkMirror_Backend  

## 🌐 Live Demo
👉 https://think-mirror-frontend.vercel.app/

---

## 🧩 Project Overview
ThinkMirror is an AI-powered web application designed to help users analyze their thoughts and decisions more logically.  
Users can write their thoughts, and the system generates counter-arguments and alternative perspectives using AI.

The goal of this project is to reduce biased thinking and improve decision-making through structured analysis.

---

## ⚙️ Tech Stack
- **Frontend:** Next.js, Tailwind CSS  
- **Backend:** Node.js, Express.js  
- **Database:** MongoDB  
- **Authentication:** JWT  
- **AI Integration:** Gemini API (text analysis)  
- **Deployment:** Vercel (frontend), Render (backend)

---

## ✨ Features
- 🧠 AI-generated **counter-arguments & analysis**  
- 🔐 **User authentication** (Signup/Login/Logout)  
- 📝 Create, edit, and delete **thought entries**  
- 📜 **History tracking** of all previous thoughts  
- ⚡ Instant UI updates after actions  
- 📱 Fully responsive design (mobile + desktop)  
- 🔒 Protected routes (only logged-in users can access features)  

---

## 🧠 How It Works (Architecture)

Frontend (React)  
↓  
REST API (Express.js)  
↓  
AI Processing (API)  
↓  
MongoDB (Stores thoughts & results)

---

## 🚧 Challenges & Learnings
- Handling async AI responses efficiently using async/await  
- Managing authentication state across the app  
- Designing clean REST APIs for CRUD operations  
- Securing routes using JWT middleware  
- Structuring user thought history for better UX  

---

## 📁 Project Structure
- Frontend → UI, routing, state management  
- Backend → API, authentication, AI integration  
- Database → Stores user data & thoughts  

---

## ⚙️ Setup Instructions

To run locally, check the individual repositories:

- **Frontend:**https://github.com/ALIM23700/ThinkMirror_Frontend 
- **Backend:** https://github.com/ALIM23700/ThinkMirror_Backend

Follow setup instructions in each repo.

---

## 📸 Screenshots

### Home Page
![Home Page](screenshots/Home.png)

### Thought History
![History Page](screenshots/history.png)

### Login Page
![Login Page](screenshots/login.png)

### Signup Page
![Signup Page](screenshots/signup.png)

---

## 🚀 Future Improvements
- Add sentiment analysis visualization (charts)  
- Improve AI accuracy with better prompt engineering  
- Add dark/light theme toggle  
- Enable sharing thoughts publicly  
- Add role-based admin dashboard  

---

## 💯 Key Highlights
- Full-stack MERN architecture  
- AI-powered functionality (beyond basic CRUD apps)  
- Clean and responsive UI  
- Secure authentication system  
- Real-world problem-solving approach  

---

## ⚠️ Important Notes
- AI responses depend on external API limits  
- Ensure API key is properly configured  
- Use sandbox/testing mode if API has quota limits  
