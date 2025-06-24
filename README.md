# 🤖 QueryAI Assistant

**QueryAI** is an open-source AI assistant built with Python that combines **voice**, **vision**, **memory**, and **emotions** — all controlled with a simple wake word: **"Q open up"**.

![QueryAI Logo](website/icon.ico)

---

## 🚀 Features

- 🎤 **Voice Interaction** – Speak naturally with speech-to-text and AI-powered replies
- 🧠 **Persistent Memory** – Remembers past chats in a JSON database
- 😃 **Emotion Detection** – Reacts differently based on your emotional tone
- 🔍 **Wake Word Activation** – Always listening for _"Q open up"_
- 👁️ **Vision AI** – Webcam support for face/object detection (OpenCV & deep learning)
- 💬 **Chat & Knowledge Search** – Integrated Wikipedia lookup and LLM chatbot
- 💾 **SQLite/JSON Storage** – Lightweight memory and logging
- 📦 **Installer Ready** – Signed `.exe` installer for Windows included

---

## 🛠️ Installation

### 📦 Windows

1. [Download the latest installer](https://yourusername.github.io/QueryAI-Assistant/website/QueryAI_Installer.exe)
2. Run the installer
3. Launch with `queryAISetup.exe` or the Start Menu shortcut

---

## 🧪 Run From Source

> Requires Python 3.9+

```bash
git clone https://github.com/YOUR_USERNAME/QueryAI-Assistant.git
cd QueryAI-Assistant
pip install -r requirements.txt
python your_script.py
```

---

## 🌐 Website

🔗 Live demo: [https://yourusername.github.io/QueryAI-Assistant/website](https://yourusername.github.io/QueryAI-Assistant/website)

---

## 📂 Directory Structure

```
QueryAI-Assistant/
├── your_script.py         # Main AI assistant
├── launcher.py            # GUI launcher
├── launch_ai.bat          # Simple batch launcher
├── chat_memory.json       # Memory store
├── requirements.txt       # Dependencies
├── queryAI_installer.iss  # Inno Setup installer script
├── website/               # GitHub Pages site
│   ├── index.html
│   ├── icon.ico
│   └── QueryAI_Installer.exe
```

---

## 📜 License

This project is licensed under the [MIT License](LICENSE).

---

## 🤝 Contributing

Pull requests are welcome. For major changes, open an issue first to discuss what you’d like to change.

---

## 💬 Credits

Built with ❤️ using:
- OpenAI GPT (via local or cloud)
- SpeechRecognition, pyttsx3, OpenCV
- SQLite & JSON
- Ursina, custom GUI launcher
- Inno Setup for packaging

---

## 🔒 Signed Open-Source

This installer is signed using [SignPath.io](https://signpath.io/open-source/). All releases are verified and safe to run.
