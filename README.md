# AI Gym Real-Time Coach 🏋️‍♂️🤖

An intelligent, real-time fitness application that uses computer vision to track workout form, count repetitions, and deliver live audio coaching powered by Large Language Models (LLMs).

---

## ⚡ Quick Features
* **Live Motion Tracking:** Real-time pose estimation for **Squats, Push-ups, and Curls**.
* **Smart Form Correction:** Instantly detects incorrect posture and offers fixes.
* **LLM Audio Coach:** Generates dynamic, human-like voice feedback using the Groq API and gTTS.
* **Workout Analytics:** Tracks historical progress, rep counts, and goals using an SQLite database.

---

## 🛠️ Tech Stack
* **Frontend:** Streamlit & Streamlit-WebRTC
* **AI & Vision:** MediaPipe, OpenCV, Groq LLM API
* **Data & Voice:** SQLite, Pandas, gTTS (Google Text-to-Speech)

---

## 🔄 Core Workflows

### 1. Video Processing Loop
`Streamlit WebRTC` ➡️ `Video Processor` ➡️ `MediaPipe Model` ➡️ `Database Logging` ➡️ `UI Update`

### 2. Voice Feedback Pipeline
`Metrics/Form Alert` ➡️ `Voice Processor` ➡️ `Groq LLM Engine` ➡️ `Text-to-Speech Output`

