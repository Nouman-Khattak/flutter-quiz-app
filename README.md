# 🧠 Flutter Quiz App

An interactive, beautifully designed Quiz Application built with **Flutter** and **Dart**. Test your knowledge with dynamically shuffled questions, real-time score calculation, and a detailed answer-by-answer review summary.

[![Flutter](https://img.shields.io/badge/Flutter-3.47+-02569B?logo=flutter&logoColor=white)](https://flutter.dev)
[![Dart](https://img.shields.io/badge/Dart-3.13+-0175C2?logo=dart&logoColor=white)](https://dart.dev)
[![License: MIT](https://img.shields.io/badge/License-MIT-purple.svg)](LICENSE)
[![Platform](https://img.shields.io/badge/Platform-Web%20%7C%20Android%20%7C%20iOS-brightgreen)](https://flutter.dev)

---

## 🌐 Live Demo

You can try the live web version of this app here:  
👉 **[Live Quiz App on GitHub Pages](https://nouman-khattak.github.io/flutter-quiz-app/)** *(Auto-deploys via GitHub Actions)*

---

## ✨ Features

- 🎨 **Modern Gradient UI**: Polished deep purple gradient background with smooth transitions and glowing button states.
- 🔀 **Answer Shuffling**: Question answer choices are randomized every time the quiz begins so no two attempts feel identical.
- 📊 **Detailed Results Screen**:
  - Displays overall score (e.g., `X out of Y questions answered correctly`).
  - Interactive scrollable recap highlighting your chosen answer vs the correct answer.
  - Distinct colored badge indicators for right and wrong answers.
- 🔄 **Restart Quiz**: Instantly reset answers and take the quiz again without reloading the app.
- 🔤 **Typography**: Integrated with Google Fonts (`Lato`) for sleek, modern readability.

---

## 🛠️ Tech Stack & Packages

- **Framework**: [Flutter](https://flutter.dev/)
- **Language**: [Dart](https://dart.dev/)
- **State Management**: Built-in Flutter `StatefulWidget` / State Lifting
- **Dependencies**:
  - `google_fonts: ^9.0.0`
  - `cupertino_icons: ^1.0.8`

---

## 📂 Project Architecture

```
lib/
├── data/
│   └── questions.dart         # Questions dataset and answer options
├── models/
│   ├── questions_summary.dart # Scrollable summary widget & status badges
│   ├── quiz_questions.dart    # QuizQuestion data model with shuffle logic
│   └── results_screen.dart    # Score breakdown & restart action
├── answer_button.dart         # Reusable styled elevated button widget
├── main.dart                  # Application entry point
├── question_screen.dart       # Active quiz screen & question index state
├── quiz.dart                  # Root widget handling screen navigation
└── start_screen.dart          # Welcome screen with logo and Start button
```

---

## 🚀 Getting Started

To run this project locally on your machine:

### Prerequisites
- [Flutter SDK](https://docs.flutter.dev/get-started/install) installed (v3.13+)
- Android Studio / VS Code with Flutter extension
- Chrome / Edge (for Web) or Android/iOS Emulator

### Installation & Run

1. **Clone the repository:**
   ```bash
   git clone https://github.com/Nouman-Khattak/flutter-quiz-app.git
   cd flutter-quiz-app
   ```

2. **Get dependencies:**
   ```bash
   flutter pub get
   ```

3. **Run the app:**
   - On Chrome (Web):
     ```bash
     flutter run -d chrome
     ```
   - On Android / Emulator:
     ```bash
     flutter run
     ```

---

## 📦 Building for Production

### Web
```bash
flutter build web --release
```

### Android (APK)
```bash
flutter build apk --split-per-abi
```

---

## 👤 Author

- **Nouman Farooq**
- Email: [nouman.khattak00@gmail.com](mailto:nouman.khattak00@gmail.com)
- GitHub: [@Nouman-Khattak](https://github.com/Nouman-Khattak)

---

## 📄 License

This project is licensed under the MIT License. Feel free to use and customize it!
