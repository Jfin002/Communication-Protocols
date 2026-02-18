# STM32F411VET6 Projects

A collection of embedded systems projects developed using the **STM32F411VET6** microcontroller.  
These projects focus on UART, SPI, I2C, IoT, sensor interfacing, and real-world applications.

---

## 📌 Microcontroller Overview

The **STM32F411VET6** is a 32-bit ARM Cortex-M4 microcontroller designed for high-performance embedded applications.

### Key Features
- ARM Cortex-M4 with FPU  
- 100 MHz Clock Frequency  
- 512 KB Flash | 128 KB SRAM  
- ADC (12-bit), DMA, Timers  
- USART, SPI, I2C, USB OTG  
- Low Power Modes  

### Pinout
![STM32 Pinout](https://github.com/user-attachments/assets/bcb766ee-6d64-48ed-9aaf-557b12a3e8de)

---

## 🛠 Development Tools
- STM32CubeIDE  
- STM32CubeMX  
- HAL / LL Drivers  
- ST-Link Programmer  

---

## 📂 Projects

---

## 📡 UART Bluetooth Control (HC-05)

Wireless LED control using STM32 and HC-05 via UART.

### Features
- Bluetooth-based control
- Mobile command interface
- Real-time response

### Project Images
<img src="https://github.com/user-attachments/assets/1deafa98-5ce0-4481-97fb-904bd466de73" width="300"/>
<img src="https://github.com/user-attachments/assets/24f418b1-cc2c-473e-843d-ce79be51ae78" width="300"/>

### Components
- STM32F411 Board  
- HC-05 Module  
- LED + Resistor  
- Android Phone  

### Commands
| Command | Action |
|---------|--------|
| on      | LED ON |
| off     | LED OFF |

---

## 🏠 Home Automation (Bluetooth)

Simple home automation using Bluetooth communication.

### Project Images
<img src="https://github.com/user-attachments/assets/f5495906-0cb2-491c-84c7-ace5ef989b2a" width="300"/>
<img src="https://github.com/user-attachments/assets/ce3833ba-ae07-4496-84fe-f1e4ae2d5874" width="300"/>

### Commands
| Command | Action |
|---------|--------|
| 1       | ON     |
| 0       | OFF    |

---

## 🌡️ Pressure & Temperature Monitoring (BMP280 - SPI)

Real-time temperature and pressure monitoring using BMP280.

### Project Images
<img src="https://github.com/user-attachments/assets/c3002d11-25cd-4d49-8c42-fffe193b091b" width="400"/>
<img src="https://github.com/user-attachments/assets/5e6b0856-10d8-48f9-938c-a43906d89389" width="400"/>

### Features
- SPI communication
- Sensor calibration
- Serial monitoring

---

## 🔗 I2C Communication

Demonstration of I2C master communication with external devices.

### Project Images
<img src="https://github.com/user-attachments/assets/e0edb617-fdcd-4bfd-9fb3-c55c278a0eb9" width="300"/>
<img src="https://github.com/user-attachments/assets/daaf24c4-68d2-410b-9e4a-90c01aa4412d" width="400"/>

### I2C Pins
| Pin | Function |
|-----|----------|
| PB8 | SCL      |
| PB9 | SDA      |

---

## 🚶 Smart Person Entry Monitor

Automatic people counter using Laser, LDR, OLED, and Buzzer.

### Project Image
<img src="https://github.com/user-attachments/assets/81edfbb8-50ca-4e13-a275-4ccf7d493a65" width="400"/>

### Features
- Beam interruption detection  
- OLED display output  
- Buzzer alert  

---

## ⚙️ Software Used
- STM32CubeIDE  
- STM32 HAL Drivers  
- Embedded C  
- UART / SPI / I2C Protocols  

---

## 📋 Other Mini Projects

- LED Blinking  
- LED with Switch  
- LDR Interface  
- IR Sensor  
- Soil Moisture Sensor  
- ADC (with Interrupt)  
- Timer & SysTick  
- UART / USART  
- SPI & I2C  
- Bluetooth Control  
- BMP280 Interface  

---

## 👨‍💻 Author

**Jeffin Paul**  
Electronics & Communication Engineer  

🔗 LinkedIn: https://www.linkedin.com/in/jeffin-paul-9b3a0b226  

---

## ⭐ If you found this useful, consider starring this repository!
