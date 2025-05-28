## 🗣️ Project 03 – Voice Assistant (AI Speech Bot)

### 📄 Description:

This project is a **Voice Assistant Web App** that allows users to interact with an AI model using **voice input and output**. The assistant listens to the user's speech, processes it using an LLM (Large Language Model), and responds audibly using **text-to-speech (TTS)**.

The app provides a natural and interactive conversational experience, bridging speech recognition with modern AI capabilities.

---

### 🛠️ Features:

- 🎙️ Speech recognition using `SpeechRecognition` and `pyaudio`
- 🧠 AI-powered responses (mocked or via language model)
- 🔊 Voice replies using `pyttsx3` text-to-speech
- 📟 Simple and intuitive command-line interface
- 🧩 Modular code structure for easy updates and enhancements

---

### 📂 Main Files:

| File         | Description                              |
|--------------|------------------------------------------|
| `server.py`     | Main logic for capturing voice, generating response, and speaking it |
| `requirements.txt` | List of Python dependencies              |

---

### ⚙️ Requirements:

- ✅ Python 3.7+
- 🎤 Microphone enabled and configured
- 🔈 Working audio output device

---

### 🚀 How to Run:
# Step 1: Install dependencies:
     ```bash
     pip install -r requirements.txt

---


### ▶️ 
# Step 2: Run the assistant:
      ```bash
    docker build . -t voice-chatapp-powered-by-openai
    docker run -p 8000:8000 voice-chatapp-powered-by-openai
