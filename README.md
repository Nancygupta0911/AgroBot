# 🌾 AgroBot – Your Smart Agricultural Assistant 🤖

AgroBot is an AI-powered multilingual chatbot designed to assist farmers with agricultural guidance, crop suggestions, weather updates, and more.  
Built with **Flask**, **Python**, and **Machine Learning**, AgroBot supports **text**, **voice commands**, and **image-based crop analysis** for a truly smart farming experience.

---

## 🚀 Features

### 🗣️ Multilingual Chatbot
- Supports **English, Hindi, Tamil, French, and Spanish**
- Automatically detects and responds in the user’s preferred language
- Translation powered by Google Translate / Deep Translator

### 🧑‍🌾 Personalized Farmer Profile
- Farmers can create and update their profiles  
- Fields include: **Name**, **Region**, **Primary Crop**, and **Preferred Language**  
- Data is securely stored in the database

### 🌦️ Weather & Crop Guidance
- Real-time weather updates using OpenWeather API  
- Provides crop-specific growth tips, irrigation schedules, and pest control suggestions

### 🧠 Image Analysis 
- Upload an image of a **crop, leaf, or pest**
- AgroBot analyzes it using a **CNN model (TensorFlow/PyTorch)**
- Detects possible crop diseases and suggests treatments

### 🎙️ Voice Interaction 
- Speak directly to AgroBot using your microphone  
- Converts speech to text using **SpeechRecognition (Google Speech API)**  
- AgroBot responds aloud using **gTTS (Text-to-Speech)**  

---

## 🌍 Tech Stack

| Layer | Technologies |
|-------|---------------|
| **Frontend** | HTML, CSS, JavaScript (Bootstrap) |
| **Backend** | Flask (Python) |
| **Database** | SQLite / PostgreSQL |
| **APIs** | OpenWeather, Google Translate, SpeechRecognition, gTTS |
| **ML Models** | TensorFlow / PyTorch for image recognition |

---


### 🧩 Folder Structure
```
AgroBot/
│
├── app.py # Main Flask application
├── requirements.txt # Python dependencies
│
├── templates/ # HTML (Jinja2 templates)
│ ├── base.html
│ ├── index.html
│ ├── chat.html
│ ├── profile.html
│ └── image_analysis.html
│
├── static/ # Static assets (CSS, JS, Images)
│ ├── css/
│ │ └── style.css
│ ├── js/
│ │ └── main.js
│ └── images/
│ ├── chat.png
│ ├── voice.png
│ └── image_analysis.png
│
├── models/ # Machine Learning models
│ └── crop_disease_model.h5
│
├── database/ # User and chat database
│ └── agro.db
│
├── utils/ # Helper scripts (language, voice, image)
│ ├── translator.py
│ ├── voice_helper.py
│ └── image_predict.py
│
├── config/ # Configuration and API keys
│ └── settings.py
│
└── README.md # Project documentation
```
---

### 📸 Screenshots
[Register]<img width="1900" height="926" alt="Screenshot 2025-11-01 144159" src="https://github.com/user-attachments/assets/c74a51c4-a963-43cb-9cd7-65a811a7beb2" />
[login]<img width="1887" height="923" alt="Screenshot 2025-11-01 144221" src="https://github.com/user-attachments/assets/8df8646d-b562-4cd3-b8c7-76513be20f16" />
<img width="1903" height="922" alt="Screenshot 2025-11-01 144251" src="https://github.com/user-attachments/assets/53be7a59-dba2-4aca-bfff-1b4dc6a8e515" />
[Your profile]<img width="1879" height="899" alt="Screenshot 2025-11-01 144341" src="https://github.com/user-attachments/assets/c51bd513-44a7-4427-9426-f3fd04116132" />
[Upload Image]<img width="1882" height="917" alt="Screenshot 2025-11-01 144431" src="https://github.com/user-attachments/assets/350ab400-3a9e-4e5f-af68-1c92503af516" />
[Image Analysis ]<img width="1882" height="910" alt="Screenshot 2025-11-01 144451" src="https://github.com/user-attachments/assets/b9d9fdd1-8782-4dc8-98f5-38aa46e50c1c" />







## ⚙️ Installation Guide

### 1️⃣ Clone the Repository
```bash
git clone https://github.com/Nancygupta0911/AgroBot.git
cd AgroBot
```
### 2️⃣ Create a Virtual Environment
```bash
python -m venv venv
source venv/bin/activate   # (Linux/Mac)
venv\Scripts\activate      # (Windows)
```
### 3️⃣ Install Dependencies
```bash
pip install -r requirements.txt
```
### 4️⃣ Run the Flask App
```bash
python app.py
```
Now open your browser and visit:
👉 http://127.0.0.1:5000
---

