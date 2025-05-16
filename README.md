# Voice Assistant

This is a simple Python-based voice assistant that listens to your voice commands, performs tasks such as telling the time, opening applications, searching the web, and responds using text-to-speech.

---

## Features

- Recognizes voice commands using Google's speech recognition API.
- Speaks responses using `pyttsx3` text-to-speech engine.
- Can tell the current time.
- Opens Notepad and Calculator on Windows.
- Performs Google searches based on voice input.
- Gracefully exits on commands like "bye", "exit", or "quit".

---

## Requirements

- Python 3.x
- `speechrecognition` library
- `pyttsx3` library
- `pyaudio` library (for microphone input)
- `datetime` (built-in)
- `webbrowser` (built-in)
- `os` (built-in)

---

## Installation

Use pip to install the required Python packages:

```bash
pip install SpeechRecognition pyttsx3 pyaudio
