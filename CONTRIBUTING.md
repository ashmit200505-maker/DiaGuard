# 🤝 Contributing to DiaGuard

Thank you for your interest in making diabetes care accessible across India! We welcome contributors from **hardware engineering, data science, clinical research, frontend development, and community health**.

---

## 📋 Table of Contents

- [Code of Conduct](#code-of-conduct)
- [How to Contribute](#how-to-contribute)
- [Development Setup](#development-setup)
- [Project Structure](#project-structure)
- [Pull Request Guidelines](#pull-request-guidelines)
- [Reporting Bugs](#reporting-bugs)
- [Feature Requests](#feature-requests)

---

## 📜 Code of Conduct

All contributors are expected to adhere to our Code of Conduct — be respectful, inclusive, and mission-driven. Health data is sensitive. Handle it with care.

---

## 🛠️ How to Contribute

1. **Fork** the repository
2. **Clone** your fork locally
   ```bash
   git clone https://github.com/YOUR_USERNAME/diaguard.git
   cd diaguard
   ```
3. **Create a branch** for your feature or fix
   ```bash
   git checkout -b feature/your-feature-name
   ```
4. **Make your changes** following the coding standards below
5. **Commit** with a clear message
   ```bash
   git commit -m "feat: add Hindi voice interface support"
   ```
6. **Push** and open a **Pull Request** against `main`

---

## 💻 Development Setup

### Backend (Flask)
```bash
cd backend
python -m venv venv
venv\Scripts\activate        # Windows
source venv/bin/activate     # macOS/Linux
pip install -r requirements.txt
flask run
```

### Frontend (React + Tailwind)
```bash
cd frontend
npm install
npm run dev
```

### Firmware (ESP32)
- Install [Arduino IDE](https://www.arduino.cc/en/software) or PlatformIO
- Open `firmware/main.ino`
- Select board: **ESP32 WROOM-32**
- Install libraries: `ArduinoJson`, `ADS1220`, `BLEDevice`

---

## 📁 Project Structure

```
diaguard/
├── backend/            # Flask API (ML inference, GenAI coaching)
├── frontend/           # React + Tailwind patient dashboard
├── firmware/           # ESP32 SWIR sensor firmware
├── models/             # Pre-trained ML model artifacts
├── docs/               # Clinical documentation and API specs
└── README.md
```

---

## ✅ Pull Request Guidelines

- Keep PRs **focused and small** — one feature or fix per PR
- Include **unit tests** for new backend logic
- Update the **README** if you add a new feature or dependency
- All ML changes must include a **SHAP explanation** validation
- Clinical data handling must follow **HIPAA-aligned** standards

---

## 🐛 Reporting Bugs

Open a [GitHub Issue](../../issues) with:
- Steps to reproduce
- Expected vs. actual behavior
- Device/sensor hardware version if hardware-related

---

## 💡 Feature Requests

Open a [GitHub Discussion](../../discussions) with:
- The problem you're solving
- Your proposed approach
- Any clinical or regulatory considerations

---

## 🙏 Recognition

All contributors are listed in [CONTRIBUTORS.md](CONTRIBUTORS.md). Significant contributions to clinical validation or core ML may be eligible for co-authorship on future publications.

---

*Built with ❤️ for India's 101 million diabetics.*
