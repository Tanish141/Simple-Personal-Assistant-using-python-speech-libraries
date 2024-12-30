## 🗣️ Simple Personal Assistant

This project implements a **voice-based personal assistant using Python's speech libraries**. The assistant can recognize voice commands, perform various actions like telling the time, opening websites, and more, while interacting with the user through speech.

---

## 🚀 Features
- Speech Recognition 🎤:
- Listens to user commands via microphone.
- Recognizes spoken words using Google's Speech Recognition API.

- Text-to-Speech 🗣️:
- Responds to user commands through a synthesized voice using pyttsx3.

- Command Execution ⚡:
- Provides the current time.
- Opens web browsers to search queries.
- Launches local applications like Safari and Calculator (system-specific).

---

## Interactive and Continuous 🔄:
Continuously listens and responds until the user exits.

---

## 🛠️ Technologies Used
- Python 🐍: Core programming language.
- SpeechRecognition: For recognizing spoken words.
- pyttsx3: For text-to-speech functionality.
- datetime: For fetching the current time.
- webbrowser: For opening web searches.
- os: For launching system-specific applications.

---

## 🚀 How to Run
1. Set Up the Environment

Create a Virtual Environment:

python -m venv speechenv

Activate the Environment:

Windows:

speechenv\Scripts\activate

macOS/Linux:

source speechenv/bin/activate

Install Dependencies:

pip install -r requirements.txt

2. Run the Assistant

python assistant.py

---

## 🛠️ Usage Instructions

Start the Assistant:

The assistant will greet you and start listening for commands.

Commands Supported:

"Hello" or "Hi":

Responds with a friendly greeting.

"Time":

Announces the current time.

"Search [query]":

Opens a web browser and searches for the query.

"Open [application]":

Opens specific applications like Safari or Calculator (system-specific).

"Bye", "Exit", or "Quit":

Exits the assistant.

Provide Input:

Speak your commands clearly into the microphone.

Interactive Experience:

The assistant continuously listens and responds until you exit.

---

## 📦 Requirements

Python 3.7+

Libraries:

speechrecognition

pyttsx3

datetime

webbrowser

os

Install Dependencies:

pip install SpeechRecognition pyttsx3

---

## 🌟 Future Enhancements

Add support for more applications.

Include weather updates and reminders.

Enhance error handling for network-dependent tasks.

---

## 🤝 Contributions

Contributions are welcome! Feel free to fork the repository, create a feature branch, and submit a pull request. 🌟

---

## 📧 Contact

For any questions or suggestions, feel free to reach out:

Email: mrtanish14@gmail.com
GitHub: [Your GitHub Profile](https://github.com/Tanish141)

---

**🎉 Enjoy Using Your Personal Assistant!**


