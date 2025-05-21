**LLM Chat Application - Flutter & Flask**
A cross-platform chat application that leverages Large Language Models (LLMs) with Flask backend and Flutter frontend. This project demonstrates how to build an AI-powered chat interface with modern web technologies.

**✨ Features**

**AI-Powered Conversations:** Integrates with GPT-2 (expandable to other LLMs).

**Cross-Platform:** Flutter app works on iOS, Android, and web.

**RESTful API:** Flask backend with clean endpoints.

**Extensible Architecture:** Easy to add new models or features.

**🛠️ Tech Stack**

**Frontend:**

*Flutter 3.18+

*Dart 3.7+

*HTTP for API communication

*Provider for state management

**Backend:**

*Python 3.10+

*Flask

*Transformers (Hugging Face)

*GPT-2 model (default)

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

**Prerequisites**

*Flutter SDK

*Python 3.10+

*Git

**Installation:**

**1.Backend Setup:**

**bash**

cd server

pip install -r requirements.txt

python llm_flask_api.py

**2.Frontend Setup:**

**bash**

cd client

flutter pub get

flutter run

**🌟 Future Enhancements:**

*User authentication

*Conversation history

*Multi-LLM support

*Voice input/output

*File upload processing

**🤝 Contributing:**

Contributions are welcome! Please open an issue or submit a PR.

1.Fork the project

2.Create your feature branch (git checkout -b feature/AmazingFeature)

3.Commit your changes (git commit -m 'Add some amazing feature')

4.Push to the branch (git push origin feature/AmazingFeature)

5.Open a Pull Request

**📄 License:**

Distributed under the MIT License. See LICENSE for more information.



