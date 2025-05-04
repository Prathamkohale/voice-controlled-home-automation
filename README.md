# 🔊 Voice Controlled Home Automation System

[![Arduino](https://img.shields.io/badge/Platform-Arduino-blue.svg)](https://www.arduino.cc/)
[![Bluetooth](https://img.shields.io/badge/Communication-Bluetooth-blue)]()
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

## 📌 Project Overview

This project is a **low-cost, voice-controlled home automation system** developed using **Arduino Uno** and a **Bluetooth module (HC-05)**. It allows users to wirelessly control home appliances (like lights and fans) using simple voice commands from an Android smartphone. This system is designed to improve accessibility and convenience, especially for elderly and physically challenged individuals.

---

## 🎯 Objectives

- Enable voice-based control of electrical appliances.
- Ensure wireless and contactless operation via Bluetooth.
- Provide a cost-effective and beginner-friendly solution.

---

## 🧰 Components Used

| Component               | Quantity |
|-------------------------|----------|
| Arduino Uno             | 1        |
| HC-05 Bluetooth Module  | 1        |
| Relay Module (4-Channel)| 1        |
| Android Smartphone      | 1        |
| AC Appliances (Bulb, Fan, etc.) | As needed |

---

## ⚙️ System Working

1. The user gives a voice command (e.g., "Turn on light").
2. An Android voice recognition app converts the speech to text and sends it via Bluetooth.
3. The Arduino Uno receives the command and activates/deactivates the corresponding relay.
4. The connected AC appliance is switched ON or OFF accordingly.

---

## 💡 Features

- 🎙 **Voice Activated Control**  
- 📱 **Wireless Bluetooth Operation**  
- ⚡ **Relay-based Switching for AC Devices**  
- 💰 **Low-Cost Implementation**

---

## 🔐 Safety Precautions

> ⚠️ This project involves **230V AC mains**. Ensure all electrical connections are insulated and handled with appropriate care. Use relay modules with opto-isolation and always test with supervision if unsure.

---

## 📚 Technologies Used

- Embedded C (Arduino IDE)
- Serial Bluetooth Communication
- Android Voice Recognition Apps

---

## 🚀 Future Enhancements

- 🌐 Wi-Fi Integration using ESP8266 or NodeMCU
- 📲 Mobile App with GUI and device status feedback
- 🔍 Sensor integration for automation (e.g., motion, temperature)

---

## 📷 Project Images / Diagrams

*(Add circuit diagrams, breadboard layout, or photos of your setup here)*

---

## 🙌 Acknowledgments

Inspired by the growing need for accessible smart home systems and the potential of low-cost microcontrollers in automation.

