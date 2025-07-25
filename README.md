# 🚗 Pushpak Rover — Autonomous Parcel Delivery System

**Innothon Hackathon Project | Team Pushpak (2024)**

Pushpak Rover is a **semi-autonomous parcel delivery robot** designed to solve the last-mile delivery challenge inside campus environments. It follows a predefined path using sensors, allows remote booking via a website, and delivers small parcels with minimal human involvement.

---

## 📋 Problem Statement & Selection Process

This project was developed as part of **InnoThon 2.0**, a campus innovation hackathon organized by NIT Warangal and Hitachi Energy. Teams were given real-world challenges and required to submit an initial proposal before being selected for prototype development.

- 🧾 [InnoThon Official Poster (Problem Statement)](Docs/Innothon_Problem_Statement.pdf)
- 📝 [Initial Proposal Document](Docs/Initial_Proposal.pdf)

Only after review and shortlisting were teams allowed to proceed to build their prototype.

---

## 📌 Problem Statement

At our college, all courier deliveries are left at the **main gate**, forcing students and faculty to **walk long distances** to collect them. This causes loss of time and effort.

---

## ✅ Our Solution: Pushpak Rover

An autonomous rover that:
- 🚶 Eliminates the need to walk to the gate
- 📍 Provides **real-time GPS tracking**
- 🛣️ Follows a predefined line-marked path
- 🖥️ Can be booked via a simple **web interface**
- 💡 Supports autonomous navigation and obstacle detection

---

## 🧩 System Architecture

### 🔧 Hardware Subsystems
- **Microcontrollers**: Arduino Mega (for motor/sensors) + ESP8266 (for GPS + Wi-Fi)
- **Sensors**:
  - IR sensors for line following
  - Ultrasonic sensors for obstacle avoidance
- **Motors**: 4 × 500 RPM DC motors controlled via dual L298 motor drivers
- **Power Supply**: Rechargeable Li-ion batteries (3.7V × 6) + 9V battery for controller

### 🌐 Web Interface
- **Web dashboard** for:
  - Rover booking
  - Occupancy status
  - Live tracking (GPS)
  - Delivery queue

---

## 📦 Features

| Feature                  | Description                                             |
|--------------------------|---------------------------------------------------------|
| 🧭 Line Following         | IR sensors guide the rover along a white path           |
| 🚧 Obstacle Detection     | Ultrasonic sensors prevent collisions                   |
| 📡 GPS Tracking           | ESP8266 + GPS module share real-time location          |
| 🔋 Power Management       | Efficient distribution and recharging supported         |
| 🌐 Web Dashboard          | User-friendly interface for booking and tracking        |

---

## 🚀 Development Timeline

1. Planning & Design  
2. Chassis Construction  
3. Sensor & Circuit Integration  
4. Microcontroller Configuration  
5. Web Platform Integration  
6. Final Testing & Optimization  

---

## 🔬 Future Enhancements

- Upgrade to **LiDAR + AI on Raspberry Pi** for smarter pathfinding  
- Add **motor upgrades** for higher load capacity  
- Integrate **secure locker system** using OTP-based locking

---
## 📹 Demo Videos

- ▶️ [Watch Rover Line-Following Demo](media/Rover_Demo_Video.mp4)

---

## 📄 Documentation

- 📘 [Project Report (PDF)](Docs/Pushpak_Rover_Presentation.pdf)

---




## 👨‍👩‍👧‍👦 Team Pushpak

- Pradeep Singh Kaurav  
- Eesh Tripathi  
- Volety Sriram Panchamukhi  
- Anoop S Rao  
- Swati Yadav

---

> *Built during Innothon Hackathon 2024 — combining embedded systems, automation, and web technologies to solve real-world campus problems.*

