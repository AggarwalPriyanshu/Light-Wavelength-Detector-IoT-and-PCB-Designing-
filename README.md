# 🔬 Light Wavelength Detector (IoT & PCB Designing)


![IoT](https://img.shields.io/badge/Domain-IoT-blue)
![Embedded](https://img.shields.io/badge/Embedded-ESP32-success)
![PCB](https://img.shields.io/badge/PCB-Hand%20Designed-orange)
![Status](https://img.shields.io/badge/Status-Working-brightgreen)

## 📌 Project Overview
The **Light Wavelength Detector** is an IoT-enabled embedded hardware project designed to **detect and analyze light wavelengths** across the UV, visible, and near-infrared spectrum.  
The system uses an **ESP32**, **AS7341 spectral sensor**, and a **UV sensor**, combined with a **custom hand-designed PCB**, to provide real-time wavelength visualization using LEDs and serial data output.

This project emphasizes **core electronics understanding, sensor interfacing, and iterative PCB design**, rather than tool-dependent automation.

---

## 🎯 Key Features
- Detection of **UV, Visible (VIBGYOR), and Near-IR wavelengths**
- Real-time spectral sensing using **AS7341 (8-channel sensor)**
- LED-based visual indication for wavelength intensity
- PWM-based brightness control for accurate representation
- Serial data output for monitoring and plotting
- **Hand-designed PCB with multiple design iterations**
- ESP32-based architecture suitable for IoT expansion

---

## 🛠️ Hardware Components
- **ESP32 Development Board**
- **AS7341 Spectral Sensor**
- **UV Sensor (S12SD)**
- LEDs:
  - Violet
  - Blue
  - Green
  - Yellow
  - Orange
  - Red
  - Infrared
- Resistors, connectors, and passive components
- Custom PCB

---

## ✍️ PCB Design Approach
- PCB layout **designed manually on paper**
- Multiple design iterations for:
  - Signal clarity
  - Proper grounding
  - Component placement optimization
- Separate **Top Layer** and **Bottom Layer** routing
- Emphasis on understanding:
  - Signal flow
  - Power distribution
  - Sensor accuracy
- Final PCB implemented after iterative corrections and validation

> Hand-drawn layouts and final PCB images are included in the repository.

---

## 💻 Software & Programming
- **Arduino IDE**
- **ESP32 Board Package**
- **Adafruit AS7341 Library**
- I²C-based sensor communication
- PWM-based LED control

---

## 🔌 Working Principle
1. The **AS7341 sensor** captures intensity values from multiple wavelength bands.
2. The **UV sensor** measures ultraviolet light intensity via analog input.
3. ESP32 processes all spectral data in real time.
4. PWM signals control LED brightness corresponding to detected wavelength intensity.
5. Sensor data is streamed to the **Serial Monitor / Serial Plotter** for visualization.

---

## 📂 Repository Structure
```text
├── Arduino Code.txt
├── CIRCUIT DIAGRAM.jpeg
├── CIRCUIT DIAGRAM 2.jpeg
├── PERFECT CIRCUIT TOP LAYER.jpeg
├── PERFECT CIRCUIT DOWN LAYER.jpeg
├── Video of Working Project.mp4
└── README.md
```
## ▶️ Demonstration
A working demonstration video is included in the repository, showcasing:
- Live light wavelength detection
- LED intensity variation based on spectral strength
- Real-time data visualization via Serial Monitor / Plotter

---

## 🚀 Applications
- Optical and spectral analysis systems  
- Smart sensing and monitoring solutions  
- Educational electronics and lab experiments  
- Embedded system prototyping  
- IoT-ready hardware development  

---

## 📚 Learning Outcomes
- Practical sensor interfacing using **I²C and analog inputs**
- ESP32 **GPIO configuration and PWM-based control**
- Manual PCB planning, routing, and layout optimization
- Iterative hardware design and validation methodology
- Real-world embedded system debugging and testing

---

## 👤 Author

**Priyanshu Aggarwal**  
Electronics & Communication Engineering  

📧 Email: Priyanshuaggarwal.in@gmail.com  
💼 LinkedIn: https://linkedin.com/in/priyanshu1201  
💻 GitHub: https://github.com/AggarwalPriyanshu  

---

⭐ If you find this repository useful, feel free to star it!
