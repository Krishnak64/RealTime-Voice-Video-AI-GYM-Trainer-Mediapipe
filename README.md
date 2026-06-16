# 🏋️‍♂️ AI Realtime Gym Coach

An intelligent **AI/ML-powered real-time gym trainer** that monitors your workout using your webcam and acts as a virtual fitness coach. It tracks body movements, analyzes posture, counts repetitions, and provides real-time voice feedback to improve exercise performance and reduce injury risk.

🚀 Live Demo: https://ai-gym-coach-live.netlify.app/  
📦 GitHub Repo: https://github.com/Krishnak64/RealTime-Voice-Video-AI-GYM-Trainer-Mediapipe  

---

## 🔥 Features

- 🎯 Real-time pose detection using MediaPipe
- 💪 Automatic rep counting for workouts
- 🧠 AI-based posture and form correction
- 📹 Live webcam-based tracking using Streamlit WebRTC
- 🔊 Voice feedback using gTTS (Text-to-Speech)
- 🤖 AI coaching using Groq LLM API
- 📊 Workout analytics and performance tracking
- ⚡ Low-latency real-time processing

---

## 🛠️ Tech Stack

- **Frontend/UI:** Streamlit 1.54.0  
- **Real-time Video:** streamlit-webrtc 0.64.5  
- **Computer Vision:** OpenCV, MediaPipe  
- **Data Processing:** Pandas 2.2.3  
- **AI Model:** Groq API (LLM Coaching)  
- **Voice Feedback:** gTTS  
- **Environment:** python-dotenv  

---

## 🧠 How It Works

1. User selects an exercise (Squats, Push-ups, etc.)
2. Webcam captures real-time body movement
3. MediaPipe detects body landmarks
4. AI analyzes posture & rep count
5. Groq AI provides intelligent coaching feedback
6. gTTS converts feedback into voice instructions

---

## 🏃‍♂️ Supported Exercises

- Squats  
- Push-ups  
- Biceps Curls  
- Shoulder Press  
- Lunges  

---
C:\Users\krish\OneDrive\Desktop\PrimeAIML\ML_Projects\AI-Realtime-GYM-Coach-LandingPage\IMGs\i1.png
C:\Users\krish\OneDrive\Desktop\PrimeAIML\ML_Projects\AI-Realtime-GYM-Coach-LandingPage\IMGs\i2.png
C:\Users\krish\OneDrive\Desktop\PrimeAIML\ML_Projects\AI-Realtime-GYM-Coach-LandingPage\IMGs\i3.png
C:\Users\krish\OneDrive\Desktop\PrimeAIML\ML_Projects\AI-Realtime-GYM-Coach-LandingPage\IMGs\i4.png
C:\Users\krish\OneDrive\Desktop\PrimeAIML\ML_Projects\AI-Realtime-GYM-Coach-LandingPage\IMGs\i5.png
C:\Users\krish\OneDrive\Desktop\PrimeAIML\ML_Projects\AI-Realtime-GYM-Coach-LandingPage\IMGs\i6.png

---
Project Structure :

AI-Realtime-GYM-Coach/
│
├── main.py
├── requirements.txt
├── .gitignore
├── .env (not pushed)
│
├── services/
│   ├── vision/
│   │   └── exercise_video_processor.py
│   ├── coaching/
│   │   ├── llm.py
│   │   ├── tts.py
│   │   └── voice_pipeline.py
│   ├── tracking/
│   ├── persistence/
│   ├── ui/
│
├── static/
├── ml_models/
└── core/

---

python -m venv venv
venv\Scripts\activate   # Windows

## ⚙️ Installation (Run Locally)

```bash
git clone https://github.com/Krishnak64/RealTime-Voice-Video-AI-GYM-Trainer-Mediapipe.git
cd RealTime-Voice-Video-AI-GYM-Trainer-Mediapipe

pip install -r requirements.txt

streamlit run main.py
