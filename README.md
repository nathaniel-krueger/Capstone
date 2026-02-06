# LiDAR Distance Measuring Tool

![C++](https://img.shields.io/badge/C%2B%2B-Embedded-blue)
![Embedded](https://img.shields.io/badge/Embedded-Systems-orange)
![Capstone](https://img.shields.io/badge/Capstone-Senior_Design-success)

A **senior capstone embedded system** that measures distance using a **TF03-180 LiDAR sensor** and displays results on a **2.4” SPI TFT LCD**.  
Firmware is written in **C++** and runs on an **ATSAMD51J19A (ARM Cortex-M4F)** microcontroller.

---

## What the System Does
- Measures distance up to **180 m** using LiDAR (UART)
- Displays distance, tilt, and battery status on a **240×320 TFT LCD**
- Logs measurement data to **microSD**
- Runs on **Li-ion battery** with AC charging and power-path control

---

## Verified Hardware (from design files)
- **MCU:** ATSAMD51J19A  
- **LiDAR:** Benewake TF03-180 (UART)  
- **Display:** NHD-2.4-240320CF-BSXV-F (SPI, ST7789 controller)  
- **Storage:** microSD card (SPI)  
- **Sensors:** IMU (I²C), ambient light photodiode  
- **Power:** AC → DC + 3-cell Li-ion battery, BQ24133 charger  

---

## Interfaces
- **UART:** LiDAR  
- **SPI:** LCD + microSD  
- **I²C:** IMU + fuel gauge  
- **GPIO / PWM:** Buttons, LEDs, LCD backlight  

---

## Firmware
- **Language:** C++  
- **Environment:** Embedded (bare-metal / HAL-based)  
- **Tools:** MPLAB X, ARM-GCC  

---

## Team – Capstone Design Team #6
- **Wasim Assad** – Display/UI & Presentation Lead  
- **Anas Sabha** – Project Integrator  
- **Omar Titi** – System & Power Design  
- **Priyansh Patel** – Manufacturing  
- **Nathan Krueger** – Safety & Compliance  

---

## License
Academic senior design project.
