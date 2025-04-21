# 🛠️ Trident Builders – Voice-Driven Daily Reporting App

A fully voice-automated web and phone-based app that enables construction field crews to submit daily reports hands-free. Built for Trident Builders LLC, this project streamlines data entry by transcribing speech, extracting structured information, and generating formatted Excel reports in real-time.

---

## 🚀 Features

- 🎙️ **Voice Input**: Workers submit reports via voice using a web app or phone call (Twilio).
- 🧠 **AI-Powered Understanding**: Uses OpenAI Whisper for transcription + GPT for understanding and data extraction.
- 📋 **Dynamic Question Flow**: Adapts based on answers — e.g., asks for multiple work entries, tools used, contractors involved.
- 📍 **Automatic Weather & Location Fill**: Auto-fills local weather data and GPS location for each report.
- 📊 **Excel Generation**: Creates structured Excel sheets in a company-approved format.
- 📱 **Browser + Phone Support**: Built-in Flutter frontend for mobile use; Flask backend supports both platforms.

---

## 🧠 Tech Stack

- **Frontend**: HTML (web) / Flutter (mobile)
- **Backend**: Flask (Python)
- **AI/NLP**: OpenAI Whisper + GPT (via OpenAI API)
- **Excel Handling**: OpenPyXL
- **Voice Pipeline**: Twilio (for phone integration), gTTS (for voice responses)
- **Hosting**: Can be deployed on Heroku, Render, or local server

---

## 📦 Demo

> 🎥 [Insert link to Loom or YouTube demo here if available]  
> 📁 Includes: real-time interaction + generated Excel file walkthrough.

---

## 📂 Folder Structure

```bash
Trident_Builders/
├── backend/                # Flask API
│   ├── app.py              # Core logic
│   ├── utils/              # Whisper, GPT, Excel helper modules
│   └── templates/          # Excel templates
├── frontend/               # HTML or Flutter UI
├── excel_reports/          # Generated Excel outputs
└── README.md               # This file
