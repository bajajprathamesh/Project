# 🤖 Obstacle Avoiding & Bluetooth Controlled Robot  

This project demonstrates the design and development of a multifunctional Arduino-based robot capable of:  

- 🚧 **Autonomous obstacle avoidance** using ultrasonic sensors  
- 📡 **Wireless Bluetooth control** via a mobile device  

Built as part of the **Product Realization Lab** at **Parul University (2023-24)**.  

---

## 📌 Features  
- Obstacle detection and avoidance using an **Ultrasonic Sensor**  
- Wireless robot control through a **Bluetooth Module**  
- Dual-mode functionality:  
  - Autonomous Navigation  
  - Manual Bluetooth Control  
- Expandable to support **voice control** and other smart features  

---

## 🛠 Components Used  
- Arduino UNO (ATmega328P)  
- Gear Motors + Robot Wheels  
- Motor Driver (L293D)  
- Ultrasonic Sensor (HC-SR04)  
- Bluetooth Module (HC-05/HC-06)  
- Li-ion Battery  
- Jumper Wires & Dot Board  

---

## 🔌 System / Circuit Design  
The Arduino UNO connects all components:  
- **Ultrasonic Sensor** → Detects obstacles  
- **Bluetooth Module** → Receives commands from smartphone  
- **Motor Driver** → Drives the motors forward, backward, left, and rig
