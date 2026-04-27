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

## 📷 Network Diagram
<img width="1898" height="813" alt="image" src="https://github.com/user-attachments/assets/d9ccdf6c-ef9e-4b80-848a-bb9c3e78f0e8" />


## ▶️ How to Run
1. Open Cisco Packet Tracer  
2. Load the `.pkt` file  
3. Run simulation and test connectivity  

## 📌 Future Improvements
- VLAN implementation  
- Wireless network integration  
- Load balancing  
