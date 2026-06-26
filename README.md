# Jarvis – Intelligent Desktop AI Assistant

Jarvis is a Python-based intelligent desktop assistant designed to automate everyday computer tasks using voice commands, large language models (LLMs), speech recognition, text-to-speech, desktop automation, and a custom graphical user interface. The project focuses on creating a modular, extensible assistant capable of handling both conversational queries and productivity-oriented automation.

---

## Overview

Jarvis combines multiple AI and automation technologies into a unified desktop application. It accepts voice input, interprets user intent, generates intelligent responses using LLMs, performs system-level automation, and communicates results through natural speech.

The project is organized using a modular architecture, making it easy to extend with new automation capabilities and AI models.

---

## Features

- Voice-controlled interaction
- Speech-to-Text (STT)
- Text-to-Speech (TTS)
- Wake-word based activation
- LLM-powered conversational AI
- Real-time web search
- Desktop automation
- Application launcher
- Browser automation
- WhatsApp messaging automation
- Media playback control
- Custom graphical user interface (PyQt6)
- Modular backend architecture
- Environment-based configuration using `.env`

---

## Technology Stack

### Programming Language

- Python

### Artificial Intelligence

- Google Gemini API
- Ollama
- OpenClaw
- SpeechRecognition

### GUI

- PyQt6

### Automation

- PyAutoGUI
- AppOpener
- Requests

### Utilities

- Python Dotenv
- Asyncio
- Threading
- JSON

---

## System Architecture

```
                    User Voice
                        │
                        ▼
             Speech Recognition Module
                        │
                        ▼
              Intent Identification
                        │
      ┌─────────────────┼──────────────────┐
      │                 │                  │
      ▼                 ▼                  ▼
 Conversation      Automation        Web Search
      │                 │                  │
      └─────────────────┼──────────────────┘
                        │
                        ▼
            Response Generation Module
                        │
                        ▼
                 Text-to-Speech
                        │
                        ▼
                      User
```

---

## Project Structure

```
Jarvis/
│
├── Backend/
│   ├── Automation.py
│   ├── Chatbot.py
│   ├── Model.py
│   ├── RealtimeSearchEngine.py
│   ├── SpeechToText.py
│   ├── TextToSpeech.py
│   └── ...
│
├── Frontend/
│   ├── GUI.py
│   ├── Assets/
│   └── ...
│
├── Data/
│
├── main.py
├── requirements.txt
├── .env.example
└── README.md
```

---

## Installation

Clone the repository

```bash
git clone https://github.com/atharva31-alt/Jarvis.git
```

Navigate to the project directory

```bash
cd Jarvis
```

Install the dependencies

```bash
pip install -r requirements.txt
```

Create a `.env` file using the provided `.env.example` template and add the required API credentials.

Run the application

```bash
python main.py
```

---

## Configuration

The application requires external API credentials and user-specific configuration.

The following files are intentionally excluded from the repository:

- `.env`
- Personal contact lists
- Authentication credentials
- API keys
- Local configuration files

An example configuration file can be provided without exposing any sensitive information.

---

## Screenshots

Add screenshots demonstrating the application here.

Example:

```
Screenshots/
├── MainWindow.png
├── ListeningMode.png
├── VoiceInteraction.png
└── AutomationDemo.png
```

---

## Demonstration

A short demonstration video or GIF showing the following workflow is recommended:

1. Wake-word activation
2. Voice command recognition
3. Conversational response
4. Desktop automation
5. Web search
6. WhatsApp messaging
7. Media control

---

## Current Capabilities

- Voice interaction
- Conversational AI
- Desktop automation
- Browser automation
- Application control
- Web search
- WhatsApp messaging
- Media playback control
- Modular AI pipeline
- GUI-based interaction

---

## Future Improvements

- Cross-platform support
- Plugin-based architecture
- Local LLM optimization
- Enhanced long-term memory
- Voice customization
- Additional automation modules
- Calendar and email integration
- Smart scheduling capabilities

---

## Security Notice

Sensitive information has been intentionally excluded from this repository.

This includes:

- API keys
- Personal contacts
- Authentication credentials
- Environment configuration
- User-specific data

The published source code demonstrates the project's architecture and core functionality while protecting private information.

---

## License

This repository is intended for educational and portfolio purposes.

---

## Author

**Atharva Anand**

B.Tech Computer Science & Engineering

Artificial Intelligence • Machine Learning • Intelligent Agents • Full-Stack Development

GitHub: https://github.com/atharva31-alt
