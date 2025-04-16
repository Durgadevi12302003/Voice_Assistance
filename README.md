# 🗣️ Voice Assistant using Python

This is a simple yet powerful Python-based voice assistant that listens to your voice commands and performs tasks accordingly. It can speak text, convert speech into text, search the web, read PDF and Word documents, and much more — all through natural voice interaction.

---

## ✨ Features

- 🔊 **Voice Activation** – Start the assistant by saying **"Hello Python"**
- 🗣️ **Text to Speech** – Converts your typed or spoken text into audio
- 🎙️ **Speech to Text** – Captures your speech and converts it into written text
- 🌐 **Google Search** – Searches the web via voice commands
- 📚 **Wikipedia Search** – Retrieves summaries of topics from Wikipedia
- 📄 **Read Word Documents** – Opens and reads `.docx` files aloud
- 📘 **Read PDF Documents** – Reads content from PDF files
- 🧭 **Interactive Menu System** – Guides users through all available features
- 🛑 **Voice Command to Exit** – Say "Close" or "Close Python" to stop the assistant

---

## 🛠️ Technologies Used

- **Python**
- `speech_recognition` – To capture and interpret spoken words
- `pyttsx3` or `gTTS` – For converting text to speech
- `PyPDF2` or `fitz` (PyMuPDF) – For reading PDF content
- `python-docx` – To extract content from Word documents
- `wikipedia` – To fetch article summaries
- `webbrowser` – To open search results
- `colorama` – To add colors to terminal text

---

## 📁 Project Structure

```
project-folder/
│
├── main.py             # Main driver script to start the assistant
├── speakListen.py      # Manages voice input and speaking output
├── websiteWork.py      # Contains Google and Wikipedia search functions
├── textRead.py         # Functions to read from PDF and Word files
├── dictator.py         # Optional module for extra command handling
├── menu.py             # Displays available features/options
├── speechtotext.py     # Handles long speech-to-text conversion
├── TextTospeech.py     # Manages text-to-speech conversion
```

---

## ▶️ How to Run the Project

1. **Install the required dependencies** using pip:

```bash
pip install speechrecognition pyttsx3 PyPDF2 python-docx wikipedia colorama
python main.py
```
---
## 🗣️ Voice Menu Commands

Use the voice menu to explore options like:

- `"Text to Speech"` – Convert typed or spoken text to audio
- `"Search on Google"` – Perform a quick Google search
- `"Search on Wikipedia"` – Fetch summaries from Wikipedia
- `"Word"` – Open and read a Word document
- `"Book"` – Open and read a PDF file
- `"Speech to Text"` – Convert spoken words into written text
- `"Close"` – Exit the assistant
## ❗ Notes

- Ensure your **microphone** is connected and working properly.
- An active **internet connection** is required for Google and Wikipedia search.
- For the best experience, **speak clearly** and avoid background noise.
- You can **customize or add new features** by editing the respective Python modules.


## 🙌 Acknowledgments

This project was developed as a part of a **Python voice assistant initiative** using natural language libraries and speech APIs.  
It draws inspiration from popular virtual assistants like **Siri**, **Alexa**, and **Google Assistant** — simplified for **learning**, **experimentation**, and **project use**.


## 📌 License

This project is **open-source** and free to use for **educational** or **personal** purposes.  
Feel free to **fork it**, **enhance it**, and **share your improvements**!




