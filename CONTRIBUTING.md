# Contributing to AI Call Assistant

Thank you for your interest in contributing! This document provides guidelines.

## Getting Started

1. Fork the repository
2. Clone: `git clone https://github.com/YOUR_USERNAME/ai-call-assistant.git`
3. Create feature branch: `git checkout -b feature/my-feature`
4. Make changes
5. Commit: `git commit -am 'Add feature description'`
6. Push: `git push origin feature/my-feature`
7. Create Pull Request

## Development Setup

### Android
```bash
cd android
./gradlew build
./gradlew test
```

### Backend
```bash
cd backend
python -m venv venv
source venv/bin/activate
pip install -r requirements-dev.txt
pytest
```

## Code Style

### Kotlin
- [Kotlin Style Guide](https://kotlinlang.org/docs/coding-conventions.html)
- 4 spaces indentation
- Max line: 120 characters
- `./gradlew ktlintFormat`

### Python
- [PEP 8](https://pep8.org/)
- 4 spaces indentation
- Max line: 100 characters
- `black .`
- `flake8 app`

## Commit Messages

```
<type>(<scope>): <subject>

<body>

<footer>
```

**Types**: feat, fix, docs, style, refactor, test, chore

## Pull Request Process

1. Update documentation
2. Add tests for new features
3. Ensure all tests pass
4. Request review from maintainers
5. Address review comments
6. Wait for approval and merge

## Reporting Issues

Include:
- OS and version
- Android version (for app issues)
- Steps to reproduce
- Expected vs actual behavior
- Logs/screenshots
- Device information

## Questions?

- Open issue with [question] tag
- Email: support@aicallassistant.com

Thank you for contributing! 🚀
