# 🔧 STM32 Embedded Systems Internship Projects

### 👨‍💻 Author: [Omkar Sawant](https://github.com/OmkarSawant25)
> Collection of STM32-based embedded C projects developed during my internship.  
> Focused on mastering **peripheral interfacing**, **interrupt handling**, **UART communication**, **PWM control**, and **MODBUS protocol** implementation.

---

## 🧩 Overview
This repository contains multiple **STM32 microcontroller** projects demonstrating hands-on experience in **bare-metal embedded programming** and **hardware interfacing**.  
Each folder represents an individual experiment or concept implemented using **STM32CubeIDE / Keil µVision**.

---

## 📁 Project List

| Category | Folder Name | Description |
|-----------|--------------|-------------|
| **LED Control** | `LedBlink`, `LedLeft`, `LedRight`, `LedRing`, `LedStart` | Basic GPIO control and LED sequencing experiments. |
| **PWM Control** | `PWM_1`, `PWM_2`, `PWM_3`, `PWM_4_INTERRUPT` | Pulse Width Modulation for LED brightness and motor control. |
| **UART Communication** | `UART`, `UART_1` – `UART_5`, `UartInterrupt`, `UartReceive`, `UartRing`, `UartRecLed` | Serial data transmission and reception using interrupts and DMA. |
| **External Interrupts** | `ExternalInterrupt`, `TimerInterrupt` | Handling GPIO-triggered events using EXTI lines and NVIC. |
| **Timer Applications** | `Timer`, `TimerChannel`, `TimerRing` | Timer-based delays, counters, and multi-channel usage. |
| **RGB LED** | `RGB`, `RGB_MAIN`, `RGB_RAIN`, `RGB_RAINBOW`, `RGB_TEST`, `RGB_WS2812` | Multi-color LED control using PWM and WS2812 LED strips. |
| **MODBUS Protocol** | `MODBUS_1` – `MODBUS_7_DISCRETE_input` | Implementation of MODBUS RTU protocol (coil read/write, discrete input read). |
| **Miscellaneous** | `Receiver`, `NEW`, `NEWE`, `LedTimer` | Additional experiments and test codes. |

---

## ⚙️ Tools & Technologies

| Category | Tools Used |
|-----------|-------------|
| **Microcontroller** | STM32F103 / STM32F4 Series |
| **IDE** | STM32CubeIDE / Keil µVision |
| **Programming Language** | Embedded C |
| **Communication Protocols** | UART, MODBUS RTU |
| **Other Interfaces** | GPIO, Timers, PWM, EXTI |
| **Debugging** | ST-Link V2 |

---

## 🧠 Learning Outcomes
- Configuring and controlling **STM32 peripherals** (GPIO, UART, TIM, ADC).
- Implementing **interrupt-driven** applications and **event-based logic**.
- Designing **PWM-based control** for LEDs and motors.
- Understanding and coding **MODBUS communication** between master and slave.
- Managing **real-time embedded systems** using timers and NVIC priorities.

---

## 🚀 How to Run
1. Open the desired project folder in **STM32CubeIDE** or **Keil µVision**.
2. Connect your **STM32 board** (e.g., Nucleo / Blue Pill / Discovery).
3. Flash the code using **ST-Link**.
4. Observe output via **LEDs**, **serial monitor**, or connected peripherals.

---

## 📷 Example Demonstrations
- **LED Blink:** Basic GPIO toggle using delay loops.  
- **PWM RGB Control:** Smooth color fading on WS2812 LED strip.  
- **UART Receive LED:** LED toggles on UART data input.  
- **MODBUS Read Coil:** Communication between master and slave devices.  

---

## 🧩 Future Work
- Integration with **FreeRTOS** for multitasking.  
- Sensor interfacing (temperature, ultrasonic, IR).  
- IoT integration via ESP32 or MQTT protocols.  

---

## 🏁 Acknowledgement
Special thanks to my **QuroLabs Team** for guidance in embedded system fundamentals and hands-on microcontroller development.


---

## 📎 Keywords
`STM32` • `Embedded C` • `GPIO` • `UART` • `PWM` • `Interrupts` • `Timers` • `MODBUS` • `RGB LED` • `Microcontroller Programming`
