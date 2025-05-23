**LLM Chat Application - Flutter & Flask**
A cross-platform chat application that leverages Large Language Models (LLMs) with Flask backend and Flutter frontend. This project demonstrates how to build an AI-powered chat interface with modern web technologies.

**✨ Features:**

**AI-Powered Conversations:** Integrates with GPT-2 (expandable to other LLMs)

**Cross-Platform:** Flutter app works on iOS, Android, and web

**RESTful API:** Flask backend with clean endpoints

**Real-time Interaction:** Streamlined chat interface

**Extensible Architecture:** Easy to add new models or feature Flask backend with clean endpoints

**🛠️ Tech Stack:**

**Frontend:**

Flutter 3.18+

Dart 3.7+

HTTP for API communication

Provider for state management

**Backend:**

Python 3.10+

Flask

Transformers (Hugging Face)

GPT-2 model (default)

**📦 Project Structure:**

llm-chat-app/

├── client/               # Flutter application

│   ├── lib/              # Dart source code

│   └── pubspec.yaml      # Flutter dependencies

├── server/               # Flask backend

│   ├── llm_flask_api.py  # Main API server

│   └── requirements.txt  # Python dependencies

└── docs/                 # Documentation

**🚀 Getting Started:**

**Prerequisites:**

Flutter SDK

Python 3.10+

**Installation:**

**1.Backend Setup:**

cd server

pip install -r requirements.txt

python llm_flask_api.py

**Frontend Setup:**

cd client

flutter pub get

flutter run

**🌟 Future Enhancements:**

User authentication

Conversation history

Multi-LLM support

Voice input/output

**🔗 Useful Links:**

Flutter Documentation:docs.flutter.dev

Flask Documentation: docs.defang.io/docs

Hugging Face Transformers: huggingface.co/docs

**📄 License:**

Distributed under the MIT License. See LICENSE for more information.
