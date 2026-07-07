# IoT Building Monitoring System

A production-ready IoT-based Building Monitoring System designed to monitor environmental conditions and improve building safety through real-time sensor data. The system continuously tracks air quality, temperature, humidity, fire hazards, water level, and motion while automatically controlling safety devices and appliances.

## Project Overview

**Project Name:** IoT Building Monitoring System  
**Category:** Internet of Things (IoT)  
**Platform:** ESP32 / Arduino UNO  
**Programming Language:** C++ (Arduino IDE)  
**Connectivity:** Wi-Fi (ESP32) / Bluetooth (Optional)  
**Cloud Platform:** Blynk / Firebase / ThingSpeak (Optional)

## Features

### 🌡 Environmental Monitoring
- Real-time temperature monitoring
- Humidity monitoring
- Indoor air quality monitoring
- Continuous environmental updates

### 🔥 Fire Detection
- Detects fire using flame sensor
- Activates buzzer automatically
- Sends emergency notifications (Optional)

### 💨 Air Quality Monitoring
- Detects harmful gases using MQ135
- Monitors indoor pollution levels
- Alerts users when air quality becomes unsafe

### 💧 Water Level Monitoring
- Detects water leakage or overflow
- Sends warning alerts
- Helps prevent water damage

### 🚶 Motion Detection
- Detects human movement
- Supports automatic lighting
- Enhances building security

### 💡 Smart Automation
- Automatic fan control
- Automatic lighting control
- Smart appliance switching
- Relay-based device management

### 📱 Remote Monitoring
- Monitor building status remotely
- View live sensor data
- Receive real-time notifications
- Cloud dashboard support

---

# Hardware Components

- ESP32 / Arduino UNO
- DHT11 Temperature & Humidity Sensor
- MQ135 Gas Sensor
- Flame Sensor
- Water Level Sensor
- PIR Motion Sensor
- Relay Module
- DC Fan
- LED Bulb
- Buzzer
- White LED
- Red LED
- Jumper Wires
- Breadboard
- Power Supply

---

# Software Requirements

- Arduino IDE 2.x
- ESP32 Board Package (If using ESP32)
- Blynk IoT (Optional)
- Firebase (Optional)
- ThingSpeak (Optional)

---

# System Workflow

1. Sensors continuously collect environmental data.
2. ESP32/Arduino processes all sensor readings.
3. The system checks predefined safety thresholds.
4. If abnormal conditions are detected:
   - Alarm activates.
   - LEDs indicate warning status.
   - Fan or appliances operate automatically.
   - Notification is sent (Optional).
5. Sensor data is displayed on the IoT dashboard.
6. System continuously monitors the building.

---

# Folder Structure

```
iot-building-monitoring-system/
│
├── Arduino_Code/
│   ├── building_monitoring_system.ino
│
├── circuit_diagram/
│
├── images/
│
├── documentation/
│
├── mobile_app/ (Optional)
│
├── README.md
│
└── LICENSE
```

---

# Pin Configuration

| Component | Pin |
|-----------|-----|
| DHT11 | D4 |
| MQ135 | A0 |
| Flame Sensor | D5 |
| Water Level Sensor | D6 |
| PIR Motion Sensor | D3 |
| Buzzer | D7 |
| White LED | D8 |
| Red LED | D9 |
| Fan Relay | D10 |
| Light Relay | D11 |
| Motor Relay | D12 |

---

# Technology Stack

- Arduino C++
- ESP32
- IoT
- Embedded Systems
- Wi-Fi Communication
- Sensor Integration
- Automation
- Firebase (Optional)
- Blynk IoT
- ThingSpeak

---

# Applications

- Smart Buildings
- Office Monitoring
- Home Automation
- Industrial Safety
- Laboratories
- Server Rooms
- Shopping Malls
- Educational Institutions

---

# Future Improvements

- AI-Based Anomaly Detection
- Energy Consumption Analytics
- Mobile Application
- Voice Assistant Integration
- Face Recognition Access
- Smart CCTV Integration
- MQTT Support
- Cloud-Based Dashboard
- Predictive Maintenance

---

# Project Objectives

- Monitor building conditions in real time.
- Improve building safety.
- Automate electrical appliances.
- Detect hazards before they become critical.
- Reduce energy consumption.
- Enable remote monitoring using IoT.

---

# Learning Outcomes

- Internet of Things (IoT)
- Embedded Programming
- ESP32 Development
- Arduino Programming
- Sensor Interfacing
- Relay Automation
- Wi-Fi Communication
- Cloud Integration
- Real-Time Monitoring
- Smart Building Systems

---

# Installation

## Clone Repository

```bash
git clone https://github.com/yourusername/iot-building-monitoring-system.git
cd iot-building-monitoring-system
```

## Upload Firmware

1. Open Arduino IDE.
2. Install required libraries.
3. Select your board.
4. Select COM Port.
5. Upload the code.

---

# Verification

```bash
Arduino IDE → Verify Sketch
```

---

# Upload

```bash
Arduino IDE → Upload
```

---

# License

This project is developed for educational, research, and academic purposes.

---

## Developed By

**AATIFAA JYOTI**

Department of Computer Science & Engineering (CSE)

IoT • Embedded Systems • Robotics • Machine Learning • Python
