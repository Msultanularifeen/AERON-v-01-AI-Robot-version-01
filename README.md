# 🤖 AERON-V01 — AI Robot by Muhammad Sultan Ul Arifeen

> Version 01 • Designed with NodeMCU + ESP32-CAM + Arduino UNO  
> Powered by Blynk | WiFi | Serial Comms | TFT Touchscreen | AI Logic  

## 🚀 Project Overview

**AERON-V01** is a smart AI robot that combines vision, motion, and interaction. Built for DIYers, students, and engineers who want a multi-controller, WiFi-enabled, intelligent robotic platform.  
This robot detects faces, avoids obstacles, shows animated eyes, follows its master, and can be fully controlled remotely via the Blynk IoT platform.

---

## 🧠 Features

- 🎯 **Face + Object Detection & Tracking** via ESP32-CAM  
- 📶 **NodeMCU as Central WiFi Controller** (Handles Blynk, servos, motor drivers)
- 🧱 **Arduino UNO** for support tasks and extra sensor input
- 🎮 **Blynk Mobile Control Dashboard**
- 📡 **Ultrasonic Sensor** for obstacle avoidance
- 🔥 **IR Sensor** for proximity triggering
- 👀 **TFT Touchscreen Display** shows animated eyes with behavior states
  - Fear
  - Excitement (when it sees you)
  - Idle state
- 🧠 **AI "Follow Master" Mode** — turns it into a robotic pet
- 🌐 **Internet Controlled via Blynk WiFi**
- 📡 **Automatic Access Point Mode** if no WiFi found

---

## 🛠️ Hardware Components

| Component           | Purpose                               |
|---------------------|----------------------------------------|
| **NodeMCU**         | Main controller + WiFi + Blynk         |
| **ESP32-CAM**       | Face & object detection, streaming     |
| **Arduino UNO**     | Handles ultrasonic/IR + supports logic |
| **Ultrasonic Sensor** | Obstacle detection                   |
| **IR Sensor**       | Behavior trigger / proximity sensing   |
| **L298N Motor Driver** | Controls motor speed/direction     |
| **Servo Motors**    | Pan/tilt face tracking & eyes          |
| **TFT LCD**         | Animated eye expressions               |
| **Battery Pack**    | Power source                           |

---

## 📂 File Structure

