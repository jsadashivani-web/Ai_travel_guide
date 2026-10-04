# AI Travel Guide 🌍

An AI-powered travel guide that generates informative descriptions of famous destinations and converts them into natural-sounding audio guides.

## Features

- 🌍 Explore famous destinations
- 🤖 AI-generated travel descriptions
- 🔊 AI voice generation using Murf AI
- 🧠 Google Gemini integration
- 🌐 Multiple language support
- 🎙️ Male and female voice options
- 📖 Summary and detailed descriptions
- 💻 Interactive web interface

## Technologies

- HTML
- JavaScript
- Tailwind CSS
- Python
- Flask
- Google Gemini API
- Murf AI API

## Project Structure

```text
AI-Travel-Guide/
├── Backend/
│   ├── app.py
│   └── requirements.txt
├── Frontend/
│   ├── index.html
│   └── index.js
├── .gitignore
└── README.md


How It Works
User selects a destination.
User chooses language and voice.
The frontend sends the request to the Flask backend.
Gemini generates the travel description.
Murf AI converts the description into speech.
The generated description and audio are returned to the frontend.
The user can read and listen to the AI travel guide.

