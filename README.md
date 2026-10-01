# First-Year EIE Engineering Projects

This repository documents the practical hardware engineering projects I built during my 1st year of Electronics and Instrumentation Engineering (EIE). 

---

## 🗑️ Project 1: Smart Waste Management Bin

### 📌 Project Overview
An automated, touch-free waste bin designed to improve hygiene and prevent the spread of germs in public or domestic environments. 

### 🛠️ Hardware Components Used
* **Microcontroller:** Arduino Uno (or equivalent microcontroller platform)
* **Sensor:** HC-SR04 Ultrasonic Sensor (used for distance measurement)
* **Actuator:** SG90 Servo Motor (used for physical mechanism control)
* **Power Supply:** 9V Battery / USB Power

### ⚙️ How It Works
1. The **Ultrasonic Sensor** continuously emits ultrasonic sound waves to monitor the area in front of the bin.
2. When a user brings their hand or trash close to the bin (within a set distance like 10-15 cm), the sensor detects the change in distance and sends a signal to the microcontroller.
3. The microcontroller processes this signal and activates the **Servo Motor**.
4. The servo motor rotates to automatically lift the bin lid open, holds it for 5 seconds, and then rotates back to close the lid automatically.

### 📷 Project Media
![Smart Waste Bin Photo](./smart_bin.jpg)

---

## ⚡ Project 2: Thermoelectric Generator (TEG) Energy Harvesting

### 📌 Project Overview
A green-energy generation experiment focused on capturing waste heat and converting it directly into usable electrical energy using the Seebeck effect.

### 🛠️ Hardware Components Used
* **TEG Module:** TEC1-12706 (Thermoelectric Cooler/Generator module)
* **Thermal Management:** Aluminum Heat Sinks & Thermal Paste
* **Voltage Regulation:** DC-DC Boost Converter Module (to step up low voltage)
* **Indicators:** Multimeter & low-power LED

### ⚙️ How It Works
1. The **TEG module** is placed between a heat source (like hot water or a heated surface) and a cold source (like ice or a heat sink exposed to air).
2. Due to the temperature difference across the module, electrons diffuse from the hot side to the cold side, generating a small DC voltage (the Seebeck Effect).
3. Because the initial voltage is too low, it is passed through a **DC-DC Boost Converter** to step up the voltage to a stable level (e.g., 5V).
4. This harvested energy is used to power a small electronic component, such as lighting up a test LED or showing a reading on a multimeter.

### 📷 Project Media
![TEG Experiment Photo](./teg_system.jpg)

