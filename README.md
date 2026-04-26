SignBridge - Sign Language Translator & Learning Platform

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Python 3.13+](https://img.shields.io/badge/python-3.13+-blue.svg)](https://www.python.org/downloads/)
[![Flask](https://img.shields.io/badge/Flask-2.0+-green.svg)](https://flask.palletsprojects.com/)

**SignBridge** is a comprehensive web application that bridges communication gaps between hearing and deaf/hard-of-hearing individuals. It offers real-time two-way translation between sign language and speech, interactive learning modules, and emergency communication tools.

## ✨ Features

### 👐 Sign to Speech
- Real-time camera-based sign language detection
- Instant text translation with confidence scoring
- Text-to-speech output
- Quick phrase shortcuts

### 🗣️ Speech to Sign
- Voice recognition to convert spoken words to text
- Sign language animation generation
- Sign sequence display with replay functionality
- Manual text input option

### 📚 Learn Sign Language
- Structured lessons (alphabet, numbers, greetings, family, emotions)
- Progress tracking with visual indicators
- Practice mode with alphabet quiz
- Achievements system
- Daily challenges

### 🚨 Emergency Communication
- Pre-loaded emergency phrases (medical, safety, communication, location)
- One-tap emergency calls (911, poison control, crisis lines)
- Location sharing with GPS coordinates
- Emergency mode with auto-call feature
- Flashlight tool
- Save/Copy emergency phrases

### 👤 User System
- JWT-based authentication
- User progress saved to database
- Personalized learning experience

## 🛠️ Tech Stack

**Frontend:** HTML5, CSS3, JavaScript, TailwindCSS, Web Speech API, WebRTC

**Backend:** Flask, SQLite, JWT, OpenCV, Flask-CORS

## 🚀 Quick Start

### Prerequisites
- Python 3.13 or higher
- Modern web browser with camera & microphone access

### Installation

1. **Clone the repository**
```bash
git clone https://github.com/yourusername/signbridge.git
cd signbridge
```

2. **Create and activate virtual environment**
```bash
# Windows
python -m venv venv
venv\Scripts\activate

# macOS/Linux
python3 -m venv venv
source venv/bin/activate
```

3. **Install dependencies**
```bash
pip install flask flask-cors opencv-python numpy pyjwt flasgger
```

4. **Run the application**
```bash
python signbridge_backend.py
```

5. **Open your browser** to `http://localhost:5000`

## 📁 Project Structure

```
signbridge/
├── signbridge_backend.py    # Flask backend with API endpoints
├── index.html               # Homepage
├── sign-to-speech.html      # Sign to speech translation
├── speech-to-sign.html      # Speech to sign translation
├── learn.html               # Interactive learning module
├── emergency.html           # Emergency communication tools
├── test_backend.py          # Unit tests
├── test_backend_thorough.py # Extended tests
├── static/                  # Static assets (uploads, videos)
├── signbridge.db            # SQLite database (auto-created)
└── requirements.txt         # Python dependencies
```
