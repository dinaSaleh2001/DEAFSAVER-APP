# 🧏 DEAF SAVER

> A Flutter mobile application designed to help deaf users communicate more easily and safely.

## 📱 About the Project

**DEAF SAVER** is a graduation project developed to support deaf and hard-of-hearing users through communication assistance and emergency features.

The application combines **Speech-to-Text, Text-to-Speech, sound classification, and emergency location sharing** to provide practical communication and safety solutions.

## ✨ Features

* 🗣️ **Speech-to-Text** — Converts spoken language into text.
* 🔊 **Text-to-Speech** — Converts text into spoken audio.
* 🌍 **Multi-language Support** — Supports communication in multiple languages.
* 🚨 **Emergency Contact** — Sends an emergency notification with the user's location.
* 🔉 **Sound Classification** — Detects and classifies important environmental sounds.
* 📍 **Location Sharing** — Uses the user's location during emergency notifications.

## 🛠️ Technologies & Tools

* **Flutter**
* **Dart**
* **Firebase**
* **REST APIs**
* **Speech-to-Text**
* **Text-to-Speech**
* **Machine Learning**
* **Git & GitHub**

## 🏗️ Project Architecture

The application was developed using a structured and maintainable Flutter architecture, with responsibilities separated between UI, business logic, and external services.

## 🔄 How It Works

### Speech-to-Text

The user speaks into the application → speech is processed → the application converts the speech into text.

### Text-to-Speech

The user enters text → the application processes the text → the text is converted into spoken audio.

### Sound Classification

Environmental sound → audio processing → classification model → predicted sound → user notification.

### Emergency Feature

Emergency action → user's current location is retrieved → emergency notification is sent to the selected contact.

## 🎓 Graduation Project

**Project:** DEAF SAVER
**Role:** Mobile Developer
**Grade:** A+
**Duration:** January 2024 – May 2024

The project was recognized among the **top five distinguished graduation projects** at the university and was nominated for the **Damietta Scientific Olympiad Competition**.

## 💡 Challenges & Solutions

### Long Speech-to-Text Sessions

One challenge was handling long speech-to-text conversations that could stop unexpectedly.

**Solution:** Improved the speech recognition flow and handled the listening state to provide a more continuous user experience.

### Arabic Speech Recognition

Supporting Arabic speech recognition required handling language-specific speech recognition behavior.

**Solution:** Integrated appropriate speech recognition configurations and tested the experience with Arabic input.

### Sound Classification

The application needed to identify environmental sounds and notify the user about the detected sound.

**Solution:** Audio files were processed and sent to the classification endpoint, then the predicted class was used to trigger the appropriate notification.

## 🚀 Future Improvements

* Improve speech recognition accuracy.
* Add more supported languages.
* Expand the sound classification dataset.
* Improve accessibility and user experience.
* Add more emergency and safety features.

## 👩‍💻 Developer

**Dina Saleh**

* GitHub: [dinaSaleh2001](https://github.com/dinaSaleh2001)
* LinkedIn: [Dina Saleh](https://www.linkedin.com/in/dina-saleh-a815b8249/)
*
