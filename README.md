# jarvis_voice_activated_virtual_assistant

## 🧠 Jarvis: Voice Activated Virtual Assistant
Jarvis is a voice-activated virtual assistant designed to perform web searches, play music, fetch news, and interact using AI-powered responses. It leverages modern Python libraries like speech_recognition, pyttsx3, OpenAI, and more to mimic behavior similar to Alexa or Google Assistant.

## 🚀 Features
- **🎤 Voice Activation:** Say "Jarvis" to activate the assistant.
- **🌐 Web Browsing:** Open popular websites like Google, Facebook, LinkedIn, YouTube, and Instagram with simple voice commands.
- **🎶 Play Music:** Play your favorite songs using a local music library mapping.
- **📰 Get Latest News:** Fetch and read out top news headlines using the News API.
- **🤖 AI Responses:** Handles general queries with GPT-3.5 via the OpenAI API.

## 📦 Dependencies
**Install the required packages using:**
- pip install -r requirements.txt

**Required Libraries:**
- speechrecognition
- webbrowser (standard library)
- pyttsx3
- requests
- pygame
- openai
- gtts (optional - alternative TTS)
- Custom module: musicLibrary.py

## 📁 Project Structure
Jarvis/ <br>
│ <br>
├── jarvis.py                # Main script <br>
├── musicLibrary.py          # Dictionary mapping song names to URLs <br>
├── README.md                # Project documentation <br>
├── requirements.txt         # Dependency list <br>

## ⚙️ Setup
**Clone the repository:**
- git clone https://github.com/yourusername/Jarvis.git
- cd Jarvis

**Install dependencies:**
- pip install -r requirements.txt

**Add your API keys:**
- OpenAI API key in the aiProcess() function.
- News API key in the newsapi variable.

## 🗣️ Usage
**Run the assistant using:**
- python jarvis.py <br>
**Note** : Then speak "Jarvis" to activate. Once acknowledged, give your command like:

- "Open Google"
- "Play [song name]"
- "What's the latest news?"
- "What's the capital of France?"

## 🔐 Notes on API Keys
- **OpenAI API Key:** Replace the key in aiProcess() with your own.
- **News API Key:** Get one from NewsAPI.org and paste it into the newsapi variable.
- Avoid hardcoding sensitive keys in production.

## ✅ To-Do
- Add weather support
- Improve wake word detection with continuous listening
- Integrate home automation features
- Add GUI interface (optional)

## 🧑‍💻 Author
Harsh Mishra <br>
GitHub: @erharshmishra <br>
