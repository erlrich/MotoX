# MotoX - IoT-based Motorcycle Security System 🏍️🔐

MotoX is an IoT-powered motorcycle security system designed to protect against theft and unauthorized use. It uses smart sensors and multiple operation modes to detect tampering, movement, and theft attempts.

## 🔧 Features
- Vibration and movement detection using SW420 & MPU6050
- Kickstand monitoring via Reed Switch
- Alarm system with relay-controlled siren & ignition lock
- DFPlayer Mini for audio feedback/voice alert
- Four operation modes:
  - **Home Mode**
  - **Travel Mode**
  - **Secure Parking Mode**
  - **Trap Mode**
  - **Ride Mode** *(under development)*
- Mobile app control via **Flutter** (BLE & Wi-Fi)

## 🧰 Hardware Components
- ESP32 (NodeMCU-32E)
- SW420 (vibration sensor)
- MPU6050 (gyroscope + accelerometer)
- Reed Switch (kickstand)
- DFPlayer Mini + 3W Speaker
- RFID RFC522 for non apps alarm deactivation
- Relay module
- Power: 12V motorcycle battery → 5V via DC-DC step-down

## 📱 Android App
- Built with Flutter
- BLE/Wi-Fi communication
- Simple UI to switch operation modes

## 📂 Project Structure
MotoX-MotoSec/
├── MotoX_Main.ino
├── docs/
├── images/
├── app/
├── LICENSE
└── README.md


## 🛡️ License
This project is licensed under the MIT License.
