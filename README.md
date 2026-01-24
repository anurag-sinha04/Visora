# 🌐 Visora — Inclusive Communication Platform  
**Breaking Language Barriers Through Sign Language, Speech, and Real-Time Accessibility**

🔗 **Live Platform:** https://anurag-sinha04.github.io/Visora/  
🏆 **Hackathon Winning Project**

---

## ☁ Deployment Note (Free Infrastructure)

Some modules such as **Vernacular Translation** and **Sign-Based Video Conferencing** are deployed on **Render free-tier servers** due to budget constraints during hackathon prototyping.

Because of this:
- The first request may take **10–30 seconds** to wake the server.
- Initial loading delay is expected.
- After warm-up, performance is real-time and stable.

This demonstrates a **production-grade system built under minimal-cost constraints**, suitable for accessibility research and hackathon evaluation.

---

## ✨ Introduction

**Visora** is a unified assistive communication ecosystem built to empower:

- Deaf and Hard-of-Hearing individuals  
- Speech-impaired users  
- Multilingual communities  
- Inclusive classrooms  
- Accessible remote collaboration  

It integrates **Sign Language Animation, Speech Recognition, Translation, Video Conferencing, and Intelligent Summarization** into one seamless platform.

---

## 🧠 Vision

> “Communication should never be a barrier to opportunity.”

Visora aims to become a **universal accessibility layer** for digital interaction.

---

## 🧩 Core Modules

### 🖐 Text → Sign Language  
Converts typed or spoken sentences into sign language videos.

### 🎥 Sign → Text *(Under Development)*  
Recognizes sign gestures from video and generates readable text.

### 🌍 Vernacular Translation  
Real-time multilingual speech translation.

### 📞 Sign-Based Video Conferencing  
Live WebRTC video calls with sign overlay and captions.

### 📝 Text Summarizer  
Converts long content into concise notes.

---

## 🚀 Key Highlights (USP)

- ⚡ Ultra-low latency video conferencing (~20ms)  
- ♿ Accessibility-first design  
- 🌐 Browser-based, no installation  
- 🔁 Real-time sign animation  
- 🏆 Hackathon award-winning system  

---

## 🏗 Technology Stack

**Frontend:**  
HTML, CSS, JavaScript, TailwindCSS, Web Speech API  

**Realtime:**  
WebRTC, Socket.IO, PeerJS  

**Backend (Optional):**  
Node.js (Express), Python (NLP/ML)

---

## 📦 Installation & Local Setup

```bash
# 1. Clone repository
git clone https://github.com/anurag-sinha04/Visora.git
cd Visora

# 2. Run Frontend
# Open index.html directly
# or use Live Server in VS Code

# 3. Run Backend (Optional for Realtime & AI)
npm install
npm start

# 4. (Optional Python Services)
pip install -r requirements.txt
python app.py
