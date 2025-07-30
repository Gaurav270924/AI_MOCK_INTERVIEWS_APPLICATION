# 🧠 MockMate – AI-Powered Mock Interview App

> An intelligent mock interview platform where users can practice interviews with a voice-based AI assistant built using Google Gemini, Firebase, and Vapi.

![App Screenshot](https://your-screenshot-link-if-any.com) <!-- Optional -->

---

## 🔗 Live Demo

👉 [Try the Live App](https://ai-mock-interviews-application-rirz.vercel.app/)

---

## ✨ Features

- 🎙️ Voice-enabled mock interviews (Vapi Integration)
- 🤖 AI-generated interview questions (Google Gemini)
- 🔐 Firebase Authentication
- 💾 Store user feedback and history with Firestore
- ⚡ Deployed using Vercel
- 📱 Responsive UI built with React + Tailwind

---

## 🛠️ Getting Started Locally

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/your-repo-name.git
cd AI_MOCK_INTERVIEWS_APPLICATION

# Install Dependencies

npm install

# Set Up Environment Variables

## Create a .env.local file in the root directory and add the following:

# Firebase Client
NEXT_PUBLIC_FIREBASE_API_KEY=your_key
NEXT_PUBLIC_FIREBASE_AUTH_DOMAIN=your_project.firebaseapp.com
NEXT_PUBLIC_FIREBASE_PROJECT_ID=your_project
NEXT_PUBLIC_FIREBASE_STORAGE_BUCKET=your_project.appspot.com
NEXT_PUBLIC_FIREBASE_MESSAGING_SENDER_ID=your_sender_id
NEXT_PUBLIC_FIREBASE_APP_ID=your_app_id
NEXT_PUBLIC_FIREBASE_MEASUREMENT_ID=your_measurement_id
# Firebase Admin
FIREBASE_PROJECT_ID=your_project
FIREBASE_PRIVATE_KEY=-----BEGIN PRIVATE KEY-----\n...\n-----END PRIVATE KEY-----
FIREBASE_CLIENT_EMAIL=your_admin_sdk_email
# Vapi
NEXT_PUBLIC_VAPI_WEB_TOKEN=your_vapi_web_token
NEXT_PUBLIC_VAPI_WORKFLOW_ID=your_workflow_id
# Gemini AI
GOOGLE_GENERATIVE_AI_API_KEY=your_gemini_key

# Start the Development Server

npm run dev

Your app will be running at: http://localhost:3000

