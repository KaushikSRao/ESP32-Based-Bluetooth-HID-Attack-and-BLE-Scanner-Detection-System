# ESP32-Based-Wireless-HID-Automation-and-BLE-Security-Awareness-System

## 📌 Overview
This project demonstrates Bluetooth security vulnerabilities by implementing both an attack system and a detection system. It uses an ESP32 to simulate a Bluetooth HID (keyboard) attack and a Python-based BLE scanner to detect and classify nearby devices in real time.

## 📡 Project Areas
- Attack Module (ESP32 Bluetooth Ducky)
- Detection Module (BLE Scanner)  

## 🚀 Features
- BLE HID keyboard simulation using ESP32
- Keystroke injection (Notepad, CMD, URLs, etc.) 
- Real-time BLE device scanning
- Device classification (Trusted / Suspicious / Unknown)  
- Web dashboard for monitoring 
- Multi-device detection support

## 🛠️ Technologies Used
- ESP32 Microcontroller  
- Arduino IDE (C/C++) 
- Python (Bleak, Flask)
- Bluetooth Low Energy (BLE)
- Web Technologies (HTML, CSS)

## 🌐 Network Design
The system is divided into two modules. The attack module uses ESP32 to emulate a Bluetooth keyboard and execute payloads on a target device. The detection module scans nearby BLE devices, processes device information, and displays the results on a web dashboard.

## ▶️ How to Run
Attack Module
1. Upload code to ESP32 using Arduino IDE 
2. Pair ESP32 with target device via Bluetooth
3. Send commands through Serial Monitor

Detection Module
1. Install required libraries
2. Run Python scanner script
3. Open Flask dashboard
4. Monitor detected devices

## 📌 Future Improvements
- Machine learning-based detection
- Cross-platform support (macOS, Linux)
- Improved classification accuracy
