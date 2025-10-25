# Friday - Your Personal AI Assistant

## Description
A Python-based AI assistant, "Jarvis," that can perform various tasks via voice and text, such as:

* Opening websites (YouTube, Google, Wikipedia, etc.)
* Playing music files
* Telling the current time
* Opening specific folders (ML folder, VS Code)
* Chatting with a large language model (using Gemini)
* Saving chat logs
* Voice command input using speech recognition
* Text-to-speech output

---

## Features Implemented

- 🔗 Open websites by voice command
- 🎵 Play music from a specific directory
- 🕒 Tell the current time
- 📂 Open predefined folders
- 🤖 Converse with Gemini (Google Generative AI)
- 📝 Save chat logs to local files

---

## Code Description

- `config.py`: Stores the Gemini API key
- `main.py`: Main script to run Jarvis

---

## Dependencies

- `speech_recognition`
- `pywin32`
- `webbrowser`
- `google.generativeai`
- `datetime`
- `os`
- `sys`

---

## Setup Instructions

1. **Install Dependencies:**
    ```bash
    pip install SpeechRecognition pypiwin32 google-generativeai
    ```

2. **Configure Gemini API Key:**
    Create a file named `config.py` and add:
    ```python
    apiKey = "YOUR_API_KEY"
    ```

3. **Set Music Paths (Optional):**
    Edit the `musics` list in `main.py` to point to your songs.

4. **Run Jarvis:**
    ```bash
    python main.py
    ```

---

## Demo Videos

### 🔹 Jarvis 1
[Watch Jarvis 1 Demo](https://github.com/pragya-singh-17/Jarvis-AI-assistant/blob/main/Jarvis%201.mp4)

### 🔹 Jarvis 2
[Watch Jarvis 2 Demo](https://github.com/pragya-singh-17/Jarvis-AI-assistant/blob/main/Jarvis%202.mp4)

---

