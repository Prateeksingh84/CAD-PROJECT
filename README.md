# 🔊 Angry Alexa – A Python-Based Voice Assistant

## 🧠 Project Overview

**Angry Alexa** is a Python-powered voice assistant designed for interactive and entertaining user experiences. Unlike conventional assistants, Angry Alexa responds with humorous, sarcastic, or "angry" tones, making it a fun and engaging personal assistant. It performs a range of tasks such as telling jokes, opening websites, announcing the time, and more.

## 🚀 Features

- 🎤 Voice input and speech recognition
- 💬 Voice responses with a sarcastic twist
- ⏰ Announces time on command
- 🎵 Plays music or opens YouTube
- 😂 Tells jokes in a witty tone
- 🧠 Modular structure with extendable commands
- 🖥️ Lightweight GUI (optional)


## 🛠️ Tech Stack

- **Python 3.8+**
- `speech_recognition` – for voice input
- `pyttsx3` – for text-to-speech
- `pyjokes` – for humor responses
- `webbrowser` – to open URLs
- `datetime` – to get the current time
- `os`, `random` – for system-level tasks

## 🧠 Technology & Algorithm Used

- **Speech Recognition Algorithm**: Converts audio to text using Google’s speech-to-text engine (`speech_recognition`).
- **Text-to-Speech Engine**: Uses `pyttsx3` for offline TTS, allowing customized voice output in an angry/sarcastic tone.
- **Command Processing Logic**: Input text is matched against keywords using conditional logic (if-else and dictionary mapping).
- **Modular Structure**: Each function (jokes, music, time) is separated into reusable modules.
- **Randomization**: Used to pick random jokes or angry phrases for diverse responses.
- **Web Automation**: Opens URLs like YouTube using `webbrowser.open()` for media tasks.

## 🧪 How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/angry_alexa.git
   cd angry_alexa
   
2. Install the dependencies:
  ```bash
   pip install -r requirements.txt

3. Run the assistant:
 ```bash
   python main.py

## 🎯 Example Commands
"Alexa, what time is it?"

"Tell me a joke"

"Play something on YouTube"

"I'm bored" → Angry Alexa will respond with attitude 😠

## 💡 Customization Tips
Edit the joke_module.py to add your own jokes

Modify utils.py to change the assistant's tone or add filters

Add more intent modules to extend Alexa's capabilities

## 🤖 Project Goals
Explore natural language interfaces in Python

Build a fun, expressive alternative to standard voice assistants

Practice modular design and voice interaction libraries


