# 📍 Circle Me

> **Connect Nearby. Stay Safe. Play Together.**

**Circle Me** is an intelligent, real-time proximity-based social and personal safety platform. Designed to make nearby connections human and secure, it combines live geolocation radar, low-latency WebSocket communication, AI-assisted interactions, and emergency safety features into a modern dark-themed web experience.

### ✨ Key Features
- 📡 **Hyperlocal Proximity Radar:** Discover nearby peers, campus communities, and verified circles with customizable privacy filters.
- 💬 **Real-time Chat & Voice Notes:** Instant messaging and audio notes powered by Django Channels & WebSockets.
- 🛡️ **Safety Shield (Walk Me Home & SOS):** Live journey tracking, battery monitoring, and instant emergency alerts for contacts.
- 🤖 **Jarvis AI Assistant:** Context-aware recommendations and vibe suggestions powered by Google Gemini 2.0.
- 🎮 **In-App Mini Games:** Multiplayer real-time mini-games over WebSockets.

### 🛠️ Tech Stack
- **Backend:** Python, Django 5, Django Channels (ASGI), Daphne
- **Real-Time & Broker:** WebSockets, Redis (`channels-redis`)
- **Database:** PostgreSQL / SQLite
- **AI Integration:** Google Gemini API (`gemini-2.0-flash`)
- **Frontend:** HTML5, CSS3, JavaScript (ES6+), Bootstrap 5, Leaflet.js
