# WRC Micromouse – STM32 (Arduino IDE)

This project is a maze-solving autonomous robot built for the **WRC Micromouse Competition**, programmed using the **Arduino IDE** on an **STM32 microcontroller**.

---

## 🧠 Overview

Micromouse is a robotics challenge where a small robot must explore and solve an unknown maze in the fastest time. This repository contains the code, drivers, and algorithms powering our STM32-based robot.

The micromouse is equipped with:
- **IR Sensors** for wall detection  
- **Quadrature Encoders** to track movement  
- **Gyroscope** for precise turning  
- **Flood Fill Algorithm** for maze-solving  
- **Smooth path planning**, including diagonal movements

---

## 🔌 Hardware Components

- **STM32F103 "Blue Pill"** board (programmed via Arduino IDE)
- IR Sensors (e.g., TCRT5000 modules)
- MPU6050 or BNO085 for IMU data
- Wheel encoders
- Dual motor driver (DRV8833)
- 3.7V Li-ion battery + boost converter
- Custom chassis and PCB

---

## 📁 Repository Contents

- `Arduino_Code/` – Main control code and configuration
- `Drivers/` – Custom sensor/motor libraries
- `MazeSolver/` – Flood Fill and movement logic
- `Hardware/` – Schematics and PCB designs
- `Docs/` – Project images, logs, and reference materials

---

## 🎥 Demo

[Insert video or image link here showing the robot solving a maze]

---

## 🙌 Contributions

Pull requests and suggestions are welcome. Feel free to fork and experiment.

---

## ✍️ Author

**Utkrisht Tripathi**  
GitHub: [@UtkrishtTripathi](https://github.com/UtkrishtTripathi)

