# SUR – Python Desktop AI Assistant

**SUR** is a Python-based desktop AI assistant designed to provide a smart, hands-free productivity tool. It leverages voice recognition and AI-driven responses to manage tasks, fetch information, and control multimedia on a Windows system.

---

## Key Features

1. **Natural Conversation**
   - Chat with SUR using voice commands.
   - Handles general queries and AI-powered responses.
   - Stores conversation history locally for future reference.

2. **Weather Updates**
   - Fetch real-time weather information for any city.
   - Displays temperature, feels-like temperature, and weather description.
   - Uses OpenWeatherMap API.

3. **News Updates**
   - Get latest general news or technology news.
   - Uses GNews API to fetch top headlines.

4. **Multimedia Control**
   - Play local music files (mp3, wav, m4a).
   - Open Windows Camera for photos or videos.
   - Open websites like YouTube, Google, ChatGPT via voice commands.

5. **AI-Powered Responses**
   - Uses OpenRouter AI (LLaMA-3.1) to provide intelligent and context-aware replies.
   - Supports both typed prompts and voice commands starting with "AI".

6. **Time and Date**
   - Can tell the current system time upon request.

7. **Hands-Free Interaction**
   - Fully integrated with speech recognition (`speech_recognition`) and Windows text-to-speech (`win32com.client`).
   - Responds verbally to commands using `SAPI.SpVoice`.

8. **Chat Logging**
   - Conversations and AI responses are saved automatically in the `OPENAI` folder.
   - Each chat file is named based on user input with a unique identifier.

---


