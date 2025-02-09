# My Engineering Thesis: Measurement of electrical heart activity during exercise

This project is a system for measuring electrical heart activity (ECG) during physical exercise, integrating a custom-built hardware device with a mobile Android application for data visualization and analysis.




**The system consists of:**

A wearable ECG device based on the STM32F103C8T6 microcontroller.

A wireless data transmission module (Bluetooth HC-05).

An Android application (Java) for real-time ECG signal display and monitoring.


**Features:**

📡 Wireless ECG Signal Transmission – Real-time data transfer via Bluetooth HC-05.

📊 Live Data Visualization – ECG signals displayed on the Android app.

📁 Data Logging & Analysis – Recorded ECG signals can be analyzed later.

⚙️ Custom Hardware Design – Compact PCB layout with integrated power management.

🔋 Battery Powered – 18650 Li-ion rechargeable battery for portability.

**Hardware Components:**
The ECG device includes:
ECG Module (AD8232) – Signal acquisition.
STM32F103C8T6 – Microcontroller for signal processing.
Step-Down Converter (LM2596S) – Voltage regulation.
Custom PCB (FR4 laminate) – Circuit integration.
Bluetooth HC-05 – Wireless communication with the Android app.
Enclosure & Battery (18650 Li-ion) – Portable and safe operation.

![urzadzenie](https://github.com/user-attachments/assets/4fc39b81-2282-4e9c-93d8-005999a522c4)
![schemat plytki eagle](https://github.com/user-attachments/assets/cd961f95-cfa7-486a-8e71-90346545d6c2)




**Software Overview:**
The firmware for STM32 was developed using STM32 HAL libraries, configured in STM32CubeMX, and programmed in µVision IDE. The Android app was written in Java, featuring a user-friendly UI for ECG monitoring.

![aplikacja android](https://github.com/user-attachments/assets/ee9b7ff4-aca4-480d-a5df-7c95a6143b06)

![dzialanei aplikacji](https://github.com/user-attachments/assets/d1d64458-543f-48b8-873b-e13a94cbc03e)
![wykres po zmeczneiu sie ](https://github.com/user-attachments/assets/86437f06-be0d-4758-9e53-f8d7c268fcc5)

![przyblizenie](https://github.com/user-attachments/assets/c12b703b-3c4a-4611-9f1d-a756b3e685b5)

**Technologies Used:**

Embedded Systems: STM32F103C8T6, HAL Libraries

Android App: Java, Bluetooth API

ECG Signal Processing: AD8232

PCB Design & Power Management
