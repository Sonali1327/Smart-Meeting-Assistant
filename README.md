# Smart Meeting Assistant

A real-time meeting assistant built with web technologies that provides **live video calling**, **closed captions (speech-to-text transcription)**, and a **transcript panel** showing what was said in the meeting. The goal is to create a meeting tool where participants can talk, and the app will show live transcription and store it for later reading.

---

## 🚀 Features

✔ Live video calls  
✔ Real-time closed captions (speech-to-text)  
✔ Transcript panel with speaker and timestamps  
✔ Easy to extend with AI insights (e.g., summaries, action items)  
✔ Built with modern frameworks and SDKs

---

## 🧠 How It Works

This application uses the **Stream Video React SDK** to handle video calls and live transcription events. It listens for closed-caption events and displays them in a scrolling transcript panel UI.

Closed captions events are captured from the meeting call and added to state, with speaker identification + timestamp for readability.

---

## 🛠️ Built With

✔ React / Next.js  
✔ Stream Video & Chat SDKs  
✔ Tailwind CSS (for UI styling)  
✔ JavaScript

---

## 📥 Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/Sonali1327/Smart-Meeting-Assistant.git
   cd Smart-Meeting-Assistant
