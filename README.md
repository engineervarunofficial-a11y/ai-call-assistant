# AI Call Assistant 🤖📱

**A production-ready Android AI Call Assistant** that automatically answers unknown phone calls using an advanced AI voice assistant, with live transcription and user intervention capabilities.

Competing with: **Equal AI**, **Google Call Screen**, **Apple Live Voicemail**

## Features

### Core Capabilities
- ✅ Auto-answer unknown calls with AI
- ✅ Real-time AI voice conversations (GPT-4o)
- ✅ Live call transcription
- ✅ Join calls anytime
- ✅ Intent detection & classification
- ✅ Spam detection with confidence scores
- ✅ Call summaries & transcripts
- ✅ Multi-language support (10+ languages)
- ✅ Encrypted call recordings
- ✅ Rich analytics dashboard
- ✅ Material 3 UI (Android 15)
- ✅ GDPR compliant
- ✅ Offline support
- ✅ Biometric authentication

## Tech Stack

### Frontend
- **Kotlin** 2.0 + **Jetpack Compose**
- MVVM + Clean Architecture
- Hilt DI, Room DB, DataStore
- Retrofit + WebSocket
- Target API 35 (Android 15)

### Backend
- **FastAPI** (Python 3.11+)
- PostgreSQL 15+ & Redis 7.0+
- OpenAI GPT-4o Realtime API
- Docker + Kubernetes
- JWT Authentication

## Quick Start

### Prerequisites
- Android Studio Hedgehog (2023.1.1+)
- Python 3.11+
- Docker & Docker Compose
- PostgreSQL 15+ & Redis 7.0+

### Setup (3 Minutes)

```bash
# 1. Clone
git clone https://github.com/engineervarunofficial-a11y/ai-call-assistant.git
cd ai-call-assistant

# 2. Environment Setup
cp backend/.env.example backend/.env

# 3. Start Services
cd docker
docker-compose up -d

# 4. Backend Setup
cd ../backend
python -m venv venv
source venv/bin/activate
pip install -r requirements.txt
uvicorn app.main:app --reload

# 5. Android (in Android Studio)
# Open android/ folder and build
```

## Documentation

- [API.md](./docs/API.md) - REST API documentation
- [ARCHITECTURE.md](./docs/ARCHITECTURE.md) - System design
- [DEPLOYMENT.md](./docs/DEPLOYMENT.md) - Deployment guide

## Contributing

See [CONTRIBUTING.md](./CONTRIBUTING.md)

## License

MIT License - See [LICENSE](./LICENSE)

---

**Built with ❤️ for better communication**
