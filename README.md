<p align="center">
  <img src="https://upload.wikimedia.org/wikipedia/commons/8/87/Arduino_Logo.svg" alt="Arduino Logo" width="100">
</p>

<h1 align="center">🧍‍♂️💻 Ultrasonic Posture & Distance Alert System</h1>

<p align="center">
  <b>Stay away from your screen — literally! 👀</b><br>
  <i>An Arduino-based posture reminder that buzzes when you sit too close.</i><br><br>
  <img src="https://img.shields.io/badge/Arduino-Ultrasonic%20Sensor-blue?style=flat-square&logo=arduino">
  <img src="https://img.shields.io/badge/Buzzer-Active-green?style=flat-square">
  <img src="https://img.shields.io/badge/DIY-Project-orange?style=flat-square">
</p>

---

## ✨ Overview
If you spend long hours coding, watching videos, or gaming — chances are your posture suffers 😅  
This project uses an **HC-SR04 Ultrasonic Sensor** and an **Active Buzzer** to alert you when you sit too close to your screen.  

👉 Simply mount the ultrasonic sensor above your monitor.  
When your face comes within **x cm**, the **buzzer alerts you to lean back** and maintain healthy distance.  
A small but smart step toward better posture and eye comfort 💡

---

## 🧩 Components Used
| Component | Quantity | Description |
|------------|-----------|-------------|
| Arduino UNO | 1 | Microcontroller board |
| HC-SR04 Ultrasonic Sensor | 1 | Measures distance |
| Active Buzzer | 1 | Beeps when too close |
| Breadboard & Jumper Wires | — | For circuit setup |

---

## ⚙️ Circuit Connections

| Component | Pin | Arduino Pin |
|------------|-----|-------------|
| HC-SR04 | VCC | 5V |
| HC-SR04 | GND | GND |
| HC-SR04 | TRIG | D9 |
| HC-SR04 | ECHO | D10 |
| Buzzer | + | D8 |
| Buzzer | - | GND |

---
## 🖼️ Circuit Diagram
---
## 🚀 How It Works
1. The **ultrasonic sensor** measures the distance between you and your screen.  
2. If you lean closer than **20 cm**, the **buzzer instantly starts buzzing**.  
3. As soon as you move back, the buzzer turns off automatically.  
4. This subtle alert helps you correct your posture and reduce eye strain 👀  

> 🧠 Simple. Smart. Effective.

---

## 🌟 Features
1. 🧍‍♂️ Automatic posture correction reminder  
2. 🔊 Instant buzzer alert when too close  
3. ⚙️ Adjustable distance threshold (change in code)  
- 🧰 Compact, beginner-friendly circuit  
- 🔄 Reusable as a proximity or door alarm system  

---

## 🔮 Future Enhancements
- 💡 Add RGB LED for distance-based color alerts  
- 🎵 Use variable beep frequency based on proximity  
- 📟 Display live distance on LCD/OLED screen  
- 🔋 Make it battery-powered for portability  
- 📱 Add Bluetooth to log posture data on your phone  

---

## 🧠 Created By
**Hriday D.**  
[GitHub ↗](https://github.com/Hridaywho)

💬 *“Sit straight. Stay sharp. Code longer.”*  

