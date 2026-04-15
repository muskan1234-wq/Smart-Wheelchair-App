# 🦽 Voice Controlled Smart Wheelchair

## 📌 Overview
This project is a Smart Voice Controlled Wheelchair system designed to help physically challenged or elderly users move independently using voice commands and Android mobile application control.

The system integrates Arduino Uno, Bluetooth module, and motor driver with a mobile app developed in Java (Android Studio) to provide smooth and safe wheelchair movement.

---

## ✨ Key Features

🎤 Voice Control System  
- Wheelchair controlled using voice commands via mobile app  
- Commands: Forward, Backward, Left, Right, Stop  

📱 Mobile App Control  
- Android app with directional buttons  
- Microphone button for voice input  
- Bluetooth connectivity with wheelchair hardware  

🔗 Wireless Connectivity  
- HC-05 Bluetooth module for communication  
- Real-time command execution  

🦽 Movement Control  
- Smooth directional movement  
- L298N motor driver integration  
- High stability and safety control  

⚡ Safety Features  
- Emergency Stop button  
- Instant response to commands  
- Safe speed control  

---

## 🧱 Tech Stack

### 📱 Android App
- Java (Android Studio)  
- XML (UI Design)  
- Bluetooth API  
- Voice Recognition API  

### 🔧 Hardware
- Arduino Uno  
- HC-05 Bluetooth Module  
- L298N Motor Driver  
- DC Geared Motors  
- Wheels + Wheelchair Frame  
- Battery (12V)  

---

## 📂 Project Structure

VoiceControlledWheelchair/
│
├── app/
│ ├── java/com/wheelchair/
│ │ ├── activities/
│ │ ├── bluetooth/
│ │ ├── voice/
│ │ ├── controls/
│ │ └── utils/
│ │
│ ├── res/
│ │ ├── layout/
│ │ ├── drawable/
│ │ └── values/
│
├── Arduino Code/
│ └── wheelchair_control.ino
│
├── AndroidManifest.xml
└── build.gradle


---

## ⚙️ Installation & Setup

### 1️⃣ Clone Repository
```bash
git clone https://github.com/your-username/voice-controlled-wheelchair.git
cd voice-controlled-wheelchair

---

## ⚙️ Installation & Setup

### 1️⃣ Clone Repository
```bash
git clone https://github.com/your-username/voice-controlled-wheelchair.git
cd voice-controlled-wheelchair
2️⃣ Android App Setup
Open project in Android Studio

Sync Gradle files

Connect mobile or emulator

Run the app

3️⃣ Hardware Setup
Connect motors with L298N driver

Connect HC-05 Bluetooth module to Arduino

Upload Arduino code

Pair mobile app with HC-05

🎤 Voice Commands
Command	Action
Forward	Move forward
Backward	Move backward
Left	Turn left
Right	Turn right
Stop	Stop movement



🚀 Future Improvements
AI-based obstacle detection

Voice assistant integration (Google Assistant)

IoT cloud monitoring

GPS tracking system

Solar-powered wheelchair upgrade

👩‍💻 Developer
Muskan Pathan
BTech Computer Science & Engineering
Project: Voice Controlled and manually Smart Wheelchair



Open Pull Request
