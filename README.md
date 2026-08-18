# 🎙️ Nova Voice Agent

> A browser-based voice-controlled assistant built with Python, Flask, HTML, CSS, and JavaScript.

Nova Voice Agent allows users to interact with a web application using natural voice commands. The application captures speech through the browser, sends the recognized command to a Python Flask backend, processes the command, and performs actions such as searching YouTube or preparing an email draft.

---

## 🚀 Demo

🌐 **Live Demo:** Add your Render deployment URL here

📦 **GitHub Repository:** Add your GitHub repository URL here

---

## ✨ Features

- 🎤 Voice-based command input
- 🧠 Python-based command processing
- 🌐 Flask backend
- 🎨 Modern responsive web interface
- ▶️ YouTube search and video playback
- 📧 Gmail email draft generation
- 🔊 Browser Speech Recognition API
- ⚡ Real-time command processing
- 🌌 Animated futuristic UI
- ☁️ Deployable using Render
- 🔗 GitHub-based deployment workflow

---

## 🛠️ Technologies Used

### Frontend

- HTML5
- CSS3
- JavaScript
- Web Speech API
- Responsive UI
- CSS animations

### Backend

- Python
- Flask
- Regular Expressions
- urllib
- JSON

### Deployment

- GitHub
- Render

---

## 🏗️ System Architecture

```text
              ┌─────────────────────┐
              │       User          │
              │   Voice Command     │
              └──────────┬──────────┘
                         │
                         ▼
              ┌─────────────────────┐
              │   Browser Frontend  │
              │ HTML + CSS + JS      │
              └──────────┬──────────┘
                         │
                  Speech Recognition
                         │
                         ▼
              ┌─────────────────────┐
              │    Flask Backend    │
              │      Python         │
              └──────────┬──────────┘
                         │
                  Command Processing
                         │
              ┌──────────┴──────────┐
              │                     │
              ▼                     ▼
        YouTube Search         Email Draft
              │                     │
              ▼                     ▼
        YouTube Video          Gmail Compose
