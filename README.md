# Jarvis – Voice Assistant

Jarvis is a Python-based desktop voice assistant that performs tasks using voice commands. It can recognize speech, respond using text-to-speech, search the web, fetch Wikipedia summaries, take screenshots, check system status, send emails, play songs, and perform basic system operations.

---

## 🚀 Features

- Voice command recognition using SpeechRecognition  
- Text-to-speech response using pyttsx3  
- Tells current time and date  
- Searches Wikipedia  
- Opens YouTube and Google search results  
- Opens applications and websites  
- Takes screenshots  
- Checks CPU usage and battery percentage  
- Sends emails using SMTP  
- Plays songs from local folders  
- Stores and reads memory notes  
- Fetches weather information  
- Fetches news headlines  
- Performs calculations using WolframAlpha  
- Executes system commands like shutdown and restart  

---

## 🛠 Tech Stack

- Python  
- SpeechRecognition  
- pyttsx3  
- Wikipedia API  
- pyautogui  
- psutil  
- pyjokes  
- smtplib  
- requests  
- WolframAlpha API  

---

## ⚙️ Project Workflow

1. The assistant starts and initializes the text-to-speech engine  
2. It greets the user with time and date  
3. It listens to the user using a microphone  
4. SpeechRecognition converts voice into text  
5. The command is processed using keyword matching  
6. The required task is executed  
7. Jarvis responds using speech output  

---

## 📦 Installation

Clone the repository:

```bash
git clone https://github.com/your-username/jarvis-voice-assistant.git
cd jarvis-voice-assistant
Install dependencies:

pip install pyttsx3 SpeechRecognition wikipedia pyautogui psutil pyjokes wolframalpha requests pyaudio
```
If pyaudio fails on Windows:

```pip install pipwin
pipwin install pyaudio
```
🔑 Required Setup
Add your email and password for SMTP
Add API keys for weather and WolframAlpha
Set correct paths for songs and screenshots
▶️ How to Run
python jarvis.py
💬 Example Commands
What is the time
Search Wikipedia for AI
Open YouTube
Search Google
Take screenshot
Tell me a joke
Check CPU
Send email
Calculate 5 plus 10
Go offline
⚡ Challenges Faced
Handling speech recognition errors due to background noise
Managing multiple command executions in a single system

Solution:
Used exception handling and modular functions to ensure smooth execution and better reliability.

🚀 Future Scope
Add offline speech recognition
Add GUI interface
Add database for storing memory
Improve command understanding using NLP
Add multi-user support
📚 Learning Outcomes
Learned speech recognition and text-to-speech integration
Understood API handling and system automation
Improved problem-solving and modular coding skills
👩‍💻 Author

Vaishnavi Ranjan
